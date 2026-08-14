---
layout: page
title: Project Ideas
permalink: /ideas/
---

> All senior design projects must meet our [Project Criteria](/criteria). Pay particular attention to the need for your project to have both algorithmic and technical components.
> Here are some ideas to get you started...

# RTX Autonomous Vehicle Competition
GW has participated in an autonomous drone competition since 2023-2024. Each year the competition presents a new contest for students to build one or more drones to overcome challenges. This is an **interdisciplinary project** that will span CS, ECE, and MAE. The CS team will primarily be responsible for developing the software to control the drones. GW will then take the drones to a competition to see how we perform compared to other schools. This is a great chance work on a real hardware/software project and build connections with Raytheon/RTX, a major R&D corporation for the US Government. **We are looking for ~4 students to fill this project!**

# Distraction Free Commuting Productivity/Entertainment
Create an application to make my hour long commute more productive or fun. The application should be designed for someone driving a car so it must be entirely audio based and be designed to limit distractions while still giving the driver something entertaining/useful to do.

# Healthcare Data Analytics Platform
Develop an algorithm for analyzing medical data to predict disease outcomes or suggest personalized treatments. Implement a web-based application that securely processes and visualizes patient data, taking into consideration data privacy and security measures.

# Traffic Optimization System
Design an algorithm to optimize traffic flow in a city based on real-time data from various sources. Develop a software solution that integrates with traffic lights, cameras, and other infrastructure to implement the algorithm and manage traffic patterns.

# Financial Portfolio Management Tool
Create an algorithm that optimizes investment portfolio allocations based on risk tolerance and market trends. Build a web or mobile application that allows users to manage their portfolios, leveraging the algorithmic insights.

# Network Threat Detector
Design a platform capable of performing high speed analysis of network traffic to detect security threats. This could involve designing and deploying ML classification algorithms to specialized hardware like programmable network cards or switches in Prof. Wood's lab.

# Public Speaking Trainer
Design a tool to help people improve their speaking skills. Your system might include automated video and audio analysis of a recorded presentation to score the speaker on their volume, posture, use of filler words, etc. The system would then give feedback to help people improve their slides and presentation delivery.

# AI Memory Bank
Build a tool that helps gather information from a user's daily life and allow it to be queried to act as a second memory. For example, you might gather audio or transcripts from a zoom meeting and then provide the user with a context-aware summary when they meet with the same people at a later time. The system would focus on both gathering the information which is worth persisting and allowing it to be queried against using techniques like Large Language Models.

# Private LLM Box
Large language models and generative AI can provide value to many businesses by helping them understand their own data, but current systems require them to share that data in ways that may violate their security or privacy policies. This project will seek to build a domain-specific LLM processing device that businesses could deploy on their own premise that guarantees all processing is done locally. For example, you could build a health-care specific platform that includes a mix of hardware (such as a mini PC with powerful graphics card in a pretty box) and software for storing patient data and loading it into powerful ML models for analysis by doctors. 

# AI-Powered Rental Platform for College Students
Develop an AI-driven platform that streamlines the process of finding rental properties for college students. The platform allows students to search for rentals based on proximity to their college, budget, and specific preferences. It also assists landlords in finding suitable tenants by matching their properties with students' needs. The project employs machine learning algorithms to recommend optimal listings, incorporating real-time data on rental prices and availability. The platform aims to simplify the housing search process for students and enhance property management for landlords.

# AI-Powered Wearable Health System for College Students
Project Description: Develop an AI-driven health monitoring system that integrates with wearable devices like smartphones and Apple Watches to track college students' sleep, diet, exercise, and other health-related activities. The system analyzes the collected data and provides personalized health recommendations based on the latest scientific research in health and wellness. By connecting the system to evidence-based studies, it offers suggestions that are not only personalized but also grounded in proven health outcomes. The project aims to improve students' well-being and academic performance through scientifically backed health management, offering actionable insights on a weekly or monthly basis.

## Research Projects

# Deep Learning for EEG Analysis:
*Faculty contact for details: Prof Xiaodong Qu*

