# Regional-Flood-Frequency-Analysis
## A Comparison of Regional Flood Frequency Analysis Results using MLR(Multi-Linear Regression), XBG(Decision Tree Ensembles), SVR(Support Vector Regression) and ANN(Artificial Neural Networks) for the Region of Australia. 
### This is a project done for the course of Advance Statistical Methods in Hydrology CE6670 at IIT Hyderabad
Steps:
1. Data Processing
- Data cleaning and processing. 
- Check the homogeneity and stationarity of data at each gauging station.
- Check for Trend and Stochasticity components using statistical tests.
2. At-site FFA (Annual Peak Stream Flow data/Peaks over Threshold)
- Perform at-site FFA for each gauging station 
- Fit the best Distributions using MLE/L-moments (GEV, Gumble, LP-III etc.)
- Use of GOF tests/use L-moment ratio diagrams.
3. Quantile Values 
- Calculate the Q2, Q5, Q10, Q15, Q20, Q25, Q50, and Q100 flood quantile values for each station. 
- Selection of Predictor Variables
- Select a set of predictor variables to build the supervised models.
- Calculate the Annual Maximum Precipitation values from precipitation data.
4. Model Training, Validation and Testing
- Fit/Train and validate all the models (MLR, NLR, SVR, ANN and XGB) to the set of Predictors and Labels from all the stations.
- Test the models on the Test data set (for a selected number of stations) and compare the results from each of the ML/DL techniques used.
