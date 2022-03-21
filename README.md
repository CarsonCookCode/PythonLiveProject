# Python Live Project - Code Summary

## Introduction
I worked in an Agile/Scrum environment to build an application demonstrating proficiency with Python in Django. I created a program that allowed the user to take a personality test from the Big 5 theory of personality using questions from the International Personality Item Pool and to save their results to a database. I gave the app useful CRUD functionality and other features utilizing APIs and Web Scraping. We used Azure DevOps to manage our repositories and user stories. I developed a productive workflow after familiarizing myself with the tools at my disposal. Over the two week sprint I had many opportunities to learn what it means to work as part of a team on a single project.

Here are some of the highlights from the project: 

## CRUD Functionality
I first worked on setting up the most basic features essential for any program that enables the user to interact with a database.
After basic CRUD functionality was completed I created the test element to the creation process of a profile.

views:
![Screenshot (64)](https://user-images.githubusercontent.com/73494842/159364163-d7f3bf52-e771-48e8-bbd7-e75335a27f53.png)

template:
![template1](https://user-images.githubusercontent.com/73494842/159364800-7ea9e7aa-1174-49e5-9655-1f35ff456d17.png)

interface:
![Screenshot (60)](https://user-images.githubusercontent.com/73494842/159361039-957f84bd-85c6-4b98-bb76-5f4e7fdda391.png)

## Create and Read
I created a function in the view and a simple interface for the user to create a profile. After data was being added to the database I need the user to be able to view the contents. I added another function to the view as well as another template for viewing the data.

template:
![template2](https://user-images.githubusercontent.com/73494842/159364855-86c983cc-40c9-4177-8f21-f16db9a46c8f.png)

![Screenshot (56)](https://user-images.githubusercontent.com/73494842/159361391-e3c8a74d-742d-4d64-ad84-3ea3b3f43b0c.png)


## Update and Delete
I implemented updating and deleting profiles and their information.

![Screenshot (65)](https://user-images.githubusercontent.com/73494842/159365192-85189543-8a3a-4c79-b3ba-301948bec046.png)

![Screenshot (57)](https://user-images.githubusercontent.com/73494842/159361462-cc48cb6b-d1f9-466e-b15e-c4ef5a4e857d.png)

## Web Scraping
I utilized web scraping to provide useful information about the personality traits and about the theory behind them by gathering information from Wikipedia. This information is gathered at runtime and will change as the Wikipedia page updates.

![Screenshot (54)](https://user-images.githubusercontent.com/73494842/159361583-30111da5-17d9-49a4-93f4-fa054a67dc45.png)

I also wanted the user to be able to quickly generate realistic profiles. I found a page containing many names for males and females to use for this purpose. When the user generates a profile it downloads the page and selects a random name to be user for the creation of the profile. For the sake of accuracy, I calculated the mean and the standard deviation for each of the traits in the general population in order to generate values on the normal distribution for each trait respectively.

![Sss](https://user-images.githubusercontent.com/73494842/159362173-436fd153-79a6-48e1-9928-fd1ee8d46d3c.png)

## API
I wanted the user to derive useful information from their personality results. I implemented a simple algorithm that determines which job is most fitting for people with a given personality makeup. The results determined the terms that would be set as parameters for the query to the API that accesses data from the employment website Indeed. The user provides a location and then they are redirected to a table of relevant jobs that may interest them as well as a link to the corresponding page from Indeed.

![Screenshot (58)](https://user-images.githubusercontent.com/73494842/159362260-4a1d2ade-e2fa-4440-80d9-50c9d4f4134e.png)

![Screenshot (59)](https://user-images.githubusercontent.com/73494842/159362275-68319794-bb7d-4855-9971-dcdfa2bd71c3.png)

## Additional Functionality
I had created a straightforward program of creating user profiles, editing information, and displaying data, but wanted to make the results the user recieved to be more meaningful. I found a publicly availavle csv file containing over 300,000 profiles with data using the same theory of personality I derived from to create my test. I enable the user to download a sample from this data and to view it. 

![Screenshot (55)](https://user-images.githubusercontent.com/73494842/159362351-b1561d5e-1ac5-401c-a1e4-3763bd2a8101.png)

I used the data to provide the user with a percentile score in order to give them a perspective on how their personality compares to the world. I also added a quick delete button to allow for quick removal of profiles.

![Screenshot (61)](https://user-images.githubusercontent.com/73494842/159362321-50e540eb-3481-445d-85cd-07e769bbe7d7.png)

## Front End Development
After completing all essential functionality for my application I increased user-friendliness and aesthetic experience. I made some simple design choices and optimizations. I wanted the data to be presented beautifully to the user and to provide a seemless bug-free service. These changes are included in the screenshots above.

## Skills Acquired
I gained a great deal of perspective from this project. I got a lot of practice with Python, Django, CRUD, APIs and Webscraping. I have become more comfortable with existing in a place where I do not know everything. This project gave me the opportunity to practice how to approach a complex problem and to decide when I need to spend time researching a concept or to experiment with what I know. I also learned that for a project to come together and to provide a useful service it is important to have a vision of the end product and to spend time planning to enable you to develop most efficiently and effectively.
