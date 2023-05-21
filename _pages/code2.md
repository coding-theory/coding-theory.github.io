---
layout: archive
title: "Code2"
permalink: /code2/
author_profile: false
redirect_from: 
  - /direct_to_code2
---

{% include base_path %}

Database for the paper "Construction of linear codes with various Hermitian hull dimensions and related EAQECCs"

## Quaternary linear codes with two-dimensional hull (h=2)

n=4

[4, 2, 2] Quasicyclic of degree 2 Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   1]  
[  0   1   1   0]  
_______________________________________

n=5

[5, 2, 4] Cyclic Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   1   w   w]  
[  0   1   w   w   1]  
[5, 3, 3] Cyclic Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   1 w^2]  
[  0   1   0 w^2 w^2]  
[  0   0   1 w^2   1]  
_______________________________________

n=6

[6, 2, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   1 w^2 w^2]  
[  0   1   0 w^2 w^2   1]  

[6, 3, 3] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   1 w^2 w^2]  
[  0   1   0   0   1   1]  
[  0   0   1   1   0 w^2]  

[6, 4, 2] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   1   w]  
[  0   1   0   0 w^2   1]  
[  0   0   1   0   0   1]  
[  0   0   0   1 w^2   0]  
_______________________________________

n=7

[7, 2, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   1 w^2 w^2   0]  
[  0   1   0 w^2 w^2   1   0]  

[7, 3, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0 w^2 w^2   w   1]  
[  0   1   0   0   1   1   1]  
[  0   0   1   1   1   w w^2]  

[7, 4, 3] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   1 w^2   w]  
[  0   1   0   0   w   1   w]  
[  0   0   1   0   0   1   1]  
[  0   0   0   1   1   0 w^2]  

[7, 5, 2] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   1]  
[  0   1   0   0   0   1 w^2]  
[  0   0   1   0   0 w^2   1]  
[  0   0   0   1   0   0   w]  
[  0   0   0   0   1 w^2 w^2]  
_______________________________________

n=8

[8, 2, 6] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   1 w^2 w^2   w   0   w]  
[  0   1   w   w   0 w^2 w^2   1]  

[8, 3, 5] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0 w^2   w   0   1   1]  
[  0   1   0   0   1   1   1   1]  
[  0   0   1   1   0   1   1   w]  

[8, 4, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   w   w   0 w^2]  
[  0   1   0   0   1   1   1 w^2]  
[  0   0   1   0   0   1   1   1]  
[  0   0   0   1   1   0   1   1]  

[8, 5, 3] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0 w^2   1   1]  
[  0   1   0   0   0   w   0   1]  
[  0   0   1   0   0 w^2   1   w]  
[  0   0   0   1   0   0   1   1]  
[  0   0   0   0   1   1   1   w]  

[8, 6, 2] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0 w^2   1]  
[  0   1   0   0   0   0   w   1]  
[  0   0   1   0   0   0   1   0]  
[  0   0   0   1   0   0 w^2   1]  
[  0   0   0   0   1   0   0   1]  
[  0   0   0   0   0   1 w^2   w]  
_______________________________________

n=9

[9, 2, 6] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   1 w^2 w^2   w   0   w   0]  
[  0   1   w   w   0 w^2 w^2   1   0]  

[9, 3, 5] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0 w^2   w   0   1   1   0]  
[  0   1   0   0   1   1   1   1   0]  
[  0   0   1   1   0   1   1   w   0]  

[9, 4, 5] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   w   w w^2   1   w]  
[  0   1   0   0 w^2   w   0   1   1]  
[  0   0   1   0   0   1   1   1   1]  
[  0   0   0   1   1   0   1   1   w]  

[9, 5, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   1 w^2   w   1]  
[  0   1   0   0   0   w   w   0 w^2]  
[  0   0   1   0   0   0   w w^2   1]  
[  0   0   0   1   0   0   1   1   1]  
[  0   0   0   0   1   1   w   w w^2]  

