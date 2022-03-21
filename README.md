# Python Live Project - Code Summary

## Introduction
I worked in an Agile/Scrum environment to build an application demonstrating proficiency with Python in Django. I created a program that allowed the user to take a personality test and save their results to a database. I gave the app useful CRUD functionality and other features utilizing APIs and Web Scraping. We used Azure DevOps to manage our repositories and user stories. I developed a productive workflow after familiarizing myself with the tools at my disposal. Over the two week sprint I had many opportunities to learn what it means to work as part of a team on a single project.

Here are some of the highlights from the project: 

## CRUD Functionality
I first worked on setting up the most basic features essential for any program that enables the user to interact with a database.

## Create
I created a function in the view and a simple interface for the user to create a profile.

## Read
After data was being added to the database I need the user to be able to view the contents. I added another function to the view as well as another template for viewing the data.
[Story 3: Display all items from database]
[Story 4: Details page]

## Update and Delete
I implemented updating and delete profiles and their information.
[Story 5: Edit and Delete Functions]

## Web Scraping
I utilized web scraping to provide useful information about the personality traits and about the theory behind them by gathering information from Wikipedia. This information is gathered at runtime and will change as the Wikipedia page updates.

I also wanted the user to be able to quickly generate realistic profiles. I found a page containing many names for males and females to use for this purpose. When the user generates a profile it downloads the page and selects a random name to be user for the creation of the profile.
[Stories 6 & 7: Beautiful Soup]
[Story 9: Save API or scraped results]

## API
I wanted the user to derive useful information from their personality results. I implemented a simple algorithm that determines which job is most fitting for people with a given personality makeup. The results determined the terms that would be set as parameters for the query to the API that accesses data from the employment website Indeed. The user provides a location and then they are redirected to a table of relevant jobs that may interest them as well as a link to the corresponding page from Indeed.
[Stories 6 & 7: API]
[Story 9: Save API or scraped results]

## Front End Development
After completing all essential functionality for my application I increased user-friendliness and aesthetic experience. I made some simple design choices and optimizations. I wanted the data to be presented beautifully to the user and to provide a seemless bug-free service.
[Story 8: Front End Improvements]
[Any other Front End work you’ve done that you would like to showcase]

## Skills Acquired
I gained a great deal of perspective from this project. I got a lot of practice with Python, Django, CRUD, APIs and Webscraping. I have become more comfortable with existing in a place where I do not know everything. This project gave me the opportunity to practice how to approach a complex problem and to decide when I need to spend time research a concept or to experiment with what I know. I also learned that for a project to come together and to provide a useful service it is important to have a vision of the end product and to spend time planning to enable you to develop most efficiently and effectively.
