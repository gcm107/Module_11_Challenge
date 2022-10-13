# Module_11_Challenge
This notebook is for forecasting with Facebook Prophet. We are trying to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

---


## Installation Guide
We will run this notebook in
[Google Colab](https://colab.research.google.com/ "Google Colab").
The first cell of this notebiook will install and run the libraries and packages. See below:

```
!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews
```
```
# Import the required libraries and dependencies
import pandas as pd
import holoviews as hv
from prophet import Prophet
import hvplot.pandas
import datetime as dt
import numpy as np
%matplotlib inline
```

---

## Usage

>* Open the forecasting_net_prophet.ipynb notebook in Google Colab. The notebook will prompt you to select csv files to read in. <b>

>>* The files to use are located in the 'Resources'    folder of this repository





---

### Contributors

G. Cale McDowell



[@gcm107](https://github.com/gcm107)

---

## License