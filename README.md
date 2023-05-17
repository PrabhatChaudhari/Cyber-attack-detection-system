# Cyber-attack-detection-system
Cyber-attack detection and attack template classification on load forecasted data using HOT-SAX and Machine Learning

Use the File Anomaly Detection System.ipynb to use the model.

1. Import a data file you wish in the sectioon "Importing Libraries and loading Models" . Make sure to have files fitter_scaler.joblib and catboost_classifier_model in the same folder.
2. simulate attacks using the functions scaling_attack,ramping_attack,random_attack and pulse_attack inn "Energy data attack simulation" section.
3. A csv file will be created that will be similar to the input file , but some of the data would be altered , which were attacked.
4. [imp] Delete the first row of the csv file which consists of heading after the above step.
5. Now run the discord detection part of the code
6. In " Displaying the results " section enter the total number of discords that the data has in num_discords variable
7. Now the code will display dates It believe are attacked.
8. Tally the dates to our attack dates and keep track of the dates that are detected incorrectly
9. Now in the "creating Dataframe and dropping rows" section drop the dates that were incorrect using the commented part of the code # df_1.drop(date_no-1,axis=0,inplace=True)
10. The model should display accuracy with which it has correctly identified the template of attacks.



