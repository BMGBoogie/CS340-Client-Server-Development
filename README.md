CS 340 Project Two README Template


About the Project/Project Title
This project was created to help our customer, Grazioso Salvare, identify animals with certain profiles to create search-and-rescue animals. They wanted the capability to work with existing data from animal shelters and apply their categorization and sorting options to aid in identifying the correct candidates for training.

Motivation
Grazioso Salvare needs a way to improve their current recruitment processes in order to optimize their search-and-rescue training program. By creating a system that shows animals within animal shelters in one centralized location, and provides information about them, can save our customer a lot of time. 

Getting Started
In order to get the database running on your local system, please follow the steps below:
1.	Within your database system (we recommend MongoDB), import the Austin Animal Center dataset CSV file using your database’s import tool.
a.	To verify that the file imported correctly, you can run a basic index search to verify that the system is able to read and pull the information stored in the file.
2.	Next, you will need to create an administrator account to ensure the proper privileges to remove limitations on data modification within the file. This file will walk you through how to create an admin account if you have not already done so.
a.	You can verify that the admin account was created by entering the following command if you are using MongoDB: mongo --authenticationDatabase “admin” -u “admin -p
3.	Optionally, if you would like to create an additional user account for the database, that may not hold all of the privileges that the admin account will have, then you can create additional user accounts the same way but can choose which rights the other accounts will have.

Installation
To run the file and system correctly, you will need a database system. We recommend MongoDB as it was used during the creation of the file, and it provides all of the required functionality without compromise.

Usage
Code Example
I wanted to retain as much simplicity as possible while ensuring that I gave the customer every feature that they requested. By simplifying the sort feature using buttons at the top of the database, and selection bubbles on the left to choose the animal you are looking at, it should help alleviate the potential confusion that can come from working within a large database like this.

Tests
There were a lot of features in this code that we needed to ensure were working as requested. The biggest focus for me was the geolocation factor, as the rest of the features were representations of the data within the system and was not as independent as the geolocation system. 

Screenshots
 
 
Contact
Your name: John Mullen