[9, 6, 3] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0 w^2   1]  
[  0   1   0   0   0   0   0   1 w^2]  
[  0   0   1   0   0   0 w^2   w w^2]  
[  0   0   0   1   0   0 w^2   1   w]  
[  0   0   0   0   1   0   0   1   1]  
[  0   0   0   0   0   1   1   1   w]  

[9, 7, 2] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0 w^2]  
[  0   1   0   0   0   0   0   1 w^2]  
[  0   0   1   0   0   0   0   0   w]  
[  0   0   0   1   0   0   0   1   w]  
[  0   0   0   0   1   0   0 w^2 w^2]  
[  0   0   0   0   0   1   0   1 w^2]  
[  0   0   0   0   0   0   1 w^2   w]  
_______________________________________

n=10

[10, 2, 8] Cyclic Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   1   w   w   1   0   1   w   w]  
[  0   1   w   w   1   0   1   w   w   1]  

[10, 3, 6] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   1   1   1   1   w w^2   0]  
[  0   1   0   1 w^2 w^2   1   0   1 w^2]  
[  0   0   1 w^2 w^2   1   0   1 w^2 w^2]  

[10, 4, 6] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   w   1   0   1 w^2 w^2]  
[  0   1   0   0 w^2   1 w^2   w w^2   0]  
[  0   0   1   0   0   1   1   1   1   1]  
[  0   0   0   1   1   0   1   1   w w^2]  

[10, 5, 5] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0 w^2   w   1 w^2   0]  
[  0   1   0   0   0 w^2   1   1   0   w]  
[  0   0   1   0   0 w^2   w   0   1   1]  
[  0   0   0   1   0   0   1   1   1   1]  
[  0   0   0   0   1   1   0   1   1   w]  

[10, 6, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   w w^2   1   w]  
[  0   1   0   0   0   0   w w^2   w   0]  
[  0   0   1   0   0   0 w^2 w^2   0   w]  
[  0   0   0   1   0   0   1   1   w   w]  
[  0   0   0   0   1   0   0   1   1   1]  
[  0   0   0   0   0   1   1   w   w w^2]  

[10, 7, 3] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0 w^2   1   0]  
[  0   1   0   0   0   0   0   1   w   1]  
[  0   0   1   0   0   0   0   0 w^2   w]  
[  0   0   0   1   0   0   0   1 w^2   1]  
[  0   0   0   0   1   0   0   w w^2 w^2]  
[  0   0   0   0   0   1   0   0   1   1]  
[  0   0   0   0   0   0   1   1   1   w]  

[10, 8, 2] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   0   1]  
[  0   1   0   0   0   0   0   0   1   1]  
[  0   0   1   0   0   0   0   0   w w^2]  
[  0   0   0   1   0   0   0   0   1   1]  
[  0   0   0   0   1   0   0   0   1   w]  
[  0   0   0   0   0   1   0   0   1 w^2]  
[  0   0   0   0   0   0   1   0   1   0]  
[  0   0   0   0   0   0   0   1   w   1]  
_______________________________________

n=11

[11, 2, 8] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   1   w   w   1   0   1   w   w   0]  
[  0   1   w   w   1   0   1   w   w   1   0]  

[11, 3, 7] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   w   1   w   w   1 w^2 w^2 w^2]  
[  0   1   0   w   0   1   w   w   0 w^2   1]  
[  0   0   1   0 w^2 w^2   w   0   1   1 w^2]  

[11, 4, 6] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   w   w   1   w   w w^2   w]  
[  0   1   0   0   w w^2   w w^2   w   w   1]  
[  0   0   1   0   w w^2   1   0 w^2   w   0]  
[  0   0   0   1   0   1 w^2 w^2 w^2   0 w^2]  

