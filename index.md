# HLTV Enjoyability Prediction Chrome Extension
A Bournemouth University Final Year Project Artefact

## Introduction
As part of my final year project I undertook a research project with the aim of improving esports spectator experience, specifically for professional CS:GO spectators. 
This aim was achieved through development of a Google Chrome Extension and supporting API which use Machine Learning to predict the enjoyability of upcoming games on [HLTV.org](https://www.hltv.org/) match pages. The following GitHub repositories contain the developed Chrome extension and API in their submitted states.

The Chrome extension was developed using JavaScrpt. The API was developed using Python (Flask) and deployed to Google Cloud Platform.
The API relies on a Machine Learning algorithm developed from primary research using Jupyter Notebook and the scikit-learn library.

## GitHub Links:
- [Chrome Extension](https://github.com/OfficiallyLukeHemmings/hltvPredictorExtension)
- [API (Google App Engine)](https://github.com/OfficiallyLukeHemmings/hltv_predictor_api)

## Dissertation Abstract
With an abundance in professional CS:GO games played each week, even when just
considering the top-tier competition, along with a variety of reasons why spectators may
not enjoy a given game, knowing which games to prioritise watching and whether or not
you are likely to enjoy them is nearly impossible. As such, this project aimed to improve
competitive CS:GO spectator experience through development of a machine
learning-based system for predicting enjoyability for upcoming games of the esports
title.

Predicting esports enjoyment appears to be a new field of research which this project
explores. Given the lack of existing solutions, CRISP-DM and ‘Rapid Application
Development’ were successfully employed to create a Google Chrome extension and
supporting cloud deployed machine learning REST API. Multiple machine learning
techniques were employed to select and refine the machine learning algorithm
implemented, with the final model reaching 75.1% accuracy based on anticipated
enjoyability ratings gathered through a preliminary questionnaire. The developed
system was user tested over a period of ten days, during which feedback confirmed
high levels of enjoyability prediction accuracy in a working environment.

The full developmental process, including the initial background study, is documented
and discussed throughout this project. All project objectives established were met and
the project achieved its aim, with 86.6% of respondents reporting the developed system
benefited their decision-making process when inspecting upcoming or ongoing
professional CS:GO games.
