# Logic Synthesis Meets Machine Learning: Trading Exactness for Generalization 

This repository contains the benchmarks for the [IWLS 2020 programming contest](https://arxiv.org/abs/2012.02530).

The contest goal was to learn a Boolean function from a training set consisting of a small sample of random minterms of the function. The solutions were evaluated on a held-out set of minterms. The teams had the goal of maximizing the accuracy of the model while staying within a limit of 5,000 AIG nodes.
The functions are provided in [Espresso PLA format](https://ultraespresso.di.univr.it/assets/data/espresso/espresso5.pdf) and the resulting models should be delivered in [binary AIGER format](http://fmv.jku.at/aiger/). The instructions provided to the participants are [here](https://github.com/iwls2020-lsml-contest/iwls2020-lsml-contest/blob/main/contest_description.pdf).


The benchmarks are also available in this repository and is composed of 100 functions in PLA, as follows: 

Function ID | Function Category
------------ | -------------
00-09 | 2 MSBs for *k-bits* adders, with *k* in {16, 32, 64, 128, 256}
10-19 | MSB of *k-bit* dividers and remainder circuits for *k* in {16, 32, 64, 128, 256}
20-29 | MSB and middle bit of *k-bit* multipliers for *k* in {8, 16, 32, 64, 128}
30-39 | *k-bit* comparators for *k* in {10, 20, ..., 100}
40-49 | LSB and middle bit of *k*-bit square-rooters with *k* in {16, 32, 64, 128, 256}
50-59 | 10 outputs of PicoJava designs with 16-200 inputs and roughly balanced on- & offset
60-69 | 10 outputs of MCNC i10 design with 16-200 inputs and roughly balanced on- & offset
70-79 | 5 other outputs from MCNC benchmarks + 5 symmetric functions of 16 inputs 
80-89 | 10 binary classification problems from MNIST group comparison
90-99 | 10 binary classification problems from CIFAR-10 group comparison

For further details on the contest including details on the benchmarks as well as the solutions of the different teams and their performance, please refer to our [arXiv paper](https://arxiv.org/abs/2012.02530).


