# Time-Series-Forecasting-Using-ARIMA-python
Implementation of Arima using  Python for times ereis forecasting

AutoRegressive Integrated Moving Average’, is a forecasting algorithm based on the idea that the information in the past values of the time series can alone be used to predict the future values

An autoregressive integrated moving average model is a form of regression analysis that gauges the strength of one dependent variable relative to other changing variables. 

ARIMA is alternatively sometimes referred as “MMM”- Market Mix Model or “Box-Jenkins” Model.

Arima is Made up of 3 Components
AR(p) Where p = order of autocorrelation (Indicates weighted moving average over past observations) 
          a)  refers to a model that shows a changing variable that regresses on its own  
               lagged, or prior, values

I(d) Where d = order of integration (differencing) (Indicates linear trend or polynomial trend)  
           a) the differencing of raw observations to allow for the time series to become      
               stationary, i.e., data values are replaced by the difference between the data  
               values and the previous values.

MA(q) Where q = order of moving averaging (Indicates weighted moving average over past errors) its a a trend indicator
               a) incorporates the dependency between an observation and a residual 
                  error from a moving average model applied to lagged observations

[If a time series, has seasonal patterns, then you need to add seasonal terms and it becomes SARIMA, short for ‘Seasonal ARIMA’. More on that once we finish ARIMA-[PDQ]. 
