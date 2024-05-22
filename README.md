# Lending Club Case Stduy
> Assist Lending Club in mitigating credit losses


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The objective is to pinpoint applicants at risk of defaulting on loans, enabling a reduction in credit losses. This case study aims to achieve this goal through exploratory data analysis (EDA) using the provided [dataset](./loan.csv).
- In essence, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Analysis indicates a strong correlation between loan amount and default probability , revealing increased chances of default
- The distribution of loans across credit grades highlights a trend where Grade B recipients receive highest proportion of loans , followed by A and C.
-nterest rates fall within 9-14% range with few outliers reaching 22%, within the range this indicates markets norms whereas outliers signify potential risk factors
- Data also suggests direct relationship between higher interest rates and increased loan default
- Loans associated with small businesses , debt consolidation and housing tend to have a higher interest rates.
- Borrowed with higher DTI ratios especially Grade A , exhibit default probabilities , this signifies DTI as one of the predictive indicators
- Analysis also reveals that majority of loan applicants reside in rented or mortgaged accommodations, with rents exhibiting a higher percentage of fully paid loans.
- Data also demonstrates clear association between higher interest rates and increased instances instances of loans being charged off 
- The duration of loan term, whether 36 or 60 months, does not significantly influence default rates. Hence loan term alone is not a decisive factor in predicting loan defaults 
- Lower grade borrowers tend to receive higher loan amounts and exhibit a higher chance for default. 
Borrowers with longer employment tenures and higher loan amounts are more susceptible 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.11.7
- Matplotlib - version 3.8.4
- Numpy - version 1.26.4
- Pandas - version 2.1.4
- Seaborn - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by live session of upGrad on EDA
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platformm.


## Contact
Created by [@ranjitha96] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->