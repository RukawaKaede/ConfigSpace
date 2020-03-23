# New feature in this repository
Add support for "fixed_dims" in "get_one_exchange_neighbourhood" and "sample_configuration" methods.

It allows us to fix partial CategoricalHyperparameter in ConfigurationSpace and sample the remaining hyperparameters.

See test/test_util.py 'test_get_one_exchange_neighbourhood' and test/test_configuration_space.py 'test_sample_configuration',

the code under the comment '# test fixed_dims' shows how to use it.

# ConfigSpace

A simple python module to manage configuration spaces for algorithm configuration
and hyperparameter optimization tasks. Includes various scripts to translate 
between different text formats for configuration space description. 
Distributed under BSD 3-clause, see LICENSE except all files in the directory
ConfigSpace.nx, which are copied from the networkx package and licensed
under a BSD license.

[![Build Status](https://travis-ci.org/automl/ConfigSpace.svg?branch=master)](https://travis-ci.org/automl/ConfigSpace)

The documentation can be found at [https://automl.github.io/ConfigSpace/master/](https://automl.github.io/ConfigSpace/master/).
Further examples can be found in the [SMAC documentation](https://automl.github.io/SMAC3/stable/quickstart.html#using-smac-in-python-svm).

## Citing the ConfigSpace

```bibtex
@article{
    title   = {BOAH: A Tool Suite for Multi-Fidelity Bayesian Optimization & Analysis of Hyperparameters},
    author  = {M. Lindauer and K. Eggensperger and M. Feurer and A. Biedenkapp and J. Marben and P. Müller and F. Hutter},
    journal = {arXiv:1908.06756 {[cs.LG]}},
    date    = {2019},
}
```
