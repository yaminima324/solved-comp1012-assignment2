Download Link: https://assignmentchef.com/product/solved-comp1012-assignment2
<br>
<h1></h1>

You <strong>don’t</strong> need to use input() to get started on this assignment. Use the values shown in the sample sessions to get your solution started, then add input <em>later</em>.

Many of the calculations require you to convert units (from millimeters to meters, from millimeters to inches, from hours to minutes to seconds). Make sure that you’re converting the values <em>before</em> doing the calculation!

Use 2 decimal places of precision for speed and 4 decimal places of precision for all other values in your output.

<strong>Do not</strong> create your own value for . Use the constant that comes from the math module.

<h2>“Programmed by…”</h2>

Use the following code snippet at the <strong>end</strong> of your script to print out the time and end of processing message:

<h1>Question 1: Required</h1>

In this question, you will calculate some statistics for a csv file named <strong>reducedweather.csv</strong>. The file contains tabular data which includes Manitoba daily minimum and maximum temperatures from Jan until Sept 17 in 2019. The first row is a header record (row), with headings <strong>Max Temp</strong> and <strong>Min Temp</strong>. After the header row, each row is a day where maximum and minimum temperature for that day is recorded. From this file, you need to calculate mean, standard deviation, highest and lowest temperature for each column.

The description for this problem is exactly same as the assignment 1 question 1. But here you need to use functions for reading the file, finding standard deviation, squared difference, max and mean value.

<h2>What to do</h2>

Create a module with name <strong>StatisticsCalculation</strong>. To create the module, you can open a new python script. Save the script with the given name. The statistics calculation module contains following functions: <strong>calculateMean(data</strong>):

The parameter data is a list of floating point values. Calculate and return the mean. Remember, data is a single list, it does not contain any nested list. <strong>calculateStdDev(data, mean):</strong>

Given a list of data and the mean of the data, calculate and return the standard deviation. Again remember, data is a single list, it does not contain any nested list. mean is a float value. <strong><em>findMin(data):</em></strong>

Given a list of data, it will return the min. Data is a single list, it does not contain any nested list. You can not use any built in function to calculate the minimum value. In this function, you need to implement your own min function. <strong><em>findMax(data,</em> <em>mean):</em></strong>

Given a list of data, it will return the max. Data is a single list, it does not contain any nested list. You can not use any built in function to calculate the maximum value. In this function, you need to implement your own max function.




Create another module with name <strong>InputOutputHandler</strong>. This module contains the following functions: <strong>printCSVResults(headings,means, stdDevs, mins, maxs):</strong>

The parameters headings, means, stdDevs, mins and maxs are lists containing the column headers and statistics from the csv file.  You need to print the statistics from this function.

<strong>readCSVFile(fileName):</strong>

The parameter <strong>fileName</strong> is a string. Open the file and read the header row and data from the csv

file. Return the header and data. This should be able to read any number of columns from the csv file.

<strong>main():</strong>

Create a main function module and from the main function call these functions to find the statistics. In your main function, there can be several lists to for storing returned minimums, maximums, standard deviations. To call the functions of <strong>StatisticsCalculation</strong> module, you need to import the module. You may call the functions in any order but the result should be exactly similar to assignment 1 question 1.

<strong>Data source:</strong> <a href="http://climate.weather.gc.ca/climate_data/daily_data_e.html?StationID=27174">http://climate.weather.</a><a href="http://climate.weather.gc.ca/climate_data/daily_data_e.html?StationID=27174">g</a><a href="http://climate.weather.gc.ca/climate_data/daily_data_e.html?StationID=27174">c.ca/climate_data/dail</a><a href="http://climate.weather.gc.ca/climate_data/daily_data_e.html?StationID=27174">y</a><a href="http://climate.weather.gc.ca/climate_data/daily_data_e.html?StationID=27174">_data_e.html?StationID=27174</a>

<strong>Sample output:</strong>