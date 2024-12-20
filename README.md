# BUSINESS UNDERSTANDING

The main goal is to analyze and predict the risks associated with purchasing and operating airplanes for both commercial and private enterprises, as part of my company's new diversification strategy.

## PROBLEM STATEMENT

The goal of this analysis is to identyfy key factors influencing the viability of aircraft operations. Specifically, risks associated with airplane accidents and the survival rates following such incidents shall be key.This is to minimize risk to passangers and the aviation company

## OBJECTIVES OF THE ANALYSIS

+ Investigate the relationship between engine type and the frequency of accidents.
+ Examine the correlation between the number of engines per aircraft and the recorded number of accidents.
+ Identify and analyze key factors that contribute to aircraft accidents, such as weather conditions and amateur-built aircraft.

### DATA
The National Transportation Safety Board (NTSB), an independent U.S. government agency dedicated to collecting data and conducting investigations to minimize accidents, has provided data dating back to 1962. This data primarily covers accidents occurring within the United States and Canada. The datasets include critical factors that could contribute to accidents, such as weather conditions, engine details, pilot information, and the phase of flight.

#### METHODS

Predictive modeling and descriptive analysis are used in this project to examine historical aviation data, identifying trends in aircraft performance, accident rates, and safety records. These methods uncover key patterns and provide insights to enhance aviation safety

##### RESULTS
![Alt text](https://private-user-images.githubusercontent.com/185777876/391877085-18b9f0ba-b630-466f-a3d6-49183cd53e3c.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzMyMTYwMjQsIm5iZiI6MTczMzIxNTcyNCwicGF0aCI6Ii8xODU3Nzc4NzYvMzkxODc3MDg1LTE4YjlmMGJhLWI2MzAtNDY2Zi1hM2Q2LTQ5MTgzY2Q1M2UzYy5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMjAzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTIwM1QwODQ4NDRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zMDFmMmEwZGM5OGU1YTRiODQwNTIyNjk5ZDNkZTdjNTRhNjhjOTA2MzIzNDgxMDdjMTMxYWYxYWI2YjU0MjFjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.a2GWgi9a8n7o-1wOxyU-Y3uFIGgEEzHKoAbXSHUEh_4)

Reciprocating engines has the highest number of accidents.

![Alt text](https://private-user-images.githubusercontent.com/185777876/391891879-b01db255-7072-4d10-ac4e-b82ffb6905aa.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzMyMTc0NzMsIm5iZiI6MTczMzIxNzE3MywicGF0aCI6Ii8xODU3Nzc4NzYvMzkxODkxODc5LWIwMWRiMjU1LTcwNzItNGQxMC1hYzRlLWI4MmZmYjY5MDVhYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMjAzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTIwM1QwOTEyNTNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01ZmFhNjU1YjQyZGRiODBiZmE1OTMyYjkwNjMxYjAxMzI2OGNmN2NhNDIwYmVlNGRjYzQwOGUwN2NjYjQyNTM4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.NzWIXY-I_cXxSJ090SXaFaCvq_9KIgESG82xXSDbrlo)

There is a direct Correlation between the VMC weather and the Frequency of accidents

![Alt text](https://private-user-images.githubusercontent.com/185777876/391898565-12bdea95-1345-4a69-8953-82ec1a41a647.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzMyMTgyMTQsIm5iZiI6MTczMzIxNzkxNCwicGF0aCI6Ii8xODU3Nzc4NzYvMzkxODk4NTY1LTEyYmRlYTk1LTEzNDUtNGE2OS04OTUzLTgyZWMxYTQxYTY0Ny5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMjAzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTIwM1QwOTI1MTRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xNTcyMDcyNzU2MDc4YTI1ZjhjNDYxY2U4MDdhYzdlMTc4NzE3OTUxOWNhYzgwNmNmYTk2MWZlMDM0NDE4NTFiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.j8NdMHrxbnRvWgSt6DWNhL9oEXf7K836tGuxpCzwIo8)

Despite the accidents/Incidents 87% of the accidents had no Injuries. 9.3% of the accidintes were however fatal.

###### FINDINGS
+ Accidents are more likely to happen in specific  weather conditions compared to others .i.e VMC
+ The reciprocation engine type perfoms poorly in the VMC weather condition
+ The 13% non fatal and fatal Injuries is very high

###### RECOMENDATIONS

+ Engene type Reciprocating engenes is is not reliable.Relative to the other types of engene its more likely to be invoved in an accidents. Makesup 84% of all the recorded incidents
+ Address Weather-Related Risks:could be caused by :
  - Ineffective weather monitoring systems
  - Pilot trainings and prior experience piloting in adverseweather
+ Study and Trainings: Countries with many minor or non-fatal accidents to be used for targeted pilot training and enhanced preventivemeasures.

###### OTHER ATTACHMENTS

1) Tableau URL is https://public.tableau.com/app/profile/job.cheruyot/viz/Job_Tableau_Aviation_Data_/Dashboard-Data?publish=yes
2) Notebook
3) Notebook pdf
4) Power point PDF
5) Tableau PDF


