# Crypto_Clustering

This project uses unsupervised learning methods (KMeans algorithm) to cluster cryptocurrencies by their performance in different time periods. The data used in the analysis is provided from a CSV file and is prepared using Pandas and the StandardScaler module from scikit learn.

![Crypto_clustering_results.png](https://github.com/rrmangum/Crypto_Clustering/blob/main/Images/crypto_clustering_results.png?raw=true)

---

## Technologies

This analysis uses python Python 3.9.12 and the following libraries:
* [Pandas](https://pandas.pydata.org/) - Provides the calculating functions, and data manipulation necessary to conduct this analysis.
* [Pathlib](https://docs.python.org/3/library/pathlib.html) - Provides the path to a CSV database.
* [hvplot](https://hvplot.holoviz.org/user_guide/index.html) - Provides the visualizations.
* [scikit learn](https://scikit-learn.org/stable/user_guide.html) - Provides the tools for unsupervised learning through clustering, standard scaling, and PCA

---

## Installation Guide

An installation is not required for this analysis if you are only wanting to review the analysis. If you wish to alter the inputted values, follow the steps below:

1. Download [Anaconda](https://www.anaconda.com/products/distribution) to your computer. 

2. To install hvplot, in your terminal or gitbash enter the following command:

```python
conda install -c pyviz hvplot geoviews
```

3. To install scikit learn, in your terminal or gitbash enter the following command:

```python
pip install -U scikit-learn
```
4. In your terminal or gitbash, navigate to the directory you saved the analysis files. Enter the following command:
```python
jupyter lab
```

---

## Usage

This analysis is not meant as financial advice, and is purely a review of cryptocurrency clustering according to their performance across different time periods.

---

## Contributors

Ryan Mangum - [LinkedIn](https://www.linkedin.com/in/ryanrmangum/) | rrmangum@gmail.com

---

## License

[MIT License](https://choosealicense.com/licenses/mit/)

Copyright (c) [2022] [Ryan Mangum]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
