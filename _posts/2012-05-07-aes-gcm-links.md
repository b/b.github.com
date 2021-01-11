---
layout: post
title: "AES-GCM Implementation & Analysis Papers"
---

# AES-GCM Implementation & Analysis Papers 

For some very good and very boring reasons I have been digging into AES-GCM (Galois/Counter Mode) implementation.  I found a number of interesting papers analyzing GCM and describing a variety of interesting aspects of secure, fast implementation.

## Analysis

* [GCM, GHASH and Weak Keys](http://www.ecrypt.eu.org/hash2011/proceedings/hash2011_03.pdf), Saarinen, 2011
* [Cache-collision Timing Attacks Against AES-GCM](http://dspace.udel.edu:8080/dspace/bitstream/handle/19716/9765/Bonan_Huang_thesis.pdf), Huang, 2010

## Implementation

* [Faster and Timing-Attack Resistant AES-GCM](http://eprint.iacr.org/2009/129.pdf), Käsper & Schwabe, 2009
* [Software Optimizations for Cryptographic Primitives on General Purpose x86_64 platforms](http://2011.indocrypt.org/slides/gueron.pdf), Gueron, 2012
* [Optimized Galois-Counter-Mode Implementation on Intel® Architecture Processors](http://download.intel.com/design/intarch/PAPERS/324194.pdf), Gopal, et al, 2010
* [Fast Cryptographic Computation on IA Processors Via Function Stitching](http://download.intel.com/design/intarch/PAPERS/323686.pdf), Gopal, et al, 2010
