Employee Request Manager

A Microsoft Power Apps Canvas application designed to simplify employee request submission and management.

Overview

Employee Request Manager is a practice project developed to explore Microsoft Power Apps and low-code application development. The application provides a simple interface where users can submit employee requests and review their submitted requests.

The project demonstrates the implementation of a multi-screen Canvas app, form-based data entry, navigation between screens, and data management using Microsoft Excel as a data source.
<img width="1920" height="743" alt="image" src="https://github.com/user-attachments/assets/9f4aa2b8-6d98-4f34-8898-c59345df252c" />
<img width="1177" height="410" alt="image" src="https://github.com/user-attachments/assets/a05b99d0-dc81-437e-b17f-f5079e133678" />
<img width="674" height="694" alt="image" src="https://github.com/user-attachments/assets/8302eb3c-a9ad-4b8a-adcc-64b67920c901" />


Features

Home Screen: Provides access to the main application functions.

Submit Requests: Allows users to create new requests by entering the request type, description, start date, and end date.

My Requests: Displays submitted requests in a gallery.

Request Status: Supports displaying the status of each request.

Screen Navigation: Enables users to navigate between the home screen, request submission form, and request overview.

Excel Integration: Uses an Excel table as the application's data source.

Screens

The application consists of three main screens:

Screen

Description

scrHome

Main landing screen with navigation options.

scrNewReq

Form for submitting a new employee request.

scrMyReq

Gallery displaying submitted requests and their details.

Technologies Used

Microsoft Power Apps — Canvas Apps

Microsoft Excel — Data source

Power Platform CLI — Source code export

Git — Version control

GitHub — Source code hosting

Project Structure

Employee-Request-Manager/
├── Employee Request Manager.msapp
└── EmployeeRequestManager_src/

.msapp — The Power Apps Canvas application package.

EmployeeRequestManager_src/ — The exported source files of the application.

Getting Started

To explore the application:

Download or clone this repository.

Open Microsoft Power Apps.

Import the .msapp file into an appropriate Power Apps environment, or use the exported source files with the relevant Power Platform CLI workflow.

Configure the Excel data source and reconnect it if necessary.

Run the application and test the available screens.

Note: You may need access to a Microsoft Power Apps environment and the appropriate permissions to import and run the application. The Excel data source may also need to be configured for your environment.

Learning Objectives

This project was developed to gain practical experience with:

Building Canvas applications with multiple screens.

Creating and configuring forms and galleries.

Managing application navigation.

Connecting Power Apps to an external data source.

Using Git and GitHub for version control and project presentation.

Future Improvements

Potential improvements include:

Adding employee identification and filtering requests by the current user.

Implementing request approval and rejection workflows.

Adding input validation and improved error handling.

Improving the user interface and responsive layout.

Integrating Microsoft Power Automate for automated notifications and approval processes.

Exploring Dataverse as an alternative data source.

Author

Stratis Zachariadis

GitHub: @StratisZx

This project was created for learning and portfolio purposes as part of my development journey in the Microsoft Power Platform ecosystem.
