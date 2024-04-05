\# ML\-House\-Prices\-Predictor

\#\# Overview of House Prices Prediction

\!\[Sample Data\]\(https://github\.com/madhesh05/TNSDC/blob/main/House%20Prices%20Prediction\.png\)

Predicting house prices using sample data from Google Colab\.

The goal is to predict the price of a house based on 8 parameters, including:

\- longitude

\- latitude

\- housing median age

\- total rooms

\- total bedrooms

\- population

\- households

\- median income

\#\# Model Architecture

The model is very simple, consisting of three dense layers:

\- \*\*Layer 1: Input Layer \(Dense Layer\)\*\* \- Input shape of \(\*, 8\), output shape of \(\*, 8\)

\- \*\*Layer 2: Hidden Layer \(Dense Layer\)\*\* \- Output shape of \(\*, 4\)

\- \*\*Layer 3: Output Layer \(Dense Layer\)\*\* \- Output shape of \(\*, 1\)

The first \(input\) layer receives the inputs such as longitude, latitude, housing median age, etc\.

The second \(hidden\) layer receives the output of the first layer and returns output in the shape \(\*, 4\)\.

The third \(output\) layer receives the output of the second layer and returns the predicted value of the house\.

Before being passed in, all parameters were normalized to be between 0 and 1 to improve performance\.

The house prices \(output\) were reduced by 6 orders of magnitude\.

\#\# Performance

After 10 epochs, the loss measured in mean square error \(of the normalized outputs\) is 0\.0058\.

Repository Link: \[TNSDC\]\(https://github\.com/madhesh05/TNSDC\)

