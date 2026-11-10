# Python Data Visualization

Matplotlib and Plotly notebooks, from plotting fundamentals to interactive machine-learning visuals and financial charts.

## Matplotlib

| Notebook | What it covers |
| :--- | :--- |
| [`matplotlib_fundamentals.ipynb`](matplotlib/matplotlib_fundamentals.ipynb) | pyplot vs object-oriented interface, subplots, styling and specialised plots using the Portland housing-price dataset |
| [`gradient_descent_visualization.ipynb`](matplotlib/gradient_descent_visualization.ipynb) | Linear regression with gradient descent: the descent path on the cost contour, a 3D cost surface and the effect of feature scaling |
| [`logistic_regression_interactive.ipynb`](matplotlib/logistic_regression_interactive.ipynb) | Sigmoid function, logistic loss vs squared error, decision boundaries and an interactive gradient-descent plot (click the contour to change *w* and *b*) |

## Plotly

| Notebook | What it covers |
| :--- | :--- |
| [`financial_charts_plotly.ipynb`](plotly/financial_charts_plotly.ipynb) | Interactive candlestick, OHLC and area charts plus KPI indicators, with price data pulled from `yfinance` |

## Running

```bash
pip install -r requirements.txt
jupyter notebook
```

The interactive plots use the `ipympl` backend (`%matplotlib widget`). The two machine-learning notebooks were written for a course environment and import helper modules (`lab3_utils.py`, `lab4_utils.py`) that aren't included here, so some cells need those helpers to re-run. The saved outputs show the results.
