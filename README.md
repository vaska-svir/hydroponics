## Unsupervised multivariate anomaly detection for Hydroponic Farming 

### Analysis of data from a network of distributed sensors placed on racks of horizontal hydroponic farming, including:
- testing the correctness of the sensors throughout the container (identifying sensors that are faulty / not collecting data correctly, need additional calibration, etc.),  
- development of a method of automatic detection of anomalies occurring in the data for a future experiment in the desiccator (based on data from one selected measurement point).*.

### The dataset analyzed includes measurement data from a network of sensors: 
- air temperature (T),
- air humidity (H), 
- atmospheric pressure (p), 
- carbon dioxide concentration in the air (co2), 
- oxygen concentration in the air (o2), 
- illumination level in the visible band (ALS),  
- illumination level in the infrared band (IR).
    
The measurement network consists of 30 points where combinations of humidity and lighting temperature sensors have been placed in both bands, 4 points where combinations of temperature, humidity, atmospheric pressure and lighting sensors have been placed in both bands, and oxygen and carbon dioxide levels in the air.

The dataset contains within it data from a 7-week time period (49 calendar days, 1176 measurements), and are downloaded hourly. They are taken from an Influx-type database hooked up directly to the crop control server.