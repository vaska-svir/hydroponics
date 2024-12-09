## Unsupervised multivariate anomaly detection for hydroponic farming 

### Research goals:
Analysis of data from a network of distributed sensors placed on racks of horizontal hydroponic farming, including:
- testing the correctness of the sensors throughout the container (identifying sensors that are faulty / not collecting data correctly, need additional calibration, etc.),  
- development of a method of automatic detection of anomalies (based on data from one selected measurement point).

### Metadata
The dataset analyzed includes measurement data from a network of sensors: 
- air temperature (T),
- air humidity (H), 
- atmospheric pressure (p), 
- carbon dioxide concentration in the air (co2), 
- oxygen concentration in the air (o2), 
- illumination level in the visible band (ALS),  
- illumination level in the infrared band (IR).
    
### ML models used in the analysis:
- Isolation Forest 
- Local Outlier Factor
- One Class SVM

### Time Series forecasting model:
- Facebook Prophet

*More information and descriptions are included as a markdowns in a notebook.* 