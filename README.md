## About

This is a MATLAB programm for solving numerically the highly oscillatory 1D Schrödinger equation

<img src="https://github.com/JannisKoerner/adaptive-WKB-marching-method/blob/main/schr%C3%B6dinger_equation.png" width="400" height="60">

Here, a(x) is a real valued coefficient function bounded away from zero and epsi is the rescaled Planck constant 0 < epsi << 1.

The routine automatically switches between a standard Runge-Kutta solver and a WKB-based stepping procedure.

## Getting Started

### Prerequisites

To run the programm the following requirements are needed:
* MATLAB

### Installation

Just clone the repository
   ```sh
   git clone https://github.com/JannisKoerner/adaptive-WKB-marching-method.git
   ```

## Usage

For a quick start you can just run the example file "Test_adaptive_WKB_marching_method_Airy.m" or "Test_adaptive_WKB_marching_method_PCF.m".

<img src="https://github.com/JannisKoerner/adaptive-WKB-marching-method/blob/main/Airy_example.png" width="800" height="300">

## License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