Explore the application of advanced deep learning techniques, including transformer-based architectures and novel algorithms like Mamba, to the analysis of EEG (Electroencephalogram) brain signal data. This project focuses on critical tasks such as emotion recognition, seizure detection, and sleep stage scoring, aiming to develop models that not only improve accuracy but also enhance interpretability and clinical relevance. The project addresses key challenges in data preprocessing, noise reduction, and the handling of imbalanced datasets, while also considering the ethical implications of using AI in sensitive healthcare applications. Students from Prof. Qu's lab has published more than ten research papers on this topic in the last two years.

# GenAI in Senior Design Course:
*Faculty contact for details: Prof Xiaodong Qu*

Integrate generative AI tools into the one-year-long CS senior design course to enhance both teaching and learning. This project will explore the application of AI-driven project ideation, automated code generation, and real-time feedback mechanisms, with the goal of fostering greater creativity and innovation among students. The project will assess the impact of these AI tools on various aspects of the course, including student engagement, creativity, collaboration, and project outcomes. Specific areas of focus will include how generative AI can assist in brainstorming novel project ideas, streamline the coding process, and provide personalized feedback that adapts to individual student needs.

<!-- # Path-Aware Microservice Security
*Faculty contact for details: Prof Tim Wood*

Design and implement a security framework for microservice applications deployed in Docker containers. The framework should intercept requests traversing microservice components and make authorization decisions or detect anomalies based on the path the requests have taken.

# ML Based Management of Serverless Functions
*Faculty contact for details: Prof Tim Wood*

Sledge is a serverless computing framework being developed at GW for low latency computation. This project will extend Sledge with an ML model to predict the processing time for each request and use this to guide resource management decisions such as scheduling and load balancing. -->

## Mentor Ideas

# Outfit Comparison
An application that allows someone to upload two outfits asking which one is better. The answer gets crowdsourced to other users. The application would be mobile, react native on Expo.

# Voting Understanding
A voting application with the goal of teaching users the difference between plurality voting, condorcet method, ranked pairs, and instant runoff. You'd be able to create a poll with your friends and see the results based on different voting systems.

# Monolithic to Microservice LLM Refactor tooling.
Converting a monolithic codebase to microservices requires a great deal of manual work, and can be a risky process. While there is tooling like Kubernetes to manage microservices, the tooling to help refactor a codebase to get to the point where orchestration tools can be used is not as prevalent. A project that uses LLMs to help analyze a codebase and provide realistic steps to automate the refactor process would save large companies time and money. This idea is fairly broad, and should be scoped appropriately for senior design.


## Project ideas from previous years

# UTA/LA Scheduler
Every year the CS department has to assign ~50 students as undergraduate Learning and Teaching Assistants. This is a complex scheduling process that is currently done manuarlly (by your poor instructor). This project would build an automated system that accepts information about classes and student/faculty preferences to determine the best matching. If you do a good job, this could be adopted by the CS department!

# Encrypted & Sharded Cloud Storage System
Build a system that allows me to provide multiple cloud storage platform credentials and will act as a single “cloud”. When I upload files, they should be encrypted and chunked, with each piece stored in a separate cloud provider. When I download files, these encrypted chunks should be joined together and unencrypted on disk. Provide a UI that allows me view an index of my files & supports uploads/downloads. This solution should take security into account.

# High Performance Remote Procedure Calls

Every time you submit a search request on Google, it is transformed into 100s to 1000s of queries sent to many different servers for processing. These requests are performed using Remote Procedure Calls (RPC), which allow one piece of software to easily invoke functionality in another. This project will design and implement a RPC protocol focused on low latency processing of requests, and will be built to work with the OpenNetVM project created by students in Prof. Tim Wood's lab. You will learn about the design of networking protocols, get practice with writing high performance C code, and learn about shared memory communication.
 
# CS Experimenter's Notebook

