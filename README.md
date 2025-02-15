# How seasonality affects the Airbnb prices in the various cities situated in different hemispheres

This project gives an insight into how hemisphere effects the price of an Airbnb. 

## Research motivation

The vacation seasons is one of the most busy time periods for Airbnb hosts, 
with an large influx of tourists traveling to popular vacation spots to spend their holidays, increasing the demand therefore the prices. 
Nevertheless, the vacation seasons differ depending on the hemisphere. 
This project aims to compare the price of Airbnb between various cities across the globe situated in two different hemispheres, 
to determine the effect of seasonality on the price of Airbnb in these cities.
-->NEEDS ADDITIONAL INFO<--

## Research question

What effect does seaonality (northern hemisphere versus southern hemisphere) have on the price of Airbnb, considering the difference in summer and winter season timings due to their geographical location?

## Data
For this research project Airbnb data will be used, accessed through Inside Airbnb.The datasets used in this project are all based on the listings in (Northern Hemispehere) Lisbon, Amsterdam, Prague and Paris, and (Southern Hemispehere) Rio de Janeiro, Buenos Aires, Mexico City and Santiago.

## Methods and results
In this chapter we will give a brief overview of the methods that have been applied, followed by the results from the ANOVA test and ends with the conclusion to our research question.

### Method:
1. Data will be acquired from [Inside Airbnb](http://insideairbnb.com/)
2. Data cleaning/auditing will be performed as required
3. Regression analysis will be performed on the date and prices
4. Automate and refine this process

### Results:


### Conclusion:



## Repository overview

### Repository contents

The raw data used is contained in a folder called "data".

The source code is stored in a folder called "src".

The generated files are stored in the generated folder "gen".

Within the "gen" folder there are separate folders for the data preparation and the data analysis stages, as well as the final deliverable of the project; namely, "data-preparation", "analysis", and "paper".

Any temporary files will be stored in "temp".

Any final products from the various stages in the pipeline will be stored in the "output" folder.

Any files related to issues with the data or the model estimation will be stored in the "audit folder".

### Repository structure

	├── README.md
	├── data
	├── gen
	│   ├── analysis
	│   ├── data-preparation
	│   └── paper
	└── src
 	   ├── analysis
 	   ├── data-preparation
 	   └── paper
	   
## Dependencies
Please follow the installation guide on http://tilburgsciencehub.com/.
- Python. [Installation guide](https://tilburgsciencehub.com/building-blocks/configure-your-computer/statistics-and-computation/python/)
For Python, make sure you have installed below packages: 
<-- include packages -->
- R. [Installation guide](https://tilburgsciencehub.com/building-blocks/configure-your-computer/statistics-and-computation/r/)
For R, make sure you have installed and loaded below packages:
<-- include packages --> 
- Make. [Installation guide](https://tilburgsciencehub.com/building-blocks/configure-your-computer/automation-and-workflows/make/)    

## Running instructions
We recommend the following instructions for people that are interested in running the code:
1. Fork this repository
2. Open your command line / terminal and run the following: 
git clone https://github.com/{your username}/Airbnb-Seasonalities.git
3. Set your working directory to working directory and run the following command: 
make
4. When ake has succesfully run all the code, it will generate something. 


## More resources

## About

This research is carried out in implementation of the course Data Preparation and Workflow Management. This is a part of the Master program of Marketing Analytics at Tilburg University. The following authors contributed to this research:

Zhiyong Zhou
Marieke Beerens
Marlou Klute
Kim Gresnigt
Mevludin Ademovic
