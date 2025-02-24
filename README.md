# Time-series-forecasting

#PROBLEM STATEMENT


They are considering making an investment in a new form of transportation - JetRail. JetRail uses Jet propulsion technology to run rails and move people at a high speed! While JetRail has mastered the technology and they hold the patent for their product, the investment would only make sense, if they can get more than 1 Million monthly users with in next 18 months.
 
You need to help Unicorn ventures with the decision. They usually invest in B2C start-ups less than 4 years old looking for pre-series A funding. In order to help Unicorn Ventures in their decision, you need to forecast the traffic on JetRail for the next 7 months. You are provided with traffic data of JetRail since inception in the test file.


Evaluation Metric:
Root Mean Squre Error (RMSE) is the evaluation metric for this contest
Note: Public and private split is 20:80 where first 44 days in public and next 169 days in private
Data dictionary
Data


Investment Feasibility Report: JetRail Traffic Forecast
<br>

1. Introduction
Unicorn Investors is evaluating a potential investment in JetRail, a high-speed rail service utilizing jet propulsion technology. The key investment criterion is reaching a minimum of 1 million monthly users within the next 18 months. This report presents a time series analysis using ARIMA to forecast JetRail's expected traffic over the next 7 months.
<br>

2. Methodology
<br>
•	Dataset Used: Historical traffic data from JetRail.
<br>
•	Models Applied: 
o	ARIMA (AutoRegressive Integrated Moving Average) for time series forecasting.
o	XGBoost (initial implementation, but underperformed and was not used for final projections).
<br>
•	Evaluation Metric: Root Mean Squared Error (RMSE), with ARIMA achieving 40.97.
<br>
•	Forecast Period: Next 7 months (~214 days).
<br>

3. Key Findings
   
3.1 Forecasted Monthly Traffic
Month	Predicted Users
September 2014	63,572
October 2014	394,154
November 2014	381,439
December 2014	394,154
January 2015	394,154
February 2015	356,010
March 2015	394,154
April 2015	343,295

3.2 Investment Criteria Evaluation
<br>
•	Target: 1 million monthly users.
<br>
•	Highest Predicted Traffic: 394,154 users (far below target).
<br>
•	Shortfall: ~60% below the required threshold.
<br>
Conclusion: Based on the ARIMA forecast, JetRail is not projected to reach 1 million users per month within the required timeframe.
<br>

4. Recommendation
<br>
🚫 Investment NOT Recommended at this Stage.
•	JetRail’s projected growth is insufficient to meet investment criteria.
•	Alternative growth strategies (e.g., marketing, route expansion) should be explored before considering an investment.
•	Additional validation with alternative forecasting models (e.g., SARIMA, Prophet) could provide further insights.
<br>

6. Next Steps
<br>
•	Conduct further analysis on seasonal trends and external factors affecting ridership.
<br>
•	Explore business interventions (pricing, advertising, new routes) to boost user adoption.
<br>
•	Consider alternative forecasting approaches for cross-validation.



