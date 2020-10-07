# Predicting energy consumption and generation using Machine learning and Deep learning
<p align="center"><img src="images/readme.jpg" /></p>

### Exploring household energy data by consumption, by generating (solar panel) by hourly, weekly, monthly, yearly, winter, summer.
* Keyword explanations (from PDF file with the data)

  *  **Generator Capacity**: Solar panel capacity recorded on the application for connection for each customer.
  *  **Consumption Category**:
      * GC:General Consumption for electricity supplied all the time excluding solar generation and controlled load supply
      * CL:Controlled Load Consumption (only in Australia) We will add CL and GG to find final energy generation.
      * GG:Gross Generation for electricity generated by the solar system with a gross metering configuration, measured separately to household loads 

  * **Half-hourly data**: Kilowatt hours (kWh) of electrical energy consumed or generated in the half hour ending at 0:30 (eg. between 0:00 and 0:30).\
  The value is positive regardless of whether it is consumption or generation. 
## Modeling:
  * For energy generation:
     * **Features**:weather information(UV Index, Temperature, Humidity, Wind Speed, Wind direction, Rain chance, etc)
     * Using models such as **Random Forest, XGBoost, Logistic regression
   * For energy consumption:
     * **Features**: time (will add other features)
     * Using time-series models such as **ARIMA, SARIMAX, Prophet and naive LSTM(DL)
## More information on slide:[Predicting energy consumption and generation.pdf](https://github.com/stardustd/Predict-energy-consumption/blob/master/Predict%20energy%20comsumption%20and%20generation.pdf)
