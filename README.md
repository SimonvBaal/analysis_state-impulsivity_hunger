# State impulsivity, hunger, and urges

## Description
In this project we analyse the effects of hunger and state impulsivity on the 
intensity of urges, and participants' ability to control them. Data files will
end with 'hsi', as an identifier for the project.

The data was collected using Ecological Momentary Assessment (aka experience 
sampling). There are 45 participants and each participant is asked to report 
about six different urges in everyday life, via a smartphone app, called SEMA3.

We also collected some demographic data contained in the 
'raw_eligibility-anon_hsi.csv' file.

## Installation
### Requirements
R 4.0.5
RStudio

### Instructions
Please download the entire folder to your computer.
Then, navigate to the folder and click on the file called "analysis_ema-avg.Rproj". 
The project should open in RStudio with the environment pre-loaded.

The package management for this project was made using 'renv'. This means that
when you run the following command, all the packages with the correct versions
will be loaded.
> renv::restore()

## Usage
There are three ways to start working with this project.

The first, and the easiest/fastest, is something RStudio may do for you, and 
that is loading the .RData file. To do this directly, one simply runs 
"load(.RData)". 

The second option is to run directly from the analysis_ema-avg.Rmd file, which 
uses the pre-cleaned dataset.

The third option is to open the cleaning_ema-avg.Rmd file. Running this file 
will pull datasets from the raw-data folder and clean them for use in the 
analysis Rmarkdown file mentioned above (this file will be stored in the 
'output/clean-data' subfolder).

Figures in the paper can be reproduced in the analysis script file and can also 
be found in the 'output/figures' folder.

## Support
Should you have any problems, please send an email to either my permanent email: 
simonvanbaal.behsci@gmail.com, or my institutional email listed on my profile page.

## Contributing
This project is not open for contributions. However, if you find a mistake,
please contact me via the email address listed above.

## Authors and acknowledgement
I wrote the code for this project myself, but I would like to thank my
collaborators for their input: Antonio Verdejo-Garcia, Neda Moskovsky, 
and Jakob Hohwy.

## Project status
This project is finished.
