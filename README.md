# Project Udagram Image Filtering Microservice
This is a sample application for Udacity's Cloud Developer course. 

**ucdp-p2-image-filter**

This project is connected to the _Cloud Developer Nanodegree Program_ course by **Udacity**.
Udagram Image Filtering Microservice is a RestAPI server . 
It offers a service to filter an image with image_url as query parameter, which is accessabele public . 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Environment ###
This program requires **node.js**  and **npm** program envirenment 

You'll need to create a new node server. 
Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

server running http://localhost:8082
press CTRL+C to stop server

## Testing of Endpoints of Local Server###
1. Root Endpoint: http://localhost:8082

2. Endpoint with image_url
http://localhost:8082/filteredimage?image_url=https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg

## Testing of Endpoints of deployed Application to AWS ###
1. Root Endpoint:  http://ucdp-p2-image-filter-dev.eu-central-1.elasticbeanstalk.com/

2. Endpoint with image_url
http://ucdp-p2-image-filter-dev.eu-central-1.elasticbeanstalk.com/filteredimage?image_url=https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg

## AWS- Elastic BeansTalk Deployment Screenshot ###
S. Folder:
deployment_screenshots/ScreenShot.png

