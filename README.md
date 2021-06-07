# UFO-Challenge

## Resources
Data Source: 

[index.html](https://github.com/monsecc01/UFO-Challenge/blob/800fdffd0c460aab27be917dce44d1c478d10114/index.html)

[data.js](https://github.com/monsecc01/UFO-Challenge/blob/800fdffd0c460aab27be917dce44d1c478d10114/static/js/data.js)

[app.js](https://github.com/monsecc01/UFO-Challenge/blob/800fdffd0c460aab27be917dce44d1c478d10114/static/js/app.js)

[style.css](https://github.com/monsecc01/UFO-Challenge/blob/800fdffd0c460aab27be917dce44d1c478d10114/static/CSS/style.css)

Software: Visual Studio Code 1.55.1

## Overview of Project: 
The purpose of this analysis was to create a webpage with an interactive data visualization of UFO sighting data. The webpage will display a table with the following UFO sighting information:
* Date
* City
* State
* Country
* Shape
* Duration
* Comments

The table will be interactive to be able to filter by *Date, City, State, Country and Shape*, making it easier to focus on specific UFO sighting information.

## Results: 
A user can interact with the UFO Finder webpage by using the Date, City, State, Country and Shape filters. The filters work by entering data text into the desired fields and then pressing "enter" to display the filtered data. Multiple filters can be used to further narrow the search. To clear the filters and reset the table, simply clear the filter fields and press enter or click elsewhere on the screen.

The unfiltered table has place holder text to demonstrate the user the format of each each field.

<img width="874" alt="No filters" src="https://user-images.githubusercontent.com/81447450/120949897-2dafdd80-c70b-11eb-92b3-a663c5bee922.png">

The date filter for example uses the format MM/DD/YYYY. 

<img width="875" alt="date filter" src="https://user-images.githubusercontent.com/81447450/120950099-aa42bc00-c70b-11eb-81fe-f43ab822489e.png">

Multiple filters can be used to narrow the data search. Simply input the desired data text into the filter fields and press "enter".

<img width="857" alt="multiple filters" src="https://user-images.githubusercontent.com/81447450/120950255-0a396280-c70c-11eb-82df-4558b3154fae.png">

## Summary: 
One drawback of being able to filter by multiple criteria is that now we have to manually delete every field we filtered for if we want to reset the table.

Two recommendations for further development are:
1.  Add a "reset" button to facilitate resetting the table.
2.  A drop down calendar for the date field would make entering dates easier. An added benefit could be the elimination of date format errors by automatically populating the date picked into the field.

