---
permalink: /projects/
title: "Projects"
author_profile: true
---

Most of the listed Github repositories have a detailed explanation of the project as a readme along with the source code

## Local - Mini - GPT:
An internet free locally deployable GPT with a suite of text and data analysis/extraction tools. A RAG solution is implemented with the help of a vector database.  
The main intention was to serve academicians and students to aid in their research by referencing personal documents in a much efficient manner. It includes text summarization, Content retrieval, custom data loaders with CSV analysis report, Q & A based chat interface with embedded local documents and daily news retrival and summarization. 
This was my capstone project for my 4th Year CSE UG degree.
- [Github Repo](https://github.com/abhishekmani12/your-GPT) 

## Visual Attendance Tracker:
A multi model deep learning system which tracks daily attendance through facial recognition with a live camera feed.  
It uses facial vector embeddings of each face and uses a SVM/KNN algorithm to discern faces, it also has a provision for instant face training (~1s) by taking 5 photos automatically in various angles. It updates records and provides a simple interface to interact with it. Deployment test on edge devices was successful.  
This was developed for my 3rd year CSE UG Degree Capstone Project.
- [Github Repo](https://github.com/abhishekmani12/Visual_Attendance_Tracking) 

## Exercise Posture Correction System:
A custom finetuned Key-point RCNN along with several other finetuned CNN models were used to create a system which classifies the type of exercise being performed and informs the user of incorrect posture by comparing the predefined safe relative leg/arm/shoulder angle with the relative angle computed by the keypoints stream from a webcam feed.  
This also includes a simple GPT based chatbot answers user specific fitness related queries by storing their body metrics.  
This was created as part of an Academic Internship Program at the National University of Singapore.
- [Github Repo](https://github.com/abhishekmani12/Pose_Detection_System) 

## Certificate based SSH Login:
Created a utility executable tool which enables Certificate Based SSH login from a Client to multiple listed new servers at an instant with on demand user creations as well.  
Certificate Signing, Key Pair exchange process are all automated. As a result this tool saves around 30 minutes which is required for the connection setup between a single client-server pair, when done manually. This was created for Linux to Linux as well as Windows to Linux connections. 
- Closed Source

## SNOMED CT Code Generation:
Built a Spring Boot application which wraps OpenAI's ChatGPT and Google's Bard (now Gemini) APIs to generate custom user specified SNOMED CT codes as part of a plugin.  
Extensive prompt engineering was done to get the required outputs from both the models. Regex was heavily used to clean and format the outputs so that they adhere to a certain template structure. 
- Closed Source

## Study of Mask Detection Systems:
Various Architectures of CNN Models, One Shot Detectors were trained and tested on different custom datasets to create an efficient and deployable solution to classify if a person is wearing a mask or not.  
This project was developed with the intention of deploying it to a mask dispensing robot that could provide masks immediately to people who were not wearing masks. This was created for the Department of CSE at my university.
- [Github Repo](https://github.com/abhishekmani12/Mask_Detector)

## Wikipedia Content Retriever:
Given a text corpus, the script extracts the most important keywords and tries to retrieve content from wikipedia for each keyword. If the exact keywords are not present in wikipedia's search result then the next closest keyword is searched for and the content is retrieved.  
This was created as I wanted a straightforward way of extracting paragraph content easily for my Local-Mini-GPT Project, rather than relying on a complex library.
- [Github Repo](https://github.com/abhishekmani12/Wiki-Content-Retriever) 

## Ageing Detector:
A simple Deep Learning Classifier which identifies different types of skin defects which are often associated with ageing. Close to 2000 images were manually collected for each type of defect, image transformations and augmentations  were performed to make the system robust.
- [Github Repo](https://github.com/abhishekmani12/Signs-of-Ageing) 


## Web Scrapper and Sentiment Analyzer:
Scrapes textual data from articles via xpath, cleans, processes data and performs sentiment analysis automatically, implemented custom stop words pertaining to various domain terminologies. This script was tested on 150+ articles.
- [Github Repo](https://github.com/abhishekmani12/Scrapping-and-Sentiment-Analysis) 

