# Weather Analysis 

Source : https://en.tutiempo.net/climate/united-states.html

Data Dictionary  --- 	Interpretation annual average climate values	\
T   (°C ) 		 --- 	Average annual temperature : Celsius \
T Avg (°F ) 	 --- 	Average annual temperature : Fahrenheit \
TM  (°C ) 		 --- 	Annual average maximum temperature \
T Avg Max (°F )  --- 	Annual average maximum temperature : Fahrenheit \
Tm  (°C ) 		 --- 	Average annual minimum temperature \
T Avg Min ( °F ) --- 	Average annual minimum temperature : Fahrenheit \
PP 				 --- 	Rain or snow precipitation total annual \
V 				 --- 	Annual average wind speed \
RA 				 --- 	Number of days with rain \
SN 				 --- 	Number of days with snow \
TS 				 --- 	Number of days with storm \
FG 				 --- 	Number of foggy days \
TN 				 --- 	Number of days with tornado \
GR 				 --- 	Number of days with hail

---

 ## Notes

- Data selected from different states to include at least 1 state from differnt timezones (different weather climates)
 
[source]
- If the table has displayed fields without values will have the symbol (-) this only indicates that has not been performed average, this happens if there is no sufficient data to compute.
- The total rainfall value 0 (zero) may indicate that there has made such measurement and / or the weather station does not broadcast.

[transformation notes]
- Replaced missing data with 0.0 for average temperature and replaced annual average/counts climate values that were missing with -1.0


