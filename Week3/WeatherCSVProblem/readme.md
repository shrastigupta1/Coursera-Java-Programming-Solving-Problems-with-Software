1. Write a method named coldestHourInFile that takes a CSVParser as a parameter. This method should return the CSVRecord with the coldest temperature in the file. It should ignore temperature values of -9999. Additionally, write a void method named testColdestHourInFile() to test this method. This method should print out information about the coldest temperature, such as the time of its occurrence.
2. Write a method named fileWithColdestTemperature with no parameters. This method should return a string that is the name of the file from selected files that has the coldest temperature. Additionally, write a void method named testFileWithColdestTemperature() to test this method. Note that after determining the filename, you could call the method coldestHourInFile to determine the coldest temperature on that day. When fileWithColdestTemperature runs and selects the files for January 1–3 in 2014, the method should print out:
Coldest day was in file weather-2014-01-03.csv
Coldest temperature on that day was 21.9
All the Temperatures on the coldest day were:
2014-01-03 05:51:00: 41.0
2014-01-03 06:51:00: 39.0
2014-01-03 07:51:00: 35.1
2014-01-03 08:51:00: 30.9
2014-01-03 09:51:00: 28.0
2014-01-03 10:51:00: 25.0
2014-01-03 11:51:00: 24.1
3. Write a method named lowestHumidityInFile that takes a CSVParser as a parameter. This method should return the CSVRecord that has the lowest humidity. If there is a tie, return the first such record found. Note that sometimes there is not a number in the Humidity column but instead there is the string "N/A". This only happens very rarely. You should check to make sure the value you get is not "N/A" before converting it to a number. Additionally, write a void method named testLowestHumidityInFile() to test this method. This method should print the lowest humidity and the time it occurred. For example, for the file weather-2014-01-20.csv, the output should be:
   Lowest Humidity was 24 at 2014-01-20 19:51:00
4. Write the method lowestHumidityInManyFiles with no parameters. This method should return a CSVRecord that has the lowest humidity over all the files. If there is a tie, return the first such record found. Additionally, write a void method named testLowestHumidityInManyFiles() to test this method and to print the lowest humidity and the time it occurred. Be sure to test this method on two files so you can check if it is working correctly. If you run this program and select the files for January 19, 2014, and January 20, 2014, you should get:
Lowest Humidity was 24 at 2014-01-20 19:51:00
5. Write the method averageTemperatureInFile that takes a CSVParser as a parameter. This method should return a double that represents the average temperature in the file. Additionally, write a void method named testAverageTemperatureInFile() to test this method. When this method runs and selects the file for January 20, 2014, the method should print out:
- Average temperature in file is 44.93333333333334
6. Write the method averageTemperatureWithHighHumidityInFile that takes two parameters: a CSVParser named parser and an integer named value. This method should return a double that represents the average temperature of only those temperatures when the humidity was greater than or equal to value. Additionally, write a void method named testAverageTemperatureWithHighHumidityInFile() to test this method. When this method runs checking for humidity greater than or equal to 80 and selects the file for January 20, 2014, the method should print out:
  If you run the method checking for humidity greater than or equal to 80 and select the file March 20, 2014, a wetter day, the method should print out:
  Average Temp when high Humidity is 41.78666666666667
