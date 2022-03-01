# DE-Project

-- Overview Of The Used Dataset:

The dataset contains information about the athletes that participated in the olypmpics starting from 1896 to 2016. It contains a record for each participation of an athlete in an olympic event. The variables in the dataset are:
- ID: A unique id for every record
- Name: The name of the athlete
- Sex: The gender of the athlete (Male or Female)
- Age: The age of the athlete at the time of participation
- Height: The height of the athlete
- Weight: The weight of the athlete
- Team: The country that the athlete plays for
- NOC: The National Olympic Committee that organized their people'sthe athletes participation in the Olympic Game.
- Games: The year and season of participation
- Year: The year of participation
- Season: The season of participation (Summer or Winter)
- City: The city that hosted the olympics.
- Sport: The sport that the athlete played in.
- Event: The event in the sport that the athlete participated in.
- Medal: The medal that the athlete won during this participation ( Bronze, Silver, Gold or Nothing)

-- Overview of the project goals and the motivation for it:

The main goal of the project was to explore the olympics dataset, Clean it by dealing appropriatly with missing values and removing outliers and learn insights from it then come up with research questions to answer. During the exploration of the dataset we observed that USA had most medals by a very big amount compared to the 2nd place team which raised a couple of questions regarding performance such as: does the USA excel in a certain sport or or just overall better at the olympics than other teams. Also, The number of men was around double the overall number of women that played in the olympics which raised a couple of questions regarding gender and events participation like: The participation of women and men in the olympics throughout the years.
In order to clean the data, the missing values and outliers in weight, height and age of the participants was dealt with accordingly.
-- Descriptive steps used for the work done in this milestone:
  1. An Exploratory Data Anaysis Section where the dataset was visualized using basic representation, the columns types and what they contain was explored and the depths of the dataset were seen.
  2. Handling of missing values in the Weight, Height, Age and Medal Columns. The missing values were either imputed using relevant factors and measures, or replaced with new descriptive phrases (for the medal ie: "No Medal"). For Weight and Height; missing values were imputed using median of correcponding event, sport and sex, then sex for any remaining missing values. Age was imputed using median of age of those in the corresponding event and sport.
  3. Handling of outliers: Outliers in 4 columns (Weight, Height, Age and Event) were explored and handled approprietly when necessary using the Z-Score. For Weight and Height, the outliers were handled on an event by event basis, where outliers for weight and height in each event were removed using Z-Score, this was done to take into consideration the differences between the events.
  4. Attempting to get insights from the cleaned data and explore more in depth the relation that exists between the different fields. This section can give some insights on how the following questions can be answered or can answer them directly.

-- Data exploration questions:

- What is the Most Successfull Athlete/Country in every Sport?
- What is the Disparity between genders throughout the years?
- What are the highest growing sports in term of number of athletes?
- Does Hosting the Olympics improve performance in terms of medals won?
- Is the age of athletes in the olympics decreasing?
- Is performance impacted by age?
- Do some countries perform better depending on the season?
- What are the highest performing countries in terms of rank by the number of Gold medals?



--Team Members:
- Selim Elbindary 43-18430
- Ali Saad 43-10950
- Fakhreldin Hussein soliman tarabay 43-11215

