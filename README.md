# Inflam

![Continuous Integration build in GitHub Actions](https://github.com/jhyland01/python-intermediate-inflammation/workflows/CI/badge.svg?branch=main)
Inflam is a data management system written in Python that manages trial data used in clinical inflammation studies.

## Main Features

Some key feature of Inflam:
* Perform basic statistical analysis (mean, max, min) of clinical trial data focussed on inflammation data
* Ability to work with clinical trial data in .csv format
* Ability to work with clinical trial data in .json format (in development)
* Plot generation of trial data

## Dependencies
Inflam requires the following Python packages:
* [NumPy](https://www.numpy.org/) - makes use of NumPy's statistical functions
* [Matplotlib](https://matplotlib.org/stable/index.html) - uses Matplotlib to generate statistical plots

The following optional packages are required to run Inflam's unit tests:

* [pytest](https://docs.pytest.org/en/stable/) - Inflam's unit tests are written using pytest
* [pytest-cov](https://pypi.org/project/pytest-cov/) - Adds test coverage stats to unit testing

See requirements.txt for a full list of environment packages.

## Installation

Copy the repository from [Inflam](https://github.com/jhyland01/python-intermediate-inflammation),
navigate to the root of the repository in your local machine and run 'pip3 install .' to install the package.

## Basic Usage

Run 'python3 inflammation-analysis.py' from the command line.

## Contributing

Feel free to contribute.

## Contact information

Email: test@test.ac.uk

## Credits

thanks to the Software Sustainability Institute for provision of this code for the [Intermediate Research Software Deve
lopment in Python](https://carpentries-incubator.github.io/python-intermediate-development/) workshop.

## Citations

n/a

## License

MIT License.