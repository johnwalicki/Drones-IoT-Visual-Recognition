# Drones-IoT-Visual-Recognition
Save Lives with Drones / IoT / Visual Recognition - Call for Code Hands on Lab

## Introduction

## Learning objectives

After completing this tutorial you will be able to:

* Create a Visual Recognition model in Watson Studio running in IBM Cloud
* Capture images from a drone and zip them into a class
* Train a model to identify objects in the images
* Score and count the identified objects

## Prerequisites
This tutorial can be completed using an IBM Cloud Lite account.

* Create an [IBM Cloud account](https://console.bluemix.net/registration)
* Log into [IBM Cloud](https://console.bluemix.net/login)
* Log into [Watson Studio](https://dataplatform.ibm.com)

## Estimated time

You can complete this task in no more than 10 minutes.

# Hands on Lab

## Step 1 - Learn about Drones

* Contixo
* Tello - Control a [Tello Drone using Node-RED](https://github.com/johnwalicki/Node-RED-Tello-Control)
* Hobbyist drones
* Commercial drones

## Step 2 - Capturing Images
Use your drone to capture images of interesting objects that you want to train a visual recognition model to autonomously identify.

In this lab, we have created three zip files to identify neighborhoods affected by the devastating 2018 West Coast wildfires. These images are our training set. *Source attribution: USA Today [article](https://www.usatoday.com/in-depth/news/nation-now/2018/08/02/drone-aerials-california-wildfire-devastation/889885002/), various internet sources*
* Aerial drone images of burned homes - [BurnedHomes.zip](/classes/BurnedHomes.zip)
* Aerial drone images of intact homes - [AerialHomes.zip](/classes/AerialHomes.zip)
* Aerial drone images of forests, roads, rivers to be used for the negative class. [NotHomes.zip](/classes/NotHomes.zip)

## Step 3 - Watson Studio
In this section, we will create a Watson Studio Project and Watson Visual Recognition model to identify images in several classes.

* Create a Project - lots of screenshots
* Create a Visual Recognition model - lots of screenshots
* Upload three zips to Cloud Storage - lots of screenshots
- Create a class *Burned Home* - drag a zip - lots of screenshots
- Create another class *Aerial Home* - drag a zip - screenshots
- Create a negative class *Not Homes* - drag a zip - screenshots
- Train your model - wait a few minutes

## Step 4 - Test your model
In this section you will use sample images to confirm your model.

## Step 5 - Implement this model in your Application
Code snippets:
