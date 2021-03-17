# Read me, Seymour!

This repo houses my attempt at the course [Final Project](https://dataviz-2021.netlify.app/assignments/#final-project) from the Winter 2021 offering of [EDLD 652](https://dataviz-2021.netlify.app): *Data Visualization for Educational Data Science*, offered through the University of Oregon's College of Education.

In order to successfully run this code, you may need to install a few packages. These lines of code should suffice to make it happen:

install.packages(c("devtools", "mapproj", "tidyverse", "gtools"))

devtools::install_github("marcusvolz/strava")

The Strava GPX dataset associated with this repo is too large to house on GitHub. If you would like to reproduce the plots shown here, you will need to extract the file called JoeStrava.zip which should be in the same folder as the index.RMD file. Just click on that and it should bring the data folder right in for you, and then things will run.

If for some reason you can't find it, you may download that [necessary file](https://github.com/JoeSwinehart/DataVizProject/raw/main/data/JoeStrava.zip) here. 

Once you have extracted the data, ensure that that the new "data"" folder is in the directory that houses the .Rmd file and things should work just fine... 

