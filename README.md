# Anomaly Detection for SCADA systems

The security of critical infrastructures is decreasing due to the
apparition of new cyber threats against Supervisory Control and Data Acquisition
(SCADA) systems. The evolution they have experienced; the use of standard
hardware and software components or the increase of interconnected devices in
order to reduce costs and improve efficiency, have contributed to this. This work
reviews the research effort done towards the development of anomaly detection
for these specific systems. SCADA systems have a number of peculiarities that
make anomaly detection perform better than in traditional information and
communications technology (ICT) networks. SCADA communications are
deterministic, and their operation model is often cyclical. Based on this premise,
modeling normal behavior by mining specific features gets feasible. [(Source)](https://link.springer.com/chapter/10.1007/978-3-642-19644-7_38#citeas)

## Overview

| File/Folder                    | Description                                                  |
| ------------------------------ | ------------------------------------------------------------ |
| [EDA.ipynb](/EDA.ipynb)        | Exploratory Data Analysis                                    |
| [TSA.ipynb](/TSA.ipynb)        | Time Series Anomaly Detection                                |
| [data](/data)                  | Data Folder                                                  |
| [output](/output/iqr_test.csv) | CSV containing IQR lower and upper bound                     |
| [plots](/plots)                | Visualizations for each individual metric and their outliers |

## Requirements

* Can be found in [requirements](/requirements.txt) file.
* Python 3.7+
* Main packages:

```python
catboost==0.23.1
jupyter==1.0.0
matplotlib==3.2.1
numpy==1.18.4
pandas==1.0.3
plotly==2.7.0
sklearn==0.0
seaborn==0.10.1
xgboost==1.1.0
xlrd==1.2.0
```
