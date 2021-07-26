# Proposal

# houseplant.app - Sara Vega

## Learning Goals

- Learn how to utilize Lobe to create ML models
- Learn how to utilize ML models
- Learn how to access computer components (webcam)
- Learn how to create a full stack application
  - React front end
    - Pogressive Web App for mobile app
  - Flask backend
- Create Unit and Integration tests for app
  
## Problem Statement

House plants are en vogue! Have you ever purchased an unmarked pot of foliage to add to your table while in a shopping frenzy? This app is perfect for that situation. With houseplant.app, budding horticulturalists will not only learn to correctly identify their houseplants, but get information on care and disease management. 

## Trello
[Trello Board](https://trello.com/invite/b/9SSWH38B/10e463f84357ecaf54c0ccab72f9547e/capstone)

## WireFrame


## Target Audience

This app is targetted toward plant enthusiasts. 

## Technologies

Mobile: Progressive Web App

Front-end: React.js

Back-end: Flask (Python)

Database: Firebase Cloud Firestore

## MVP Feature Set
1. User can access webapp via browser and upload a photo to the website.
   1. Return is used to call to a separate API to retrieve Plant Care data.
2. User can access webapp via browser and use webcam to capture a photo of plant.
   1. Return is used to call to a separate API to retrieve Plant Care data.
3. User can access webapp via browser and show plant to webcamera, which will live update with identification and information.
   1. User can 'pause' webcam feed to read information.
   2. Return is used to call to a separate API to retrieve Plant Care data.
   3. They can open tabs for care, disease management and pest management.
4. User can access webapp via browser OR mobile app and view plant through camera/webcam, which will live update with identification and information.
   1. User can 'pause' webcam feed to read information.
   2. Return is used to call to a separate API to retrieve Plant Care data.
   3. They can open tabs for care, disease management and pest management.

Plant Care Sheet?
- Use a plant API 
- Have a loading screen that takes data from an external Plant API and brings in that data
- If 3 - 4 extra days you could build your own
- Otherwise call another API thru the front end. 

Options:
https://docs.oracle.com/cd/E41106_01/doc.621/e48908/cor_plant_api.htm#g84008
https://data.nal.usda.gov/dataset/usda-plants-database-api-r/resource/f981f826-583c-48bd-a29c-3c0ee7a34fc6


**Microservices Model**

Prediction service - Keep as a local API using Lobe Connect?
Time: 3 days
- Flask w/Tensor Flow
- IF ONLY LOCAL - Lobe Connect

Caresheet service - Custom API 
Time: 3 days
- Flask
- Create an ERD Diagram/Wireframe

Front-end service - calls both prediction and caresheet. 
Time: 
- Refresh new page w/caresheet info
- REALLY HASH OUT HOW THIS WILL LOOK

Database - Firebase
Time: 

Deployment - Azure
Time: 

**If low on time:**
- Back-up/Faster:
  - Keep everything local

https://www.lobe.ai/docs/export/export

