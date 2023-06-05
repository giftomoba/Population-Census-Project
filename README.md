# Population-Census-Project
The main aim of this project is to help the government decide on the best service to invest in and also the best infrastructure to be built in an unused plot of land.

## Background Information:
Every ten years, the United Kingdom undertakes a census of the population, with the most recent one having 
been conducted in 2021. The purpose of such a census is to compare different people across the nation and to 
provide the government with accurate statistics of the population to enable better planning, to develop policies, 
and to allocate certain funding. 

This project provides a comprehensive and detailed analysis of the population data of a moderately sized town, 
situated in between two major cities. The aim is to make insightful recommendations on what the local 
government should build on an unoccupied piece of land.
To ensure accurate recommendations, errors in the data such as missing (null) values, spurious entries and
misleading information were treated or dropped where appropriate.

Furthermore, a well detailed visualization and analysis will be used to arrive at the recommendations in the latter 
part of the report.


## Data Dictionary: 
The mock census you will be given contains randomly generate data using the Faker package in Python. It has 
been generated in a similar manner to (and designed to directly emulate the format of) the 1881 census of the 
UK wherein only a few questions were asked of the population. The fields recorded are as follows: 
- Street Number (this is set to “1” if it is a unique dwelling); 
- Street Name; 
- First Name of occupant; 
- Surname of occupant; 
- Age of occupant; 
- Relationship to the “Head” of the household (anyone aged over 18 can be a “Head” – they are simply the person who had the responsibility to fill in the census details); 
- Marital status (one of: Single, Married, Divorced, Widowed, or “NA” in the case of minors); 
- Gender (one of: Male, Female; note that other responses were not implemented in 1881); 
- Occupation (this field was implemented in a modern style, rather than typical 1881 occupations); 
- Infirmity (we have implemented a limited set of infirmities following the style of 1881); 
- Religion (we have implemented a set of real-world religions).

## Project Task:
- Clean and preprocess the data and make necessary visualizations.
- To advise on what the government should build on an unused plot of land
- To provide insights based on the data into what services should be invested in.

## The Various Data preprocessing and visualizations done can be found on the Jupyter file and project report.

## RECOMMENDATIONS:
Coupled with the estimated number of commuters currently living in the town, there seem to be a good number 
of students (non-tertiary) who would have attained the minimum age required by law to enter the university in 
approximately ten years’ time. Hence, it is imperative for the local authorities to build train and subway stations 
to prepare for this increased number of commuters in the future. The analysis also suggests an influx of people 
within the working age into the town and this may increase as the town further develops. So having a train station 
to cater for the influx of people into the town, as well as commuters leaving the town, would efficiently decongest 
the road network.

Although the population within the employment age range had a good percentage employed, there were still a 
few who were unemployed (ages predominantly between 34 and 50 years). Also, it is worthwhile to note that 
students in higher institutions would soon enter the job market and would have to compete with those currently 
unemployed as well as others from outside the town seeking jobs within the town. Hence, an investment in 
employment and skill building would highly impact positively in further reducing the unemployment rate and 
ensure most university graduates are employable.

Furthermore, in addition to investment in infrastructure due to influx of people into the town in search of job or 
settlement, there would also be a need to invest in care as seen from the future retirement analysis because 
there is likely going to be over 30% increase in the number of the population above retirement age and may be 
needing care in the future, even though the population appear healthy at old age.
