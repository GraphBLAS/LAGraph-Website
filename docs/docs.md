---
layout: default
title: API Documentation
nav_order: 3
has_children: true
permalink: /docs/docs
---

# LAGraph C API Documentation

LAGraph is primarily designed using the C programming language for the following reasons:
  * Maximize compatibility with the GraphBLAS C API
  * Least-common denominator for creating language bindings in other languages
  * Generally high performance and low-overhead
  * Portability across many different platforms and compilers

In this section, we describe the LAGraph algorithms and utilities, as well as how to use them effectively. We break the information into the following components:
  * **Function Prototype.** This is essentially the entry in the LAGraph header file and describes how to call the function.
  * **Parameter Description.** A description of each parameter in the function signature is provided.
  * **Theoretical Basis.** The underlying mathematics and/or theory of the algorithm is provided with references.
  * **Performance Concerns.** While LAGraph functions are meant to be flexible and easy to use, there may be specific use cases that will enable (or hinder) high-performance of the library implementation.
