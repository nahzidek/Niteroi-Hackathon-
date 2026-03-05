# Niteroi Project Data

## Overview
Complexo do Viradouro and Caramujo are areas in Niteroi that have long suffered high criminal activity and isolation. It has now been redeveloped for the general public, but the data analysis has been tricky. The project sponsor wants to know how to collect and analyze data that determines whether the redevelopment has actually caused less crime in the area, or if there is a "no snitching" code causing fewer crime reports.

Niteroi has provided an excel spreadsheet that covers crime occurrences, including the crime type(homicide, robbery, and theft crimes), location, and time from 2021 to 2025, as well as shapefiles georeferencing the Viradouro and Caramujo areas. 

## Data Sources
All Files were recieved from Felipe Leichsnering Mendes
*   **Niteroi Crime*: Primary, proprietary data
    *   2021-2025
    *   Translated_Sheet_Final.xlsx is the translated version of Niteroi_original_Dados_SEOP.xlsx

*   **Viradouro**: 
    * Shape files
    * Viradouro and Caramujo areas

## Data Processing & Cleaning
1.  **Translation**: All Columns were translated to English from Portuguese using Google trans API

## Data Structure

The data is organized as follows:

*   `Raw Data/`: This folder contains the original raw Portuguese crime data 
    *   `Niteroi_original_Dados_SEOP.xlsx`: This file contains the original data in Portuguese on homicide, robbery, and theft crimes from 2021-
*   `Cleaned Data/`: This folder contains the translated crime data 
    *   `translated_sheet_final.xlsx`: This file contains the translated data in Englishon homicide, robbery, and theft crimes from 2021-2025 
*   `Shapefiles/`: This folder contains shapefiles. (No need to list all .shp, .sbx files individually)
    *   `Viradouro.shp`: georeferencing of the Viradouro and Caramujo areas.


## Use Cases and Inspiration

A few use cases to inspire the participants.

1.  **Use Case**: Different crimes by years to analyze the trends from before and after redevelopment.
2.  **Idea**: Dashboard allowing users to switch between years and crime type as well as see the full scale
3.  **Hard Problem**: Find where the crime drops, stagnates, or any other changes, and identify patterns that can imply a conclusion
