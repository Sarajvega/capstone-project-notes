# Proposal

# Birdsong.app - Sara Vega

## Learning Goals

- Learn how to utilize ML models
  - time permitting, create and train a model. 
- Learn how to create a full stack application
  - React front end
  - Flask backend
  - Mobile component
- Master building a Flask API

## Problem Statement

There are over 1,000 species of birds in the United States, which makes identifying every bird you hear a difficult task! This application will provide the seasoned birder or budding orinthology enthusiastic a way to identify a bird based off of a sound clip. They will be able to edit the sound clip and will receive a percentage guess along with information on the identified bird. 

## Target Audience

This app is targetted toward bird enthusiasts. 

## Basic Pieces
- Get Model to consume dataset and give prediction
- Create API to call model with information.
- Create basic application version that consumes a sound file and spits out file size.
- Get application to pass sound file to API to model and return a prediction.

## Technologies

[Kaggle Competition winning model](https://github.com/ryanwongsa/kaggle-birdsong-recognition)
Front-end: React.js
Back-end: Flask (Python)
Database: Firebase Cloud Firestore

## MVP Feature Set

1. User can use desktop to upload a soundclip under a certain size.
   1. Return will be a percentage along with species name. 
2. User can upload a soundclip to the desktop app and edit which portion they would like analyzed. 
    1. Return will be a percentage along with species name. 
3. User can upload a soundclip to the desktop app and edit which portion they would like analyzed. 
   1. Return will be a percentage along with information about the species.
4. User can upload a soundclip to the desktop app or to mobile application.
   1. Return will be a percentage along with information about the species.
5. User can upload a soundclip to the desktop app or to mobile application. User can create a loging and save what species they observed and where.
   1. Return will be a percentage along with information about the species and an option to save information.