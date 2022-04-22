# COVID-19 Crunchers

Project 1, Data Science Boot Camp

Submitted by Harish Korrapati, Britney Washington, Ishanjit Sidhu, Corey Lawson-Enos

## Summary
* 

## Packages Required
sodapy (Socrata), json, requests, pandas, numpy, matplotlib.pyplot, scipy.stats, census

## API Tokens Required
Save to config.py file as:
* US CDC: appToken = '<token>'
* US Census: api_key = '<token>'

## Summary Analysis
* Latitude did not show significant relationship to Humidity, Cloudiness, and Wind Speed categories. Sample humidity plot: 

![alt text](https://github.com/clawson13/python-api-challenge/blob/0bfb9434e4ecd2b0e2b83335a9e208d2540a885d/Images/Lat_v_Humidity.png)

* Although northern latitude change shows a strong link to temperature, the tie is much weaker in the South; as such, it cannot be construed from the dataset generated that latitude is the only contributing factor to global temperature variance.

![alt text](https://github.com/clawson13/python-api-challenge/blob/0bfb9434e4ecd2b0e2b83335a9e208d2540a885d/Images/Lat_v_Temp_South.png)

* Interactive Google Map displays VacationPy's plotted cities colored by humidity level:

![alt text](https://github.com/clawson13/python-api-challenge/blob/ba53edee096843f90384e8a38df02067d2372aa0/Images/Heat_Map.png)
