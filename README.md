# stocker
A Stock Analysis and Prediction Toolkit using Additive Models (by Will Koehrsen)

see:   https://github.com/WillKoehrsen/Data-Analysis/tree/master/stocker



from stocker import Stocker

stk = Stocker('RACE.MI','CSV','C:\Temp\Storico')
print(stk.stock.tail(5))
stk.changepoint_prior_scale = 0.25
#stk.evaluate_prediction()
