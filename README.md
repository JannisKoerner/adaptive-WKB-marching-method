<h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about">About</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#help">Help</a></li>
    <li><a href="#license">License</a></li>
   </ol>

## About

This is a MATLAB tool for solving numerically the highly oscillatory 1D Schrödinger equation

<img src="https://github.com/JannisKoerner/adaptive-WKB-marching-method/blob/main/schr%C3%B6dinger_equation.png" width="300" height="45">

Here, a(x) is a real valued coefficient function bounded away from zero and epsi is the rescaled Planck constant 0 < epsi << 1.

The routine automatically switches between a standard Runge-Kutta solver and a WKB-based stepping procedure.

The whole program directly corresponds to our recently submitted article: J. Körner, A. Arnold, K. Döpfner, WKB-based scheme with adaptive step size control for the Schrödinger equation in the highly oscillatory regime. A preprint is available in the archive [arXiv:2102.03107](https://arxiv.org/abs/2102.03107).

The main program is "adaptive_WKB_marching_method.m", which, depending on the users input, might or might not call the numerical integration routine "clenshaw_curtis.m" (see also [here](#help) for help).

## Getting Started

### Prerequisites

To run the program the following requirements are needed:
* MATLAB

### Installation

Just clone the repository
   ```sh
   git clone https://github.com/JannisKoerner/adaptive-WKB-marching-method.git
   ```
or download it manually and make sure the folder is added to the MATLAB search path.
## Usage

For a quick start you can just run the example file "Test_adaptive_WKB_marching_method_Airy.m" or "Test_adaptive_WKB_marching_method_PCF.m".

<img src="https://github.com/JannisKoerner/adaptive-WKB-marching-method/blob/main/Airy_example.png" width="800" height="300">

## Help

There are short documentations available, just type the following commands into your MATLAB console:
```sh
   doc adaptive_WKB_marching_method
   ```
```sh
   doc clenshaw_curtis
   ```

## License

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
