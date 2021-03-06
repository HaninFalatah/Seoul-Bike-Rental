# Project Proposal

#### Question/need:
* What is the framing question of your analysis, or the purpose of the model/system you plan to build? 
  * which day of the week the bikes are rented more than others?
  * Is there an hour the bikes are rented most?
  * If there is a season the bikes are rented more than others?
* Who benefits from exploring this question or building this model/system? 
  * the people in Seoul that rid bikes

#### Data Description:
* What dataset(s) do you plan to use, and how will you obtain the data? The Seoul Bike Sharing Demand Data Set
  - The Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
* What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? 
  - The weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
  - I expect when there is rain or snow fall that count of rentl bikes goes down and the weekend and Holiday bikes goes down   
* If modeling, what will you predict as your target? 
   * perdicting if the day is functional for Bikes 
* The Number of Instances:8760 and the Number of Attributes:14 

#### Tools:
* How do you intend to meet the tools requirement of the project? 
    * pandas, numpy, matplotlib, seaborn, train_test_split, LogisticRegression, LinearRegression, RandomForestRegressor,SVR, cross_val_score, fbeta_score, accuracy_score, 

#### MVP Goal:
* What would a (MVP) look like for this project?
   * The goal of this project is to better understand which factors are most important for the the bike rental.
