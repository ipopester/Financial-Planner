# Financial-Planner

This is a tool designed to determine whether the customer's current portfolio of cryptocurrency, stock, and bond holdings meet the minimum required amount to create an 'emergency' retirement fund, and if elligible, create projections of the potential returns of that portfolio. Monte Carlo simulations using a variety of stock/bond ratios were run in order to determine returns based on 10 and 30 year investment periods. 

## Technologies

The analysis was performed using python 3.7 and Jupyter Lab 3.2.4. Below are the critical dependencies used and associated documentation:

* [python](https://www.python.org/downloads/) 3.7.11 

* [pandas](https://pandas.pydata.org/docs/) 1.3.5

* [jupyter](https://jupyterlab.readthedocs.io/en/stable/) 3.2.4
___

## Installation Guide

Before running the application, make sure that a python development environment has been activated in the CLI. 

Install the following dependencies:

```python
    Python 3.7
    pip install pandas
    pip install jupyter lab
```

___

## Usage

To view the report, clone this repo on GitHub using the link provided. Open the `financial_planning_tools.ipynb` file in the Report directory using Jupyter Lab to view the results. Image files containing the line plots and histograms for the values of the portfolios over time can be viewed in the Images folder.


## Contributors

Ian Pope: iancpope@uw.edu

## License

Copyright (c) (2022) (Ian Pope)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
