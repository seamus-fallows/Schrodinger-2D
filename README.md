# Schrödinger-2D

This notebook transforms images into 2D potentials for the time-independent Schrödinger equation and numerically solves for the eigenstates using the method of finite differences.

## Features

* Image Processing: Functions for grayscale conversion, trimming, resizing, and displaying images.
* Numerics: Constructs the discretized 2D Laplacian operator as a sparse matrix and solves the eigenvalue problem using `scipy.sparse.linalg.eigsh`
* Visualization: Contour and 3D surface plots for probability density functions (PDFs) of quantum states.
* Time-Dependent Wave Functions: Constructs and animates the time evolution of superposition states.

## Examples

The notebook includes examples using various images like 'star.png', 'sphere.png', 'koch.png', and a generated circular harmonic potential. For each example, it solves for eigenvalues and eigenvectors, constructs PDFs, and visualizes them. It also includes animations to demonstrate the time-dependent behavior of superposition states.

![Example eigenstate](https://github.com/seamus-fallows/Schrodinger-2D/blob/main/koch5.png?raw=true)

![Example animation](https://github.com/seamus-fallows/Schrodinger-2D/blob/main/animation.gif?raw=true)

## Note

The animations may take some time to generate, depending on the discritization resolution.
