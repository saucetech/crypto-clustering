# crypto-clustering

This project clusters various cryptocurrencies based on their performance and visually plots the results for analysis. Using market data for various cryptocurrencies' performance, I have used the original data to find the best value for k (which resulted in 4) and plotted the cluster in hvplot. Then, I optimized the clusters using Principal Component Analysis to visualize and compare the results. The analysis shows that PCA clustering provides a cleaner and more compact visualization of the clusters, while the k value remained the same.

## Technologies

This project leverages Python 3.7 with pandas, hvplot, Path, and sklearn.

## Installation Guide

In order to run this project, you will need to install hvplot and sklearn.

You can confirm whether they have been installed with the following code:

```
conda list scikit-learn
conda list hvplot
```
If they are not installed, you can install the required packages via the following code:

```
pip install -U scikit-learn
conda install -c pyviz hvplot
```

## Usage

Simply clone the repo and open the crypto_investments.ipynb notebook in order to review the analysis.

## Contributors

Brought to you by Austin Do. Email: austindotech@gmail.com

## License

MIT License
