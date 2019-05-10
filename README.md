The Effects of the Batter's Eye on Hitting Quality

Hello and thank you for stumbling upon the early stages of my thesis.

If you want to read about what I have working on, feel free to look at the Gillingham_Econ_Project.pdf.   

If you are wanting to recreate my results, however, you will have to do a little bit of data collection yourself. GitHub will not allow me to upload files larger than 25 MB, and this thesis is looking at every pitch thrown in the MLB from 2017-2018. You may want to take a moment to consider your computing power, because you will be working with about 1.4 million rows of data. 

- First, go to https://baseballsavant.mlb.com/statcast_search

- Located in the first column, you will need to change the "Player Type" to Batter.

- Further down the first column you will see "Group By", I had it grouped by Player Name. If you are wanting to do exactly what I did, don't change that! But if you want to be better than me, group it by stadium and it will probably make your life a lot easier. Plus you will be able to remove the line of code that un-groups batters. 

- In the second column change the year from 2019 to 2017-2018. I actually downloaded the years separately but if you combine them it will save you time and you will be able to remove couple lines of code in DataPrep. 

- Click Search and wait until your results pop up (this may take up to a minute or so).

- After getting your search results there will be a picture of a floppy disk. If you don't know what a floppy disk is, you should probably Google it, but it is located on the right side of the screen just below and to the left of the words "Save Search". Clicking it should automatically download all of the data that you will need.

- Save it to an easy to remember place because you will need the file path when loading the data into R (or python or Julia or whatever you know best). 

From there you should be able to source the code and it will reproduce what I have written in the .pdf. There are notes in the code at places where I got caught up to try and help if the same thing happens to you.

Be sure to start with the DataPrep file. This will have all of the libraries you need and will put the characteristics that I have into the dataset. The process of how these variables were created is in the .pdf. 
