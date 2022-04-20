# M5-forecasting-trials

This repo takes data from the M5 forecasting competition (see https://www.kaggle.com/c/m5-forecasting-accuracy) and applies several methods for forecasting the demand of items. I do not apply these methoids to the whole dataset of 3,049 orudtcs over 10 stores (in 3 states), but rather apply it to randomly selected items.

The methods applied in the smoothing part:
* Holt-Winters
* Simple Croston model
* Extended Croston model

In the Machine Learning part I use LightGBM, find the better objective function and then perform hyperparaneter optimization.
