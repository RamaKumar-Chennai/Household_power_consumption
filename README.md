The Household Power Consumption dataset is a multivariate time series dataset that describes the electricity consumption for a single household over four years from December 2006 to November 2010. The observations 
were collected every minute.

The dataset includes measures about specific energy uses.
The documentation identifies the following variables of interest:

global_active_power: The total active power consumed by the household (kilowatts).
global_reactive_power: The total reactive power consumed by the household (kilowatts). voltage: Average voltage (volts).
global_intensity: Average current intensity (amps).
sub_metering_1: Active energy for kitchen (watt-hours of active energy).
sub_metering_2: Active energy for laundry (watt-hours of active energy).
sub_metering_3: Active energy for climate control systems (watt-hours of active energy).
The active energy refers to the real power consumed, and the reactive energy is the unused power in the lines.
We can see that the dataset provides the active power as well as some division of the active power by main circuit in the house, especially the kitchen, the laundry and the air conditioning.

PERFORMANCE METRICS FOR LINEAR REGRESSION MODEL

Root_mean_squared_error: 0.038455
Mean_absolute_percentage_error: 0.044900
R² Score: 0.998200




PERFORMANCE METRICS FOR RANDOM FOREST REGRESSION MODEL

Root_mean_squared_error: 0.033469
Mean_absolute_percentage_error: 0.030923
R² Score: 0.998636



PERFORMANCE METRICS FOR RANDOM FOREST REGRESSION MODEL after RANDOMIZED SEARCH 

Root_mean_squared_error: 0.027386
Mean_absolute_percentage_error: 0.016199
R² Score: 0.999087



Of all three ML models,RANDOM FOREST REGRESSION MODEL with HYPER PARAMETER TUNING(RANDOMIZED SEARCH ) GIVES THE BEST  RESULTS


NEURAL NETWORK MODEL PERFORMANCE METRICS:


Root mean squared error is   0.5268588662147522

Mean absolute percentage error is   0.7015218138694763

 R2_score_value is   0.660955011844635



OF ALL MODELS,RANDOMIZED SEARCH MODEL IS THE BEST MODEL
