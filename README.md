# Project-1: Organizing and Summarizing Air Quality Data
This repository includes the files for Project No.1

## Raw Code
- [Raw Code](https://github.com/NathanJones08/Project-1/blob/main/AirQuality_Daily_StudentVersion.csv)

## Project Code
- [Project Code](https://github.com/NathanJones08/Project-1/blob/main/Project%201%20(1).ipynb)

## Scope of Work
- [SOW](https://github.com/NathanJones08/Project-1/blob/main/SOW%20for%20Project%20%231%20(1).docx)

### ANNOTATED CODE DOCUMENT
- [ACD](https://github.com/NathanJones08/Project-1/blob/main/ACD%20for%20Projcet%20%231.docx)

## Prompts
1. What are the 5 locations in Nebraska with the highest mean and median concentrations of VOC, PM 2.5 and PM 10.0?
2. On what days did the maximum values occur and where did this maximums occur?
   1. What are some potential reasons these maximums occurred on these days in these locations based on initial research?
3. Does humidity and temperature have a noticeable effect on air quality?
4. Have there been any Air Quality Index (AQI) health risks (unhealthy for sensitive populations) at any of the locations in the dataset for PM 2.5 and PM 10 based on the EPA’s AQI ratings?
   1. When did they happen?
   2. Based on exploratory research, what could have been a potential cause?
5. Bonus: Does the sensor altitude have an impact on the air quality values?

## Solution
### Task 1
- Data from AirPurple dataset will be extracted making a group and aggregate, which will filter the data by location and include the maximums.
- This will be transferred to a table where the top five locations maximums will be extracted based on VOC, PM2.5 and PM10.

### Task 2
-  Data from AirPurple dataset will be extracted making a group and aggregate, maximum filtering the dates and locations of said maximums.
-   The data will be transferred to a table to clean up and organize the data according to Date, Location, and recorded maximum.

### Task 3 
- Data from AirPurple dataset will be extracted and transferred and organized in a table file using data processing in the Python software environment.
- The humidity, temperature, and altitude will be extracted.
- While being cleaned in a table, the data will be formatted for temperatures from <32 degrees, 32-50 degrees, 51-70 degrees, >70 degrees.
- The humidity will be referenced against the air quality to visualize if there is a noticeable difference.

### Task 4
- Data from AirPurple dataset will be extracted and transferred and organized in a table using data processing in the Python software environment.
- The data will be formatted for an AQI >101, and searched by the following groups PM 2.5 and PM 10.

### Task 5
- The altitude has already been extracted from the AirPurple dataset
- The altitude will be referenced against air quality to visualize if there is a noticeable difference.

### Final Deliverable
- As a final deliverable our team will include the cleaned CSV file and the raw data file.

### Summary
- [Final Summary](https://github.com/NathanJones08/Project-1/blob/main/Summary%20for%20Project%20%231.docx)
