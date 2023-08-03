# statistical_modeling_matlab
Highlights of my research work include MATLAB-based statistical modeling of unstructured raw data from GPS satellites over several years. The research involved data modeling and processing, followed by generating various residual plots, including trends and root mean square analysis. Finally, the obtained results were compared with independent data set models to validate the findings. The research outcomes were also presented at a European conference.
## Map of Geodetic Stations in Sweden
![img](https://github.com/ttariqaziz/statistical_modeling_matlab/blob/main/Plots/Map%20of%20stations.png)
## Station Types 
First-order Station (left) Second-order Station (right), (Images courtesy of SWEPOS, Sweden)
![img](https://github.com/ttariqaziz/statistical_modeling_matlab/blob/main/Plots/Station%20types.png)
## Good and Bad Geometry
![img](https://github.com/ttariqaziz/statistical_modeling_matlab/blob/main/Plots/Good%20bad%20geometry.png)
## Error Sources
![img](https://github.com/ttariqaziz/statistical_modeling_matlab/blob/main/Plots/Error%20sources.png)
## Space Weather Sources
![img](https://github.com/ttariqaziz/statistical_modeling_matlab/blob/main/Plots/Space%20weather%20error%20sources.png)
## Residual Plots
![img](https://github.com/ttariqaziz/statistical_modeling_matlab/blob/main/Plots/Plot1.png)
## Zenith Hydrostatic and Wet Delay Plots
![img](https://github.com/ttariqaziz/statistical_modeling_matlab/blob/main/Plots/Plot2.png)
## Metrics
| Station ID | RMS (mm) | Mean Difference (m) | Standard Deviation (m) |
|------------|----------|---------------------|-----------------------|
| ALB0       | 5.829    | ECMWF Model: 0.0041 | ECMWF Model: 0.0062   |
|            |          | RCA Model: 0.0046  | RCA Model: 0.0071     |
| GYRO       | 5.428    | ECMWF Model: 0.0016 | ECMWF Model: 0.0066   |
|            |          | RCA Model: 0.0016  | RCA Model: 0.0067     |
| HISO       | 5.676    | ECMWF Model: 0.0031 | ECMWF Model: 0.0062   |
|            |          | RCA Model: 0.0030  | RCA Model: 0.0063     |
| NYBO       | 5.673    | ECMWF Model: 0.0042 | ECMWF Model: 0.0068   |
|            |          | RCA Model: 0.0042  | RCA Model: 0.0068     |
| OVTO       | 5.275    | ECMWF Model: 0.0032 | ECMWF Model: 0.0071   |
|            |          | RCA Model: 0.0032  | RCA Model: 0.0070     |
| OXEO       | 6.938    | ECMWF Model: 0.0013 | ECMWF Model: 0.0074   |
|            |          | RCA Model: 0.0012  | RCA Model: 0.0075     |
| STAO       | 7.095    | ECMWF Model: 0.0013 | ECMWF Model: 0.0067   |
|            |          | RCA Model: 0.0012  | RCA Model: 0.0069     |
| VASO       | 7.095    | ECMWF Model: 0.0018 | ECMWF Model: 0.0080   |
|            |          | RCA Model: 0.0018  | RCA Model: 0.0080     |
## Conclusion
- Until the year 2010, only 25 first stations were used for measuring Tropospheric delay measurement. However, after these results and validation, we can conclude that these nine second-order stations could also be usable for measuring Tropospheric delay estimation.
- One of the biggest advantages of using this technique is its cost-effectiveness compared to the much more expensive balloon and airborne techniques, as it relies on the existing infrastructure.
- Secondly, GNSS measurements can be obtained at any time and in any weather condition, making it highly accessible.
- For more sophisticated measurements, we can use balloons and airborne systems, but launching those systems requires proper planning and is limited to a few times per year, whereas GNSS systems work 24/7 and function in all weather conditions.
- From all the results shown in this thesis, we can confidently state that these second-order stations are usable for monitoring Tropospheric water vapor activity and delay estimation.
