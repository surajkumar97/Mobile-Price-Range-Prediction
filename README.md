# Mobile-Price-Range-Prediction
## INTRODUCTION

In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

### Data Description -

Battery_power - Total energy a battery can store in one time measured in mAh

Bluetooth - Has bluetooth or not

Clock_speed - Speed at which microprocessor executes instructions

Dual_sim - Has dual sim support or not

Fc - Front Camera mega pixels

Four_g - Has 4G or not

Int_memory - Internal Memory in Gigabytes

M_dep - Mobile Depth in cm

Mobile_wt - Weight of mobile phone

Px_height - Pixel Resolution Height

Px_width - Pixel Resolution Width

Ram - Random Access Memory in Mega

Touch_screen - Has touch screen or not

Wifi - Has wifi or not

Sc_h - Screen Height of mobile in cm

Sc_w - Screen Width of mobile in cm

Talk_time - longest time that a single battery charge will last

Three_g - Has 3G or not

Wifi - Has wifi or not

Price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(highest cost).

## Conclusion

1. From EDA we can see that here are mobile phones in 4 price ranges. The number of elements is almost similar.
2. Half the devices have Bluetooth, and half don’t.
3. There is a gradual increase in battery as the price range increases.
4. Ram has continuous increase with price range while moving from Low cost to Very high cost.
5. Costly phones are lighter.
6. RAM, battery power, pixels played more significant role in deciding the price range of mobile phone.
7. From all the above experiments, we can conclude that logistic regression and, XGboosting with using hyperparameters we got the best results.