Computer Science researchers often need to run experiments to test the performance of different algorithms or pieces of software. This project will design a web-based tool to help researchers design experiments, run tests, gather data, and analyze/visualize results. The primary challenge with this project is designing a system which is flexible to support many different types of experiments -- an OS designer might want to run experiments to evaluate the impact of different schedulers, while a ML researcher may need to evaluate the impact of different neural network parameters on multiple data sets. How can you design a tool that can easily run these diverse workloads and gather the data in a consistent way so that it can be easily analyzed and reproduced?

# BikeBuddy: Safe and Customizable Cycling Routes

Project Description: Develop a mobile application that provides cyclists in Washington, D.C., with safe and optimized biking routes. The app integrates bike lane data, safety statistics, and user feedback to offer customized routes that avoid high-speed roads and dangerous intersections. Real-time updates and user reports enhance route accuracy and safety. The project utilizes advanced algorithms, React Native for mobile development, and AWS for backend infrastructure, aiming to promote cycling as a safer and more reliable mode of transportation.

# Re(search)-Verse: Personalized Graduate School Research Tool

Project Description: Create a platform that centralizes information on professors, universities, and research papers to assist students in finding the best graduate school and mentor. The platform uses a combination of relational and graph databases to store and visualize relationships between researchers, their publications, and collaborating professors. Users can input preferences such as location, research area, and university ranking, and the platform’s ranking algorithm will generate personalized recommendations. APIs like Semantic Scholar and OpenAI’s models are used to gather and categorize research data.

# WalletWiz: AI-Powered Personal Finance and Credit Card Optimization

Project Description: Develop a web application that helps users manage personal finances and optimize credit card usage. The platform provides two key features: personalized spending insights based on user-defined goals and tailored credit card recommendations. WalletWiz uses AI algorithms to analyze spending patterns, offer actionable advice, and suggest credit card offers that match the user's financial habits. The application integrates technologies like OpenAI, LangChain, and the Plaid API for secure data management and intelligent recommendations.


# ChatGPTravel: AI-Powered Optimized Travel Itineraries

Project Description: Develop a web service that generates personalized travel itineraries based on user preferences such as cost, rating, and travel time. The platform leverages generative AI, like ChatGPT, to suggest activities and destinations, which are then verified and enriched using APIs like Yelp and Foursquare. The itinerary is optimized using combinatorial algorithms to create the most efficient, cost-effective, or highly-rated experience. The project aims to simplify travel planning by providing tailored, optimized itineraries that enhance the travel experience.

# Eco-Sorting: AI-Driven Waste Management System

Project Description: Develop an AI-powered system that uses Convolutional Neural Networks (CNNs) to accurately classify and sort waste images into recyclable categories. The project focuses on enhancing recycling efficiency through a user-friendly platform that allows easy image uploads and provides clear recycling instructions. The system leverages pre-trained models and integrates tools like TensorFlow and Django to ensure high accuracy and scalability across various recycling scenarios.

# Style Genius: AI-Powered Clothing Shopping Platform

Project Description: Develop a comprehensive shopping website that uses web scraping and AI algorithms to personalize clothing recommendations based on user preferences and body dimensions. The platform integrates NLP to analyze product reviews and enhances the shopping experience by offering tailored suggestions from multiple retailers. The project involves full-stack development, including backend (Flask), frontend (HTML/CSS/JavaScript), and hosting on AWS, with a focus on creating an intuitive user interface and efficient data processing.

# College Football Prediction Platform

Project Description: Develop a user-friendly platform that predicts the outcomes of college football games using machine learning algorithms such as Logistic Regression, KNN, and Random Forest. The platform provides fans with accurate win predictions, detailed team information, and live game schedules. It combines real-time data processing with engaging content to enhance the user experience. The project focuses on building a full-stack application using technologies like Flask, AWS, and Python, with a strong emphasis on delivering accurate predictions and an intuitive interface.

# Mixed Reality UI for First Responders (AR/VR)

Design and implement holograms for incident command perspective and heads-up displays (HUD) for first responders using VR headset with eye tracking feature and video passthrough AR capabilities. The project will require the use of AR/VR equipment (headsets or Glass), provided by the department. It expands on some of the solutions provided by the NIST Chariot Challenge by expanding the UI design using eye tracking capable headsets, video passthrough etc.
