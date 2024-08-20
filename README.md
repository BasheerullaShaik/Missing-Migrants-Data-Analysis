# Missing-Migrants-Data-Analysis
**Introduction**
Migration is a significant global issue with profound humanitarian and socio-economic implications. The dataset analyzed in this project, sourced from the Missing Migrants Project, includes information on migrants, refugees, and asylum-seekers who have died or gone missing during their migration journey. The primary motivation behind this analysis stems from observing the increasing number of migrants around us and discovering that North America is the most frequently used migration route. This repository contains a thorough examination of 13,370 migration-related incidents.

**Dataset Description**
The dataset consists of 13,370 rows and 25 columns, tracking incidents involving migrants, refugees, and asylum-seekers. The data includes several attributes, some of which have missing values. Below is a summary of the key attributes in the dataset:

Main ID
Incident ID
Incident Type
Region of Incident
Website Date
Incident Year
Reported Month
Number of Dead
Minimum Estimated Number of Missing
Total Number of Dead and Missing
Number of Survivors
Number of Females
Number of Males
Number of Children
Region of Origin
Cause of Death
Country of Origin
Migration Route
Location of Death
Information Source
Coordinates
UNSD Geographical Grouping

**Data Transformation and Exploratory Data Analysis (EDA)**
Data cleaning and transformation were essential steps in preparing the dataset for analysis. The following tasks were performed:

**Data Cleaning:** Removed duplicates, transformed data types, and dealt with outliers.
**Missing Data Handling:** Imputed missing values in numeric columns with zeroes or the median, and removed rows where imputation was not feasible.
**EDA Techniques:** Used the describe() function to understand data distribution and info() function to identify data types and missing values.

**Analysis**
The analysis focused on several key areas:

**Cause of Death:** Investigated the leading causes of death among migrants.
**Migration Regions:** Identified regions with a higher number of migration incidents.
**Migration Routes:** Examined the routes most frequently used by migrants, with a particular focus on the US-Mexico border.
**Survival Rates:** Compared the number of dead, missing, and surviving migrants over the years.

**Key Findings**
**Leading Cause of Death:** Drowning is the most common cause of death.
**High Migration Routes and Regions:** The US-Mexico border and North America region have the highest migration rates.
**Survival Rate:** The analysis reveals a 59% survival rate among migrants.
**Regional Death Analysis:** The Mediterranean region has the highest number of deaths.

**Managerial Implications**
The findings from this analysis have several critical implications for policymakers and international organizations:

**Safety Precautions and Training:** Implementation of safety measures and training for migrants.
**Immigration Policy Reform:** Reforming immigration policies to facilitate safer migration routes.
**Real-time Monitoring and Response:** Establishing real-time monitoring and response systems.
**UN Intervention:** Urgent UN intervention is required in the Mediterranean region.
**Increased Security and Awareness:** Enhancing security measures and raising awareness among migrants.
