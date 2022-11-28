# Citibike

## Project overview
CitiBike is a bike rental service located in and around New York. It's customer data is open source which makes it great for exploring.

This project uses Citibikes data for the year 2018, visualizes it and builds a predictiv model for the customer types.
Additionally it uses the google maps API to compare traveling times for bike, public transport and cars for 200 randomly selected samples.

## Set up
The project consists soley of jupyter notebooks.
A key is needed to use the google maps part and can be acquired at https://developers.google.com/maps/ .
It is absolutly vital to start with the Engineering notebook, as it produces the necessary data for the other notebooks.

## Notebooks
### Engineering_Visualisation
Has most of the engineering steps needed for the data, as well as the data aquisition itself.
Produces a couple of pickle files that can be used by the other notebooks.
Does also contain a couple of visualisations, helpful to get a first grip of the datas insights.

### ML
Compares the performance of several ML algorithms and uses the best one to train a model to predict the customer types of the company.

### Google
Uses the google maps API to compare 200 randomly selected bike rides with car traffic and available public transport.

### NYPD
Explores the traffic data of NY in regards to bike related accidents.
