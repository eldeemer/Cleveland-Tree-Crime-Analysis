# Cleveland-Tree-Crime-Analysis
This project intends to find an association between tree cover and violent crime in the city of Cleveland, OH, using a least squares regression and bootstrapping in STATA. 
## Purpose
This code was created for my senior Political Science Capstone research paper as the quantitative analysis half of a mixed methods project. I completed this research independently with advising from a faculty member. Though the project is normally exclusively qualitative in nature, I opted to include a quantitative element to present a more comprehensive and compelling argument for how tree cover impacts crime. I used a combination of two public datasets. The first was the Urban Tree Canopy Assessment from the Cuyahoga County Planning Commission, a mapping imitative completed by the city of Cleveland to understand land usage for the county. The second was an aggregation of other datasets (including the ACS, CPS, Cleveland Police Reporting, etc.) stored in the Northeast Ohio Community and Neighborhood Data for Organizing data suite. 
## Usage
This project can be used by city officials to better understand the landscape of tree cover and crime in order to enact local legislation and initiatives. My results show a negative relationship between the dependent variable (violent crime) and the independence variable (tree cover), indicating that tree removal should be limited and long term tree planting should be increased. Some limitations include a small number of observations (something accounted for through bootstrapping) as well as a lack of temporal variety in the data. This same model could be used for other forms of crime as well as in other cities, or on a state/nationwide scale. The covariates accounted for are in line with those used in similar literature. This project adds to a wealth of literature on the topic of greenspace and crime in urban environments, where mixed results have been found in other cities. 
## File Descriptions
- POSC Capstone Do.do: The plaintext .do file needed for STATA to run the code
- POSC_Capstone.log: The plaintext code with model outputs
- Property Crime Scatter.png: The correlation graph for tree cover on property crime
- Violent Crime Scatter.png: The correlation graph for tree cover on violent crime
