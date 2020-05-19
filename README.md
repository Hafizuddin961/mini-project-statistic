# mini-project-statistic
Project on Energy consumption in a household analysis <br/>
Open source code Statistic_1m.ipynb in Google Colab (advisable using Google Chrome browser)<br/>
Step 1 - Open link https://colab.research.google.com/notebooks/intro.ipynb#recent=true<br/>
Step 2 - Choose GitHub column <br/>
Step 3 - Enter a my GitHub URL https://github.com/Hafizuddin961/mini-project-statistic then, click search icon<br/>
Step 4 - Open notebook Statistic_1m.ipynb<br/>

To see dataset I used, go to dataset folder and there is 4 dataset which are:
1) energydata_complete.csv (fully taken from https://github.com/LuisM78/Appliances-energy-prediction-data - never used in code)<br/>
2) energy-1month.csv (filtered dataset for 1 month - mostly used dataset)<br/>
3) full-1month.csv (full attribute of data for 1 month - rarely used)<br/>
4) energy-1month-Wh (same as (2) but have unit - rarely used)<br/>

------------------------------------------------------------------------------------------------------------------------------<br/>

**Data Set Information:**

The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru), and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non predictive attributes (parameters).

<b>Attribute Information</b>:

date time year-month-day hour:minute:second<br/>
Appliances, energy use in Wh<br/>
lights, energy use of light fixtures in the house in Wh<br/>
T1, Temperature in kitchen area, in Celsius<br/>
RH_1, Humidity in kitchen area, in %<br/>
T2, Temperature in living room area, in Celsius<br/>
RH_2, Humidity in living room area, in %<br/>
T3, Temperature in laundry room area<br/>
RH_3, Humidity in laundry room area, in %<br/>
T4, Temperature in office room, in Celsius<br/>
RH_4, Humidity in office room, in %<br/>
T5, Temperature in bathroom, in Celsius<br/>
RH_5, Humidity in bathroom, in %<br/>
T6, Temperature outside the building (north side), in Celsius<br/>
RH_6, Humidity outside the building (north side), in %<br/>
T7, Temperature in ironing room , in Celsius<br/>
RH_7, Humidity in ironing room, in %<br/>
T8, Temperature in teenager room 2, in Celsius<br/>
RH_8, Humidity in teenager room 2, in %<br/>
T9, Temperature in parents room, in Celsius<br/>
RH_9, Humidity in parents room, in %<br/>
To, Temperature outside (from Chievres weather station), in Celsius<br/>
Pressure (from Chievres weather station), in mm Hg<br/>
RH_out, Humidity outside (from Chievres weather station), in %<br/>
Wind speed (from Chievres weather station), in m/s<br/>
Visibility (from Chievres weather station), in km<br/>
Tdewpoint (from Chievres weather station), Â°C<br/>
rv1, Random variable 1, nondimensional<br/>
rv2, Random variable 2, nondimensional<br/>

Where indicated, hourly data (then interpolated) from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis, rp5.ru. Permission was obtained from Reliable Prognosis for the distribution of the 4.5 months of weather data.

<b>Relevant Papers:</b>

Luis M. Candanedo, Veronique Feldheim, Dominique Deramaix, Data driven prediction models of energy use of appliances in a low-energy house, Energy and Buildings, Volume 140, 1 April 2017, Pages 81-97, ISSN 0378-7788,

<b>Citation Request:</b>

Luis M. Candanedo, Veronique Feldheim, Dominique Deramaix, Data driven prediction models of energy use of appliances in a low-energy house, Energy and Buildings, Volume 140, 1 April 2017, Pages 81-97, ISSN 0378-7788,
