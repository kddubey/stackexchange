# stackexchange

Simulations for my questions and answers on
[stats.stackexchange.com](https://stats.stackexchange.com/users/337906/) and
[stackoverflow.com](https://stackoverflow.com/users/18758987/).

Bonus for employers and other types of stalkers: my [contributions to open source
software](https://github.com/kddubey/stackexchange/blob/main/oss.md).


| dir/file link                                                                                                         | q/a link                                                                                                                                   |
|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [`var_pred_var_error`](https://github.com/kddubey/stats-stackexchange/tree/main/var_pred_var_error)                   | [Does higher variance in predictions  result in higher variance error estimation?](https://stats.stackexchange.com/q/568492/337906)        |
| [`select_on_test.ipynb`](https://github.com/kddubey/stats-stackexchange/blob/main/select_on_test.ipynb)               | [Demonstrate that a model can simultaneously be  selected and evaluated on a test set](https://stats.stackexchange.com/a/570680/337906)    |
| (external) [`cappr`](https://github.com/kddubey/cappr)                                                                | [Demonstrate that a more usable version of  zero-shot text classification works](https://stats.stackexchange.com/q/601159/337906)          |
| [`train_on_test_features`](https://github.com/kddubey/stats-stackexchange/tree/main/train_on_test_features)           | [Is training on test set features (not labels) ok?](https://stats.stackexchange.com/q/611877/337906)                                       |
| [`sample_via_gumbel`](https://github.com/kddubey/stats-stackexchange/blob/main/sample_via_gumbel)                     | [Demonstrate that one can sample directly in  log-space](https://stackoverflow.com/a/76230531/18758987)                                    |
| [`precision_drop.ipynb`](https://github.com/kddubey/stackexchange/blob/main/precision_drop.ipynb)                     | A simple answer to: why did precision drop in  production?                                                                                 |
| [`auprc.ipynb`](https://github.com/kddubey/stackexchange/blob/main/auprc.ipynb)                                       | [Demonstrate that integral approximators are  trying to hurt you](https://stats.stackexchange.com/a/623015/337906)                         |
| [`db_sampling_rate.ipynb`](https://github.com/kddubey/stackexchange/blob/main/db_sampling_rate.ipynb)                 | Calculate a sampling rate for a database query                                                                                             |
| [`negative_vs_downsampling.ipynb`](https://github.com/kddubey/stackexchange/blob/main/negative_vs_downsampling.ipynb) | (in-progress) [What's the need to formulate  negative sampling for contrastive training?](https://stats.stackexchange.com/q/623900/337906) |
| [`to_batch_or_not_to_batch`](https://github.com/kddubey/stackexchange/tree/main/to_batch_or_not_to_batch)             | (in-progress) Mathematically analyze and  demo dynamic batching                                                                            |


## Setup

Need Python 3.8+

Create an environment `se` using venv:

```
cd /your/venvs

python -m venv se

source se/bin/activate

python -m pip install -r /path/to/stackexchange/requirements.txt
```

If the notebook says that it needs to run on a GPU machine, and you have a Google
account, [open the notebook in Google
Colab](https://stackoverflow.com/a/67344477/18758987).


## Usage

Interact w/ the code via Jupyter. I like [VS code
notebooks](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).
