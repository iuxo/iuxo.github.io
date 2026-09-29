# Overview

This repo contains a starter website that contains information about me, blog posts, and started data analysis on some data sets.

# Version and Build Requirements
This project makes use of
`Quarto - 1.10.18`
`uv - 0.12.13 linux`
`R - 4.6.1.`

Install these 3 first before proceeding with the rest of the installation.

`Python - 3.14` (can be installed after uv)

# Installation Guide
Installation Guide for Linux machines.
1. Clone the repo. `git clone git@github.com:iuxo/iuxo.github.io.git`
2. Navigate into the cloned repo. `cd iuxo.github.io`
3. In Terminal, get the Python packages `uv sync`.
4. To open locally, run `uv run quarto preview`.
5. The live site is located on `https://iuxo.github.io/` while the local site is on `http://localhost:3840/` where your port may vary, depending on your machine.
6. The data comes installed in the `palmerpenguins` package in python, and `mtcars` library in R.

