# Covid and Masking in Gwinnet County

## Goal


## Setup

### Environment
All scripts are run in Jupyter Notebook using python 3.7.9. The full list of dependencies can be found in the requirements.txt file

### How to Run
All code used is contained in the <> notebook. Running all cells will collect and process all data. See the description in the notebook to skip the data acquisition or processing stages.

### Stages

#### 1. Data Acquisition

## Data

### Case Data

#### Source
Case data was obtained from a [Kaggle project](https://www.kaggle.com/antgoldbloom/covid19-data-from-john-hopkins-university/version/377?select=RAW_us_confirmed_cases.csv) that provides access to the COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University. It was accessed on 2021-11-1.

#### Description

#### Notes
Although the repository was accessed in October 2021, it was posted in October 2017.

### Mask Mandate Data

#### Source
Mask mandate data was obtained from the [CDC Policy Surveillance](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i) site, accessed on 2021-11-01.


#### Description
1. "Face_Masks_Required_in_Public": A requirement for individuals operating in a personal capacity to wear masks 1) anywhere outside their homes or 2) both in retail businesses and in restaurants/food establishments.

#### Notes


### Mask Compliance Data

#### Source
A [New York Times and Dynata Estimate](https://github.com/nytimes/covid-19-data/tree/master/mask-use) based on survey data from July 2nd to 14th, 2020. The data is based on 250,000 online survey responses and contains estimates down to the county level of mask usage while in public. Specifically, each participant was asked: How often do you wear a mask in public when you expect to be within six feet of another person? This was accessed on 2021-11-01.


#### Description


#### Notes
