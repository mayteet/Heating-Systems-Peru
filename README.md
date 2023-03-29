# Technical Feasibility of Heating Systems and ACS in mining camps of Peru located in the mountains

<p align="center"> <img src = 'Sources\Morococha.jpg' /> </p>

The mining camps located in the mountains are in areas of high solar potential, which is an opportunity to diversify their matrix of energy consumption, and tax and economic benefits. Of the 570 mining projects that are in the production stage, 52.45% are located in the highlands of Peru. In these areas the average daily solar radiation is between 5 and 6 kWh/m2, values considered high.

This research seeks to analyze the economic technical feasibility of implementing a sanitary hot water and heating system taking advantage of the solar resource for the Tuctu mining camp, located in Morococha, Peru at about 4000 meters above sea level. For this, a study of the meteorological variables of interest is carried out, such as: global solar radiation on a horizontal surface, maximum, minimum, and average temperatures, wind speed and direction. Besides, a thermal demand calculation was made to size the compoments of the propose. Finally, the TIR and VAN were calculated as main KPIs of the economic feasibility. 

### **Methodology: **

A meteorologycal year is mandatory to analyse this time dependent system. To build a year that represents all the data of Morococha from 1996 to 2022, we got the information from the public database NRBDS. The information we got was: global solar radiation on an horizontal surface, minimum, and maximum temperatures, wind speed and direction. An API was used to connect to the database and simplify the process of getting the information. 

<p align="center"> <img src = 'Sources\Solar methodology.drawio.png' /> </p>


### **Results: **
The following dashboards shows the data analyzed.
The first one is related to the Metereological information of the study zone. It figure shows that the minimum temperature to use is -3.52 °C. The average temperature in Morococha is of 6.18 °C. The lowest temperature are presentend on May to August.

The global horizontal radiation is of our interest to size the solar collectors. It shows that it is in average it is 200 kWh/month.m2

<p align="center"> <img src = 'Sources\Metereologycal dashboard.png' /> </p>

There were 6 study cases created to analyze the thermal demand in heating and cooling. 
1. Good isolation, big windows
2. Good isolations, smaller windows
3. Bad isolation, big windows
4. Good isolation, turn to the east
5. Good isolation, without windows
6. Bad isolation, without windows


In general, the analysis presents a demand for heating, cooling and DHW. It is observed that cases 3 and 6 have a greater demand for heating and cooling. These two cases in particular represented homes without good insulation. Therefore, insulation significantly affects (>97% in heating and >88% in cooling) the thermal demand. On the other hand, the demand for ACS remains constant for all cases.

Cooling is one of the main concerns. This requirement is presented for cases 1, 3,4,6. These three cases in particular, for the hours of cooling demand, solar gains are observed through the windows, roof and occupancy.

The earnings through the large windows (2.86 m2) is on average 2000 kWh. If the size is decreased (0.95 m2), the energy gain decreases to 600 kWh by approximately 70%

The gains through the roofs vary from an insulated house to another that is not. These increase close to 95% (306 kWh to 7445 kWh) for homes with low insulation.

The earnings per occupancy remain constant throughout the day with a value of 500 kWh.

In this sense, it is recommended to insulate the houses, especially the part of the roof, to reduce the demand for cooling, as well as having windows with an area of ​​0.95 m2.


<p align="center"> <img src = 'Sources\thermal demand.png' /> </p>

A comparative analysis was performed to investigate a feseable solution for diferent number of collectors. Some of the KPI's defined were: f value, performance, TIR, VAN, and payback.

The first graph to the left shows the variation or the solar fraction of the system, and the performance for different number of collectors.

The second graph in the middle shows the CO2 production. When it is negative, it means that the solar fraction has superated the thermal demand. 

<p align="center"> <img src = 'Sources\Comparative analysis.png' /> </p>

### **Disclamer: **

This research his made in aims of study. There were many considerations taking into consideration. The information and data taken was from public datasources. No sensible information about Morococha is shared.