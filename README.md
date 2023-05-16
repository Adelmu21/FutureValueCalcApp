# FutureValueCalcApp

https://github-actions-workflow-021.azurewebsites.net/

# TravelExperts
> Website that features a Travel Website including a main page, a bookings page and a My bookings page to view bookings
a login and register feature, in order to access the content of the both the bookings page and the mybookings page.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Screenshots](#screenshots)
* [Live Demo](#live-demo)
* [Setup](#setup)

## General Information
- Travel Website intented to allow users to view and add packages (a user would be the customer)
- Intended to create a user experience to provide a platform that displays a product
- Made as a final project for my class
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Bootstrap 5
- jQuery JS library 3.6
- Microsoft .NET
- C# 
- HTML5
- CSS

## Screenshots

Main Page <hr>
![Main Page screenshot](./img/MainPage.jpg)<br>

Calculation Demo
![Calculation Demo screenshot](./img/CalculationDemo.jpg)<br>

Validation Demo
![Validation Demo screenshot](./img/ValidationDemo.jpg)<br>

## Live Demo

Click <a href="https://github-actions-workflow-021.azurewebsites.net/">here<a> if you would like to try it out for yourself.

## Setup
after downloading all files in the repo (Visual Studio was used to build and run the Web App)
- then start TravelExpertsWorshop2.sln file
- set TravelExpertsData library as Startup project
- go to Project Manager Console and make sure the default project is set to TravelExpertsData
- cope and paste this scaffold in PM console Scaffold-DbContext -Connection "Data Source=localhost\sqlexpress;Initial Catalog=TravelExperts;Integrated Security=True;Encrypt=False" -Provider Microsoft.EntityFrameworkCore.SqlServer -Context TravelExpertsContext -OutputDir "look up where the TravelExpertsData folder is, right click and copy as path to paste here" -DataAnnotations
- now after it says complete make sure to set the TravelExperts project back as start up project
- Run the program and you should be able to navigate trough the page

## Thank you for reading
