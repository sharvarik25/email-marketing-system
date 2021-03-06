# MovieLens Email Marketing System
Created a web application which would send emails to the customers recommending top 5 movies based on Train Matchbox Recommender of Microsoft Azure. Analysed the performace of the model and email statistics using a third-party domain @MailGun and visualized on Microsoft Power BI.

User can select a particular customer so that the recommender engine can generate top 5 recommended movies and email them.

## Workflow
•	Collected dataset from MovieLens website

•	Ingested the data in Microsoft SQL Server

•	Loaded the dataset from Microsoft SQL Server to Microsoft Azure SQL

•	Generated the recommendation engine using Train Matchbox Recommender in ML Learning Studio

•	Designed a web application using Flask with Email Sending functionality

•	Created a webservice of the recommender engine and leveraged it in the web app


## Project Proposal
https://codelabs-preview.appspot.com/?file_id=1Tad2rzpMAGpc3Rr_Yl540uoLu_66FlSGplhfWdmfbLM#0

## Claat Report
https://codelabs-preview.appspot.com/?file_id=1fNYAKwiUYsbJZLbcDYZZTkW_Ha2kke-416QQn454Pds#0

## Note

•	Replace the api key for Azure Machine Learning Model

•	Replace the json file for accessing the BigQuery Database

•	Please follow instructions in claat document to use our application (Point 8)

## Installation

•	pip install Flask

•	pip install pandas

•	pip install numpy

•	pip install requests

•	pip install json

•	pip install google.cloud

•	pip install google.oauth2

•	pip install warnings

•	pip install matplotlib

•	pip install pyodbc


## Recommendation Engine Model

https://gallery.azure.ai/Experiment/Recommendation-Model
 
## Dashboards

https://app.powerbi.com/view?r=eyJrIjoiYjlhNTc1ZDAtYzgxOS00NWEwLTgyNTUtMzFlNDMxOGI5ZThkIiwidCI6IjZhYmZjNzNmLWRhNjQtNDEzNy05ZjlmLTE1ZmFhZTU2ZjY4NSIsImMiOjN9


