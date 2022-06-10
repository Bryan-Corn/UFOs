![image](https://github.com/Bryan-Corn/UFOs/blob/main/Readme_Images/UFO_heading.png)

# UFOs
Module 11

## Overview

The purpose of this project is to organize UFO data stored in a JavaScrpt array into a filterable table based on certain criteria. The table will is dynamic, based on user input, and is displayed in an attractive webpage for easy access and viewing. The webpage is customized using Bootstrap and utilizes ECMAScript.


## Results

The filters have defined defaults that do not affect the table but show the user the proper format of each field. The defaults are the alphabetical first for each field but there is an issue with the date format as noted above the next image:
![image](https://github.com/Bryan-Corn/UFOs/blob/main/Readme_Images/UFO.png)


The first filter is for the date. A user can enter a date to show all the sightings on that day that are in our database. The default in this field is not the first date of our sightings as 1/10/2010 is recognized before 1/1/2010. The dates from 1/1/2010 to 1/9/2010 could be changed in the database to 1/01/2010 to 1/09/2010 to correct this.
![image](https://github.com/Bryan-Corn/UFOs/blob/main/Readme_Images/UFO_1.png)


The next filter is for the city:
![image](https://github.com/Bryan-Corn/UFOs/blob/main/Readme_Images/UFO_2.png)


The state (or province for Canada) is next:
![image](https://github.com/Bryan-Corn/UFOs/blob/main/Readme_Images/UFO_3.png)


Country is the next filter field:
![image](https://github.com/Bryan-Corn/UFOs/blob/main/Readme_Images/UFO_4.png)


Finally, the shape of the reported object is the last filter:
![image](https://github.com/Bryan-Corn/UFOs/blob/main/Readme_Images/UFO_5.png)


To reset the filters to default, the user can delete any entry in a filter field and hit enter.

## Summary

### Filter Limitations
One issue with this design is that the filter entries must match the data exactly. This requires standardization of the columns for which we have a filter. Filtering the 'duration' element would be very difficult as the data for duration is diverse. A possible fix for this would be to group the durations into defined categories.

### Data Limitations
Another limitation is that the database is static and pretty limited. Adding more sightings would be beneficial but would require a lot of cleaning to match the existing data. Adding new sightings as they occur would go a long way in increasing this webpage's utility.
