# The Bandwagon Effect: Not Just Another Bias
This repository contains the code used for the experiments in "The Bandwagon Effect: Not Just Another Bias" published at ICTIR 2022 ([preprint available](https://arxiv.org/abs/2206.12701)).

Citation
--------

If you use this code to produce results for your scientific publication, or if you share a copy or fork, please refer to our ICTIR 2022 paper:
```
@inproceedings{knyazev2022bandwagon,
  Author = {Knyazev, Norman and Oosterhuis, Harrie},
  Booktitle = {Proceedings of the 2022 ACM SIGIR International Conference on the Theory of Information Retrieval (ICTIR '22)}
  Organization = {ACM},
  Title = {The Bandwagon Effect: Not Just Another Bias},
  Year = {2022}
}
```

License
-------

The contents of this repository are licensed under the [MIT license](LICENSE). If you modify its contents in any way, please link back to this repository.

Usage
-------

This code makes use of [Python 3](https://www.python.org/) and the following packages: [jupyter](https://jupyter.org), [matplotlib](https://matplotlib.org), [numpy](https://numpy.org/), [scipy](https://scipy.org) and [tqdm](https://tqdm.github.io). Make sure they are installed.

There are three files, which can be accessed by running `jupyter notebook .` in the project folder.

`lambda_estimation.ipynb` is used to obtain the (mis)estimated lambda values under a strong bandwagon effect, as described in Section 6.1.

`figure3.ipynb` is used to generate Figure 3.

`figure4.ipynb` is used to generate individual subfigures from Figure 4. Variables `a` and `b` can be used to modify the strength of the bandwagon effect. Variables `a_hat` and `b_hat` can be used to provide (mis)estimated lambda values to all estimators. In case of memory limitations, there is an option to calculate and save, or load predictions for a subset of estimators by running the cells marked as `OPTIONAL`.