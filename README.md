# DeepLearning-Challenge

Overview: The purpose of this analysis was to detirmine if we can accurately predict the success probability of and organization recieving money from AlphabetSoup based on specific categories as indicators of success. The data was provided from Alphabet soup containing 34000 items  

Results:
* The variables we considered as targets for our model were "Application Type and Classification"
* The features for the optimized model were NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, and INCOME_AMT
* We found that "EIN, STATUS, and SPECIAL_CONSIDERATIONS" were not useful targets or features and were removed from our inputs

-We chose layers of 100, 30, and 10 for a total of three layers for our optimized neural network for variety purposes and to increase our accuracy and decrease our dropped percentage from our original itereation of the analysis.
-We achieved an accuracy of 79% from our optimized modelwhich exceeded the target of 75%
-We trimmed unnecessary categories from our original data to have fewer features as well as cleaned specific categories to show more relevant counts of their indicators. We also increased our nuerons and our layers to boost our overall accuracy and succeeded in hitting our target accuracy of 75% 

Summary: Based on our exceeding the target accuracy threshhold I believe our model would be a useful one as far as predicting success of organizations. When a random forest classifier was used, the accuracy was lower at 77%
