# ML-Trading

A machine learning program that both analyze the pricing data of stocks and make decisions about when to buy and sell shares.

---

## Technologies

This project leverages python 3.7 with the following package:

* [Pandas](https://pandas.pydata.org/) - Entry point, open source data analysis and manipulation tool.

* [NumPy](https://numpy.org/) - Python library used for working with arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

* [hvPlot](https://hvplot.holoviz.org/) - Provides an alternative for the static plotting API provided by Pandas and other libraries.

* [Matplotlib](https://matplotlib.org//) - Comprehensive library for creating static, animated, and interactive visualizations in Python.

* [scikit-learn](https://scikit-learn.org/stable/) - Python machine learning that provides supervised and unsupervised learning algorithms.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
pip install -U scikit-learn
conda install -c pyviz hvplot
```

Next, import required libraries and dependencies.

```python
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
```

---

## Usage

To use this machine learning application simply clone the repository and run the **machine_learning_trading_bot.ipynb** with:

```python
  machine_learning_trading_bot.ipynb
```

---

## Contributors

This project brought to you by Agnes.

---

## License
MIT License

Graphic shown below is served as our baseline prior tuning the trading algorithm.

<img width="387" alt="Screen Shot 2022-09-08 at 7 19 31 AM" src="https://user-images.githubusercontent.com/105394703/189468553-50036e34-9262-4466-b488-7c4949bc501b.png">

Graphic shown below is after tuning the offset to 5 months from our baseline of 3 months.

<img width="384" alt="1" src="https://user-images.githubusercontent.com/105394703/189565185-b43e12d5-d605-46be-8d78-308b03f1be6f.png">


Graphic shown below using the new model with updated trading algorithm.

<img width="388" alt="Screen Shot 2022-09-08 at 7 19 59 AM" src="https://user-images.githubusercontent.com/105394703/189489309-35594234-05a2-4a4f-bd56-420a6e31cc41.png">