[11, 5, 5] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   w   0   1 w^2   1   w   0]  
[  0   1   0   0   w   0   w   1 w^2   0   w]  
[  0   0   1   0   w   0   1   w   w   0 w^2]  
[  0   0   0   1   0   0 w^2   0   1 w^2   w]  
[  0   0   0   0   0   1   0 w^2   w w^2   1]  

[11, 6, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   w w^2   1   w   0]  
[  0   1   0   0   0   0   w w^2   w   0   0]  
[  0   0   1   0   0   0 w^2 w^2   0   w   0]  
[  0   0   0   1   0   0   1   1   w   w   0]  
[  0   0   0   0   1   0   0   1   1   1   0]  
[  0   0   0   0   0   1   1   w   w w^2   0]  

[11, 7, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   1   0 w^2   w]  
[  0   1   0   0   0   0   0   1   0   1   1]  
[  0   0   1   0   0   0   0   1   1   w   0]  
[  0   0   0   1   0   0   0   1   w   1   w]  
[  0   0   0   0   1   0   0   0   w w^2   1]  
[  0   0   0   0   0   1   0   0   1   1   1]  
[  0   0   0   0   0   0   1   1   w   w w^2]  

[11, 8, 3] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   w   0   1]  
[  0   1   0   0   0   0   0   0   0   w w^2]  
[  0   0   1   0   0   0   0   0   1 w^2   0]  
[  0   0   0   1   0   0   0   0   w   0   w]  
[  0   0   0   0   1   0   0   0   w   0 w^2]  
[  0   0   0   0   0   1   0   0   w w^2 w^2]  
[  0   0   0   0   0   0   1   0   0   1   1]  
[  0   0   0   0   0   0   0   1   1   1   w]  

[11, 9, 2] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   0 w^2 w^2]  
[  0   1   0   0   0   0   0   0   0   0 w^2]  
[  0   0   1   0   0   0   0   0   0 w^2   1]  
[  0   0   0   1   0   0   0   0   0   1 w^2]  
[  0   0   0   0   1   0   0   0   0   w   1]  
[  0   0   0   0   0   1   0   0   0   w   w]  
[  0   0   0   0   0   0   1   0   0   w   w]  
[  0   0   0   0   0   0   0   1   0   0   1]  
[  0   0   0   0   0   0   0   0   1   1 w^2]  
_______________________________________

n=12

[12, 2, 8] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   1   w   w   1   0   1   w   w   0   0]  
[  0   1   w   w   1   0   1   w   w   1   0   0]  

[12, 3, 8] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   1   1   w   0   1   w w^2   w   1]  
[  0   1   0   w   1 w^2   1   0   1   1   w w^2]  
[  0   0   1   1   1   1   1   w   1   0 w^2   w]  

[12, 4, 6] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0 w^2   0   w   w   1   1   0   w]  
[  0   1   0   0 w^2   0 w^2   1 w^2 w^2   w   0]  
[  0   0   1   0 w^2   0   w w^2   w   0   0   1]  
[  0   0   0   1   1   0   0 w^2 w^2   1   w w^2]  

[12, 5, 6] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   1   0   0 w^2   w   1 w^2   0 w^2]  
[  0   1   0   1   0   0   w   0 w^2   1   w   w]  
[  0   0   1   w   0   0   1   w   0 w^2   1   0]  
[  0   0   0   0   1   0   1   w   1   w   1 w^2]  
[  0   0   0   0   0   1   1 w^2 w^2   1   w w^2]  

[12, 6, 5] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   1 w^2   1   0 w^2   0]  
[  0   1   0   0   0   0   0   1 w^2   1   0 w^2]  
[  0   0   1   0   0   0   w w^2 w^2 w^2   w   w]  
[  0   0   0   1   0   0   1   0   w w^2   1 w^2]  
[  0   0   0   0   1   0   w   w   w   w   0 w^2]  
[  0   0   0   0   0   1   w   1   0   w   1   w]  

