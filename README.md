# Analyze Chicago Crime Data

## Data Source

- [Chicago Data Portal](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2)

## Tasks and notebooks

- Separate raw data to CSV files by year (2001-2023) and do basic data cleaning ([notebook](https://github.com/jiashenyue/chicago-crime-data/blob/main/part-1.1-preparing-crime-data.ipynb))
 - Due to file size, all yearly CSV files are not uploaded to [Data folder](https://github.com/jiashenyue/chicago-crime-data/tree/main/Data)

- Answer stakeholder questions ([notebook](https://github.com/jiashenyue/chicago-crime-data/blob/main/part-1.2-answer-questions-use-chicago-crime-data.ipynb))

## 1. Comparing Police Districts
### Which district has the most crimes? Which has the least?

![png](https://github.com/jiashenyue/chicago-crime-data/blob/main/PNG/District_barplot.png)

## 2. Crimes Across the Years
### Is the total number of crimes increasing or decreasing across the years?

![png](https://github.com/jiashenyue/chicago-crime-data/blob/main/PNG/change-crime-yearly.png)

### Are there any individual crimes that are doing the opposite (e.g decreasing when overall crime is increasing or vice-versa)?

- `CRIMINAL SEXUAL ASSAULT` and `CONCEALED CARRY LICENSE VIOLATION` are two primary types of crime that have increased between 2001 and 2023 despite the overall trend of decrease in crime

![png](https://github.com/jiashenyue/chicago-crime-data/blob/main/PNG/change-crime-by-type.png)

## 3. Comparing Months
### What months have the most crime? What months have the least?

MonthName |	Count
----------|------
July	| 717048
August	| 710209
May	| 682775
June	| 681565
October	| 676081
September	| 668030
March	| 645322
April	| 626998
January	| 621738
November	| 608773
December	| 579504
February	| 547286

![png](https://github.com/jiashenyue/chicago-crime-data/blob/main/PNG/crime-by-month.png)

### Are there any individual crimes that do not follow this pattern? If so, which crimes?

- The table below shows the month with the max and min occurrence of each primary crime type

Primary Type |	Max Month	| Min Month
-----|-----|----
ARSON	| July	|February
ASSAULT | May	| December
BATTERY	| July	| February
BURGLARY	| August	| February
CONCEALED CARRY LICENSE VIOLATION	| September	| December
CRIM SEXUAL ASSAULT	| July	| December
CRIMINAL DAMAGE	| July	| February
CRIMINAL SEXUAL ASSAULT	| January	| April
CRIMINAL TRESPASS	| March	| December
DECEPTIVE PRACTICE	| January	| February
DOMESTIC VIOLENCE	| January	| January
GAMBLING	| August	| December
HOMICIDE	| July	| February
HUMAN TRAFFICKING	| January	| November
INTERFERENCE WITH PUBLIC OFFICER	| August	| December
INTIMIDATION	| October	| November
KIDNAPPING	| May	| February
LIQUOR LAW VIOLATION	| June	| December
MOTOR VEHICLE THEFT	| October	| February
NARCOTICS	| March	| December
NON - CRIMINAL	| June	| March
NON-CRIMINAL	| October	| January
NON-CRIMINAL (SUBJECT SPECIFIED)	| February	| May
OBSCENITY	| October	| April
OFFENSE INVOLVING CHILDREN	| January	| November
OTHER NARCOTIC VIOLATION	| May	| October
OTHER OFFENSE	| March	| December
PROSTITUTION	| January	| December
PUBLIC INDECENCY	| August	| January
PUBLIC PEACE VIOLATION	| May	| December
RITUALISM	| January	| June
ROBBERY	| October	| February
SEX OFFENSE	| July	| December
STALKING	| July	| December
THEFT	| July	| February
WEAPONS VIOLATION	| May	| February
 
 
