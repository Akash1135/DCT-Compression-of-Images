# DCT-Compression-of-Images
Image Compression using DCT(DISCRETE COSINE TRANSFORM)
The discrete cosine transform (DCT) is a technique for converting a signal into elementary
frequency components. It is widely used in image compression. Here we develop some simple
functions to compute the DCT and to compress images. 





The One-Dimensional Discrete Cosine Transform
The discrete cosine transform of a list of n real numbers s(x), x = 0, ..., n-1, is the list of length n
given by:

S u( ) = 2 n C u( ) s x( ) cos
( ) 2x +1 uπ
x= 0 2n
n−1
ε u = 0,...,n
where C u( ) = 2
−1 2 for u = 0
= 1 otherwise
Each element of the transformed list S(u) is the inner (dot) product of the input list s(x) and a
basis vector. The constant factors are chosen so that the basis vectors are orthogonal and
normalized. The eight basis vectors for n = 8 are shown in Figure 1. The DCT can be written as
the product of a vector (the input list) and the n x n orthogonal matrix whose rows are the basis
vectors
