# pycounts_ts_mds

[![codecov](https://codecov.io/github/SimplyTim/pycounts_ts_mds/graph/badge.svg?token=5WRCGL2RGR)](https://codecov.io/github/SimplyTim/pycounts_ts_mds)

A short test package that counts the words in a given file.

## Installation

```bash
$ pip install pycounts_ts_mds
```

## Usage

`pycounts_ts_mds` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_ts_mds.pycounts_ts_mds import count_words
from pycounts_ts_mds.pycounts_ts_mds import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_ts_mds` was created by Timothy Singh. It is licensed under the terms of the MIT license.

## Credits

`pycounts_ts_mds` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