[12, 7, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   1   0 w^2   w   0]  
[  0   1   0   0   0   0   0   1   0   1   1   0]  
[  0   0   1   0   0   0   0   1   1   w   0   0]  
[  0   0   0   1   0   0   0   1   w   1   w   0]  
[  0   0   0   0   1   0   0   0   w w^2   1   0]  
[  0   0   0   0   0   1   0   0   1   1   1   0]  
[  0   0   0   0   0   0   1   1   w   w w^2   0]  

[12, 8, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   1   0   1 w^2]  
[  0   1   0   0   0   0   0   0   1   1   0 w^2]  
[  0   0   1   0   0   0   0   0   w   0 w^2 w^2]  
[  0   0   0   1   0   0   0   0   1   1   w   0]  
[  0   0   0   0   1   0   0   0   1   w   1   w]  
[  0   0   0   0   0   1   0   0   0   w w^2   1]  
[  0   0   0   0   0   0   1   0   0   1   1   1]  
[  0   0   0   0   0   0   0   1   1   w   w w^2]  

[12, 9, 3] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   0   w   1   w]  
[  0   1   0   0   0   0   0   0   0   1   w   1]  
[  0   0   1   0   0   0   0   0   0 w^2 w^2 w^2]  
[  0   0   0   1   0   0   0   0   0   w   1   0]  
[  0   0   0   0   1   0   0   0   0 w^2   w   1]  
[  0   0   0   0   0   1   0   0   0   w   0   1]  
[  0   0   0   0   0   0   1   0   0 w^2   1   w]  
[  0   0   0   0   0   0   0   1   0   0   1   1]  
[  0   0   0   0   0   0   0   0   1   1   1   w]  

[12, 10, 2] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   0   0 w^2   1]  
[  0   1   0   0   0   0   0   0   0   0   1 w^2]  
[  0   0   1   0   0   0   0   0   0   0   1   w]  
[  0   0   0   1   0   0   0   0   0   0   1   w]  
[  0   0   0   0   1   0   0   0   0   0   w w^2]  
[  0   0   0   0   0   1   0   0   0   0   w   w]  
[  0   0   0   0   0   0   1   0   0   0   1 w^2]  
[  0   0   0   0   0   0   0   1   0   0   w   0]  
[  0   0   0   0   0   0   0   0   1   0   0   w]  
[  0   0   0   0   0   0   0   0   0   1   w   w]  
_______________________________________

n=13

[13, 2, 10] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   1   0   0 w^2   1 w^2 w^2 w^2 w^2   1 w^2]  
[  0   1 w^2   1   w   0   w   1   w w^2   1   0   w]  

[13, 3, 9] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0 w^2   1   w w^2   0   1 w^2   0   1   w]  
[  0   1   0   0   1   1   1   w   w   w w^2 w^2 w^2]  
[  0   0   1   1   1   1   1   1   1   1   1   1   1]  

[13, 4, 8] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0 w^2   w   1 w^2   1   0   1 w^2   1]  
[  0   1   0   0   w w^2 w^2 w^2   0   w   w   0 w^2]  
[  0   0   1   0 w^2   1   0   0   w w^2   w   w   w]  
[  0   0   0   1   w   0   1   w w^2 w^2   w   1   0]  

[13, 5, 6] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   1   0   0   w   0   w   1   1   0]  
[  0   1   0   0   1   0   0   0   1 w^2   1   0 w^2]  
[  0   0   1   0   w   0   0   1 w^2   1   0   w   w]  
[  0   0   0   1   w   0   0 w^2 w^2   w   w   1   1]  
[  0   0   0   0   0   1   0   0   w   w   1 w^2   1]  

