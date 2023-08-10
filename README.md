# Kinsa Historic Data Share

## Who is Kinsa?
Kinsa's solutions predict, and help prevent, the impact of infectious illness on healthcare organizations and families. We use advanced technology and epidemiological techniques to analyze unique illness signals, gathered from millions of households and other sources, to track and forecast the spread of illness earlier than other systems and get ahead of the next surge.

## How do we collect this data?
Kinsa sells and freely distributes FDA-cleared, Bluetooth-enabled smart thermometers. Kinsa thermometers pair with an associated app and record temperatures and symptoms reported by users. When recording symptoms, users can assign symptoms to multiple family members within a single household. Users can opt in to share location of their readings. Kinsa anonymizes and aggregates these readings to produce illness signals for different regions across the US. Kinsa households represent a diverse sample of the US population with 2.5 million households across all 50 states.

## How to interpret the data?
The data provided in this repository are estimates of the percent of a region’s population experiencing illness. All estimates are 7 day sums of symptom incidence. Kinsa age weights our users to ensure that estimates represent the percent of the entire population that is experiencing an illness episode. 

Since people reach for their thermometer at the first signs of a fever, Kinsa captures data at symptom onset. Other surveillance systems will not start to collect data until a patient has become sick enough to interact with the health system. Thus, Kinsa’s data can capture mild respiratory illness earlier and more robustly than traditional public health surveillance.

## Limitations
The data shown is a small subset of the total Kinsa data available. As with all disease surveillance, no signle source can capture all illness trends across the country. Kinsa users must have access to a smartphone to use the app. Additionally, some rural states may have a low number of active users and therefore have noisier data for less common symptoms.

## Available data in this repository
Symptoms included: 
- fever
- cough
- sore throat
- runny nose
- stuffy nose
- diarrhea
- vomiting
- nausea
- loss of taste/smell (added June 20, 2020)
- stomach ache
- fatigue
- body aches
- chills

## How/who to contact for more data/inquiries
This repository is a small sample of the available data that Kinsa collects. If you would like to access more recent or historical data, more granular data, daily data, or disease-specific data, please reach out to insights@kinsainsights.com with your inquiry. Kinsa has an API available where the most up to date Kinsa data can be added to your nightly data pipeline. 

## Data Dictionary
- date
- weekly date (Mondays) ranging from Jan 2018 to July 2022
- region
- Includes all 50 states + DC and national data (region = ‘US’)
- symptom_type
- The specific symptom incidence
- percent_ill
- percent of Kinsa users who have newly experienced the symptom within the past 7 days
