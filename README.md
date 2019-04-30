# Project Tesla (Token Economy System Learning Application)

## Overview
Reinforcement is a key to ABA (Applied Behavior Analysis) to reduce the occurrence of disruptive behaviors in order to increase skill acquisition. It is frequently used in natural environments as well by parents, but can be challenging to deliver and even harder to track. One use case is to use a wearable device to communicate with the subject on rewards during common activities. For example, a child is in Karate class, frequent self-stimulatory behavior, such as tightening his belt, staring in the mirror, or winking at the lights, causes him to miss instructions. Through a wearable a parent or therapist could grant tokens, or take away token using a mobile device and wearable. The data could be saved to show progress. The backend token platform could be used broadly and even be linked to rewards. For example, earning 10 minutes of computer time.

## Prototype Architecture

Adopted Azure serverless architecture for building a scalable prototype. A parent or a therpist could use a mobile app or a web browser to access the the application to start a therapy session with the child. All of the therapy session information stored in Azure Cosmos Db and data operations are implemented using Azure Function APIs. A wearable app used by the child can get the push notifications send via the Microsoft App Center push notification feature.

A High level architecture used for the proof of concept is given below.

  <img src="https://github.com/sowsan/project-tesla/blob/master/Autism_Hack.jpg" width="350" alt="accessibility text">


## Repos
All  of the artifacts used for the prototype architectures has been shared via its own repos below.

 - [Mobile App Repo](https://github.com/sowsan/project-tesla-mobile)
 - [Web App Repo](https://github.com/sowsan/project-tesla-web)
 - [Wearable App Repo](https://github.com/sowsan/project-tesla-wear)
 - [API Repo](https://github.com/sowsan/project-tesla-api)





