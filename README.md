# FounderNLightning_Postman
This repo containing Postman Public API automation

# Task 2

A well-documented API like https://developer.twitter.com/en/docs or https://api.slack.com or any known to you with public documentation and pick a random API endpoint.
Write a set of Postman API automated tests that you would write for that endpoint.
OR
Take the contact form POST API ( given for the UI automated tests assignment ) and write all API automated tests that you would write for that endpoint. 

# Solution:

1. Selected a public APIs to showcase the type of tests covered to test the API in Postman. 
https://api.publicapis.org/entries 

# Execution: Import the json in Postman Local and run the API.

Used GET API for Founder and Lightning Contact US page.
{{ContactUS_Static-URL}}3991028/b15d4232-7672-429d-81fd-a00020bddf95/json?hs_static_app=forms-embed&hs_static_app_version=1.2802&X-HubSpot-Static-App-Info=forms-embed-1.2802&hutk=49ece67ca13d1730e1634f0b7a6c8be6

{{ContactUS_Static-URL}} : https://forms.hsforms.com/embed/v3/form/

Utilized Global environment for URL reusability in multiple end points.

# Scenarios:
1. Load Contact Us page with valid parameter.<br/>
   Verified response, its performance and validation in 7 Verification Points.

2. Load Contact Us page with blank parameter.<br/>
   Verified response, its performance and validation in 7 Verification Points.

POST API still in progress as in my local collection it shows 400 bad request.







