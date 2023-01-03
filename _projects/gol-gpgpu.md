---
title: Game of Life on GPGPU
sub_title: "Master's Culminating Project"
date: 2021-05-07
tags: complete cuda
---

A Game of Life on CUDA implementation, done for [CSE 603 - Parallel and Distributed Processing](https://cse.buffalo.edu/~jzola/PDP/) at the University at Buffalo, with the aim to use integer bitwise operations to speed up traditional CUDA implementations of the Game of Life. Measured a speedup of over 600x over the naive CPU implementation, with a little over a billion cell updates per second.

[See the project on GitHub](https://github.com/nbarrios1337/bitwise-GoL-GPGPU)
