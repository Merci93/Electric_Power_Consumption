# <span style = 'color:blue'>Tetouan Power Consumption</span>                                                                                                  
A study of the power consumption in Tetouan, a city in the Northern part of Morocco, with land area of 
approximately 10375 sq.km. and a population of about 400,000 inhabitants as of 2017 census, with an annual
increase of approximately 1.78% in 2017. Since it is located along the Mediterranean Sea, its weather is
mild and rainy in the winter, hot and dry during the summer months.

The power consumption data was collected from Supervisory Control and Data Acquisition System (SCADA) of
Amendis which is a public service operator and in charge of the distribution of drinking water and
electricity since 2002. The purpose of the electricity distribution network is to serve low and medium
voltage consumers in Tetouan regions. For this purpose, the delivery and distribution of electrical energy
from the point of delivery to the end user, the customer, is ensured by Amendis. The energy which is
distributed comes from the National Office of Electricity and Drinking Water. After transforming the high
voltage (63 kV) to medium voltage (20 kV), it is allowed to transport and distribute the energy.

With the electricity consumption being so crucial to the country, the idea is to study the impact on energy
consumption. The dataset is exhaustive in its demonstration of energy consumption of the Tétouan city in
Morocco. The distribution network is powered by 3 Zone stations, namely: Quads, Smir and Boussafou.

The data consists of 52,416 observations of energy consumption on a 10-minute window. Every observation is
described by 9 feature columns.

1. **Date Time**: Time window of ten minutes.
2. **Temperature**: Weather Temperature.
3. **Humidity**: Weather Humidity.
4. **Wind Speed**: Wind Speed.
5. **General Diffuse Flows**: “Diffuse flow” is a catchall term to describe low-temperature (< 0.2° to ~ 100°C)
fluids that slowly discharge through sulfide mounds, fractured lava flows, and assemblages of bacterial mats
and macrofauna.
6. Diffuse Flows
7. Zone 1 Power Consumption
8. Zone 2 Power Consumption
9. Zone 3 Power Consumption

# Tasks
1. Assess data
2. Separate features to enable power consumption prediction in the three zones.
3. Build model to predict power consumption

# Models
1. Decision Tree
2. Random Forest
3. Gradient Boosting