# obesity_levels_classification
Classifying estimated levels of obesity

##### Rationale:
- Machine learning may be useful to characterize cardiovascular risk, predict outcomes, and identify biomarkers in population studies.

##### Objective
- Obesity is a complicated illness with its own debilitating characteristics, pathophysiologies, and comorbidities. Increased BMI is a risk factor for noncommunicable illnesses such as diabetes, cardiovascular disease, and musculoskeletal problems, resulting in a significant loss in life quality and expectancy.The key findings of the data from NHANES in 2015-2016 stated that The overall prevalence of obesity was higher among non-Hispanic black and Hispanic adults than among non-Hispanic white and non-Hispanic Asian adults. The same pattern was seen among the youth. 
- Here we develop machine learning classification models to identify the most contributing risk factors in estimating levels of obesity. 
- We are also interested in knowing which features associated with eating habits, physical condition or physiological charateristics are critical in predicting the obesity levels in the Hispanic population
- To test the ability of several classification models, to predict several categories of obesity levels.
- Estimate effect sizes of robust risk factors and their associations with obesity levels utilizing general linear models 

##### Data
- This data  is for the estimation of obesity levels in people from the countries of Mexico, Peru and Colombia, with ages between 14 and 61 and diverse eating habits and physical condition. Data was collected using a web platform with a survey (see Table 1) where anonymous users answered each question, then the information was processed obtaining 17 attributes and 2111 records, after a balancing process described in Fig. 1, Fig. 2. The attributes related with eating habits are: Frequent consumption of high caloric food (FAVC), Frequency of consumption of vegetables (FCVC), Number of main meals (NCP), Consumption of food between meals (CAEC), Consumption of water daily (CH20), and Consumption of alcohol (CALC). The attributes related with the physical condition are: Calories consumption monitoring (SCC), Physical activity frequency (FAF), Time using technology devices (TUE), Transportation used (MTRANS), other variables obtained were: Gender, Age, Height and Weight. Finally, all data was labeled and the class variable NObesity was created with the values of: Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II and Obesity Type III, based on information from WHO and Mexican Normativity. The data contains numerical data and continous data, so it can be used for analysis based on algorithms of classification, prediction, segmentation and association. Data is available in CSV format and ARFF format to be used with the Weka tool.


##### Skills Employed:
- Exploratory Data Analysis
- Data Cleaning and Preprocessing
- Data Visualization
- Feature Selection and Balancing of Data
- Machine Learning 