[13, 6, 6] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   w   0   w w^2   1   0   0   w]  
[  0   1   0   0   0   1   0   0 w^2 w^2 w^2   0 w^2]  
[  0   0   1   0   0 w^2   0   0   w w^2   0   w w^2]  
[  0   0   0   1   0 w^2   0   w w^2   w   0 w^2   0]  
[  0   0   0   0   1   1   0   w   0 w^2   w w^2 w^2]  
[  0   0   0   0   0   0   1   0   w   w   1 w^2   1]  

[13, 7, 5] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   0   1 w^2   1 w^2]  
[  0   1   0   0   0   0   w   0   1   0 w^2   0   w]  
[  0   0   1   0   0   0   0   0   1   0   1   1   w]  
[  0   0   0   1   0   0 w^2   0   0   w   1 w^2   w]  
[  0   0   0   0   1   0   w   0 w^2   w   w   0   w]  
[  0   0   0   0   0   1   1   0 w^2   w   1   1   0]  
[  0   0   0   0   0   0   0   1   w   1   w   1   w]  

[13, 8, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   w w^2   0   w   1]  
[  0   1   0   0   0   0   0   0   w w^2   1   w   0]  
[  0   0   1   0   0   0   0   0   w   1 w^2 w^2 w^2]  
[  0   0   0   1   0   0   0   0 w^2   1 w^2   w   1]  
[  0   0   0   0   1   0   0   0   w   1   0   w w^2]  
[  0   0   0   0   0   1   0   0   1   1   1   w w^2]  
[  0   0   0   0   0   0   1   0 w^2 w^2   1   0   1]  
[  0   0   0   0   0   0   0   1 w^2 w^2   w w^2   1]  

[13, 9, 4] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   0 w^2   0 w^2   1]  
[  0   1   0   0   0   0   0   0   0   w   w   0   w]  
[  0   0   1   0   0   0   0   0   0   w   0 w^2   w]  
[  0   0   0   1   0   0   0   0   0 w^2   w w^2   w]  
[  0   0   0   0   1   0   0   0   0   0 w^2   w   1]  
[  0   0   0   0   0   1   0   0   0   w   w   1   1]  
[  0   0   0   0   0   0   1   0   0   1   1   w   w]  
[  0   0   0   0   0   0   0   1   0   0   1   1   1]  
[  0   0   0   0   0   0   0   0   1   1   w   w w^2]  

[13, 10, 3] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   0   0   1 w^2   w]  
[  0   1   0   0   0   0   0   0   0   0 w^2   1   0]  
[  0   0   1   0   0   0   0   0   0   0   1 w^2 w^2]  
[  0   0   0   1   0   0   0   0   0   0   1 w^2   0]  
[  0   0   0   0   1   0   0   0   0   0   1   w   1]  
[  0   0   0   0   0   1   0   0   0   0   0 w^2   w]  
[  0   0   0   0   0   0   1   0   0   0   1 w^2   1]  
[  0   0   0   0   0   0   0   1   0   0   w w^2 w^2]  
[  0   0   0   0   0   0   0   0   1   0   0   1   1]  
[  0   0   0   0   0   0   0   0   0   1   1   1   w]  

[13, 11, 2] Linear Code over GF(2^2)  
Generator matrix:  
[  1   0   0   0   0   0   0   0   0   0   w   0 w^2]  
[  0   1   0   0   0   0   0   0   0   0   0   0 w^2]  
[  0   0   1   0   0   0   0   0   0   0   1   0   1]  
[  0   0   0   1   0   0   0   0   0   0   w   0 w^2]  
[  0   0   0   0   1   0   0   0   0   0 w^2   0   0]  
[  0   0   0   0   0   1   0   0   0   0 w^2   0   0]  
[  0   0   0   0   0   0   1   0   0   0   w   0   w]  
[  0   0   0   0   0   0   0   1   0   0   1   0   1]  
[  0   0   0   0   0   0   0   0   1   0   w   0   1]  
[  0   0   0   0   0   0   0   0   0   1   1   0   w]  
[  0   0   0   0   0   0   0   0   0   0   0   1 w^2]  
