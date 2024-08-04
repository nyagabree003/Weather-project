Weather Data Analysis 
 Overview 
 This project includes dataset of the weather and it required to use Python and SQL to analyze the data. The weather parameters in the datasets involve temperature, wind speed, visibility, and conditions. In general, the method applies to a wide variety of questions, from the individual selection of specific types of weather to the assessment of statistical characteristics. 
 
 Dataset 
 The dataset used in this project is provided in a CSV file format and contains the following columns:The dataset used in this project is provided in a CSV file format and contains the following columns: 
 
 Date/Time: The time when the weather data was recorded. 
 Temperature (°C): The temperature in degree Celsius also done. 
 Dew Point Temp (°C): The temperature at which according to physics and chemistry the water vapor in the air condenses and water droplets start to form that temperature is referred to as dew point temperature in degree Celsius. 
 Rel Hum (%): The proportion of the humidity to the maximum possible for this temperature in percent. 
 Wind Speed (km/h): The wind speed in the units of Kilometres per hour on the day of the observation. 
 Visibility (km): The value expressed in kilometers of the visibility realized during the experiment. 
 Stn Press (kPa): The station pressure reported in kilopascals. 
 Weather: Details of the state of the atmosphere. 
 Project Structure 
 The project is divided into two parts:The project is divided into two parts: 
 
 
 Using Python and the Pandas library, 
 
 Filtering Weather Conditions: 
 
 Select all documents in which the weather was precise: clear. 
 Determine the frequency of the exact wind speed measurement of 4 km/hr. 
 Locate all the times when it is clear weather, relative humidity is above 50, or the visibility is above 40. 
 Data Exploration and Summary: 
 
 It is also very important to signal for any cases of NULL values that may be present in the current dataset. 
 Find the average visibility of data set. 
 Compute the column means for each of the weather conditions. 
 Data Manipulation: 
 
 Change the name of the column from Weather to Weather_Condition. 
 Specific Condition Filtering: 
 
 Count the number of records that satisfy conditions where wind speed is more than 24 km/hr and visibility is specifically 25 km. 
 Determine the number of weather conditions that involves snow. 
 Part 2 encompasses the SQL Data Analysis whereby unusual and high patterns of the data set are identified. 
 The dataset is then transferred to a SQL data base where similar tasks are carried out using SQL statements. Example SQL queries include: 
 
 Returning records where a specified condition of the weather element is met. 
 Measuring the frequency of appearance of certain wind speeds. 
 Calculating average visibility. 
 Looking for NULL values in the dataset Eliminating these NULL values from the dataset very important before proceeding to avoid misleading outcomes. 
 How to Run 
 Prerequisites 
 Python 3
 The pandas which is a useful library should be installed by using the command pip install pandas. 
 Using mySQL database
 Run the Python Code 
 Make a copy of the repository 
 It is also important to make sure that the dataset which consists of a CSV file is in the project directory. 
 Execute the code  in Jupyter notebook to conduct the analysis. 
 SQL Analysis 
 Bring your CSV data into an SQL database. 
 Execute the provided SQL scripts. 
 Results 
 Weather Conditions: The data set uncovers different weather scenarios that include the number of days that are clear and the days with snow. 
 Summaries: This provided the required mean visibility and occurrence of specific conditions in the given frequency. 
 Data Filtering: Other weather types arre partitioned regarding such parameters as wind velocity and moistness. 

 
 Conclusion 
 This project includes a detailed weather data analysis with exploiting Python and SQL. Therefore, it is possible to utilize the results of this work for the further investigation of weather conditions and their changes.

 License
This project is licensed under the MIT License. See the LICENSE file for details.
