# stocker
A Stock Analysis and Prediction Toolkit using Additive Models (by Will Koehrsen)
This is a modified version of Stocker to load CSV file from a local folder, it works both with Quandl and Yahoo CSV data.

see original at:   https://github.com/WillKoehrsen/Data-Analysis/tree/master/stocker


```python
from stocker import Stocker
stk = Stocker('RACE.MI','CSV','C:\Temp\Storico')
print(stk.stock.tail(5))
stk.changepoint_prior_scale = 0.25
stk.evaluate_prediction()
```




