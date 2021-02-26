# Investigate a Dataset - Evaluation GDP per sector for several countries
## by Lucas Amaro de Oliveira

Project to Udacity in partial fulfillment of the requirements for the Danalyst Nanodegree.

In this project, I will analyze a dataset and then communicate my findings about it. I will use the Python libraries NumPy, pandas, and Matplotlib to make my analysis easier.

## Table of Contents

* [Introduction](#Introduction)
* [Data Wrangling](#Data-Wrangling)
* [Summary](#Summary)

## Introduction

In the present project, four variable will be analysed. The first three refers to the economy sectors: agriculture, industry, and services; the last one is the GDP per capita; Based on those data the following questions will be enseared:

* From where the richness of the countries come from?
* Which countries had the most increase in the GDP/per capita over the past 5 decades?

## Data Wrangling

#### Sector databases
The economy GDP is divided into three sectors: agriculture, industry, and services.
For all three sectors, the value add is the net output of a sector after adding up all outputs and subtracting intermediate inputs. It is calculated without making deductions for depreciation of fabricated assets or depletion and degradation of natural resources. The origin of value added is determined by the International Standard Industrial Classification (ISIC), revision 3. Note: For VAB countries, gross value added at factor cost is used as the denominator.

##### Agriculture (% of GDP)
*description*: Agriculture corresponds to ISIC divisions 1-5 and includes forestry, hunting, and fishing, as well as cultivation of crops and livestock production. 
*source link*: https://data.worldbank.org/indicator/NV.AGR.TOTL.ZS

##### Industry (% of GDP)
*description*: Industry corresponds to ISIC division 10-45 and includes manufacturing (ISIC divisions 15-37). It comprises value added in mining, manufacturing (also reported as separated subgroup), construction, electricity, water, and gas. 
*source link*: https://data.worldbank.org/indicator/NV.IND.TOTL.ZS

##### Services (% of GDP)
*description*: Services correspond to ISIC division 50-99 and they include value added in wholesale and retail trade (including hotels and restaurants), transport, and government, financial, professional, and personal services such as education, health care, and real state services. Also included are imputed bank service charges, import duties, and any statistical discrepancies noted by national compilers as well as discrepancies arising from rescaling.
*source link*: https://data.worldbank.org/indicator/NV.SRV.TETC.ZS

#### GDP/capita(US$, inflation-adjusted)
*description*: GDP per capita is gross domestic product divided by midyear population. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation fo natural resources. Data are in constant 2010 US dollars.

*source link*: https://data.worldbank.org/indicator/NY.GDP.PCAP.KD


## Summary

The dependency on agriculture drops exponentially as the GDP per capita grows. This may be because of a limit on the land available for agriculture. The GDP can not grow over this limit based only on this sector.

Despite the fact countries with high GDP per capita presented on average a low industry ratio compared with countries with low GDP per capita, there is a slight correlation between industrialization and higher GDP per capita. The countries with very high GDP per capita presented a mean industry ratio value 28.54% higher than the countries with very low GDP per capita.

There appears to be a correlation between countries with high GDP per capita and the ratio of the services sector. This correlation is stronger than the one found in the industry sector. The countries with very high GDP per capita presented a mean services ratio value 34.36% higher than the countries with very low GDP per capita. Since services are less depending on infrastructure than industry, it allows the services sector to grow more. Furthermore, when people overcome the need for food (agriculture) and stuff (industry), services become the growing expenditure.

The countries that presented the fast growth in the past 5 decades are China, South Korea, Botswana, Singapore, and Myanmar.