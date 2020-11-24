# Logic Synthesis Meets Machine Learning: Trading Exactness for Generalization

This repository contains the data and solutions from the teams participating in the [IWLS 2020 programming contest](https://storage.googleapis.com/iwls_contest_2020/ML2S.pdf)

The contest consists in learning a Boolean function from a training set, consisting in a small sample of random minterms of the function.
The functions are made available in [Espresso PLA format](https://ultraespresso.di.univr.it/assets/data/espresso/espresso5.pdf), and should be delivered in [binary AIGER format](http://fmv.jku.at/aiger/)

The Benchmarks is also available in this repository, and is composed by 100 functions in PLA, as follows: 

Function ID | Function Category
------------ | -------------
00-09 | 2 MSBs for *k-bits* adders, with *k* in {16, 32, 64, 128, 256}
10-19 | MSB of *k-bit* dividers and remainder circuits for *k* in {16, 32, 64, 128, 256}
20-29 | MSB and middle bit of *k-bit* multipliers for *k* in {8, 16, 32, 64, 128}
30-39 | *k-bit* comparators for *k* in {10, 20, ..., 100}
40-49 | LSB and middle bit of *k*-bit square-rooters with *k* in {16, 32, 64, 128, 256}
50-59 | 10 outputs of PicoJava designs with 16-200 inputs and roughly balanced on- & offset
60-69 | 10 outputs of MCNC i10 design with 16-200 inputs and roughly balanced on- & offset
70-79 | 5 other outputs from MCNC benchmakrs + 5 symmetric functions of 16 inputs 
80-89 | 10 binary classification problems from MNIST group comparison
90-99 | 10 binary classification problems from CIFAR-10 group comparison

The candidates did not know beforehand the Benchmarks functionality. For further discussion on the benchmark generation, and the team's solutions, please refer to the following paper: 



