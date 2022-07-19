---
sequence_id: 5
speaker: Aaron Roth
title: Robust Multivalid Uncertainty Quantification
time: 1100
#affil: 
webpage: https://www.cis.upenn.edu/~aaroth/
abstract: When deciding how to act as a function of our predictions, it is important to be able to quantify the uncertainty in our predictions. Traditional conformal prediction methods give a very simple, general way of attaching uncertainty sets to black box predictions, but have two well-known shortcomings - first, they generally require that the future look like the past --- i.e. that the data be i.i.d. or exchangeable. While mathematically convenient, this often fails in the face of various kinds of distribution shift. Second, they provide marginal coverage guarantees --- i.e. guarantees that are valid only as averaged over all instances. This can paper over weaknesses of a model on small sub-populations, which is especially worrisome when we are making predictions about people. I'll present an exciting (I think :-) new method that solves both of these problems; it can endow arbitrary black box predictors with prediction sets that promise statistically optimal empirical coverage guarantees not just marginally, but conditionally on a large number of arbitrarily defined (possibly intersecting!) subsets of the data, and does so without requiring any distributional assumptions at all --- i.e. it has guarantees even against adversarially chosen streams of data.
---