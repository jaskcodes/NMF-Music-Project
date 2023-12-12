# Music Creation through Non-negative Matrix Factorization
Colaborators: Trenton Wesley, Sarang Joshi

### Introduction

Non-negative matrix factorization (NMF) refers to a group of linear algebra techniques that allows
one to decompose a matrix into a product of two matrices. With NMF, a matrix, V is typically
factorized into two matrices, W and H. Commonly, W is referred to as the feature matrix and H
referred to as the coefficients matrix. All three of these matrices have a non-negativity constraint
that requires all elements to be greater than or equal to 0. This non-negativity constraint can be very
useful for interpretability. 

We explore non-negative matrix factorization (NMF) in the context of
music samples. We show that NMF is a useful method for capturing the features
of audio files. We also show that different loss functions in NMF algorithms can
lead to a significant difference in the features captured. Finally, we successfully
combine the features of different music samples to generate new music.
