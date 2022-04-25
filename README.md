# CST-452_ManzanitaProject_Portfolio
Project portfolio describing my CST-452 capstone project in detail.


<br>
<!-- Introduction to the project. What problem did I aim to solve and why? -->

## 📝 Introduction

Hey there 👋

I’m Jack Setrak, a senior software developer at GCU. The project is aimed toward residential communities looking to manage all their users, day to day activities and events, maintenance, and administration services in one site. Intended to be simplistic for ease of use but capable to scaled based on what the community needs. 

Demonstration Video: <br>
[![FinalCapstonePresentation](https://img.youtube.com/vi/fSnTTAuYv7M/0.jpg)](https://www.youtube.com/watch?v=fSnTTAuYv7M)

<br>
<!-- What high level functional and non-functional requirements  that were supported in this project -->

## Requirements Supported
High-level functional:
* Simplified navigation bar
* All in one page letting users access multiple pages from one spot using visual aids (Link imbedded images)
* Role based privileges limiting functionality access to certain roles
* Admin users are the only ones allowed to register a new account.

Non-functional:
* Responsive Pages
* Spring Security Authentication 
* JSON Web Tokens (JWT) Security

<br>
<!-- What technologies were used? -->

## 💻 Technologies
Project is created with:
* Front-end (Link found at the bottom)
  - Visual Studio Code 1.61.2
  - Vue 3 version: 12.3
  - Node.js 14.18.1
  - Axios 0.24.0
* Back-end = (Link found at the bottom)
  - Spring Suite 4.12.0
  - Spring 2.5.5
  - Java 11
* Database = MongoDB Atlas
* MongoDB Compass 1.29.4
* JavaScript
* Java
* HTML/CSS
* Bootstrap 4
* Hosting
  - Heroku
* Postman
* Diagram.net

<br>
<p float="left">
  <img src="https://devland.at/assets/images/vue3-first-look/vuelogo.png" width="100" Height="100" />
  <img src="https://pbs.twimg.com/profile_images/1235868806079057921/fTL08u_H_400x400.png" width="100" Height="100" /> 
  <img src="https://cdn.techjockey.com/web/assets/images/techjockey/products/5717_Mongodb-Atlas.jpg" width="100" Height="100"/>
</p>

The project is partially hosted on Heroku. Hosted back-end and attempted to get front-end up as well but could not. Had to run locally and call the hosted APIs. Further attempts will be made. Otherwise, if problem continues, other hosting platforms such as Azure or AWS will be used as an alternative.

<br>
<!-- What technologies were chosen and why. What best practices were supported and implemented. Is it cloud-deployed? -->

## New Technologies Learned
What I had to learn and why:
* Not being familiar with the languages used was a problem at first. Slowed down development in the early stages
as I had to spend time learning the tool and libraries.
* Vue was a completely new framework for me to use. JavaScript in general was not something I used in the past. A few JS snippets were used but did not dive into the technology up to this point. This was chosen because upon further research, VUE came out to be a solid framework built upon the work of React and Angular taking the best of both and fixing the problems in between. Front-end development was simple and straight  forward with plenty of up-to-date documentation but its active community. 
* Spring Boot was not all new. Being familiar with Java and the basics of Spring, veering into Spring Boot did not take much effort. Tons of documentation and resources exist making troubleshooting any problems less troublesome than usual. 

<br>
<!-- What challenges were faced along the  -->

## Challenges
Risks and challenges this project faced:
* Not being familiar with the languages used was a problem at first. Slowed down development in the early stages
as I had to spend time learning the tool and libraries.
* Initially, the project was to be developed in Laravel and Angular, but it was diverted to Spring Boot, and Vue. Required some project reconstruction/replanning. 


<br>
<!-- What issues does this project have? -->

## ⚠️ Issues ⚠️
Issues found within the project:
* Edit profile: User is unable to edit their own profile. Information sent overwrites and deletes current info.
* Cannot  host front-end on Heroku due to file issues resulting in failed deployments 

<br>
<br>
<!-- What were some diagrams used to plan this project? -->


## Diagrams
Physical Solution:<br>
![image](https://user-images.githubusercontent.com/36085137/165023826-1c3fd903-5ae2-439d-97de-9f34a6623781.png)
> Physical solution involves everything that's required to run this project. The two separate applications will communicate with each other over API calls using AXIOS. Both the Vue.js and the Spring Boot applications will be hosted to the cloud by Heroku. Both projects don’t require intensive components so minimal specifications are easy to meet. Heroku cloud's free container provides around 550-1000 dyno usage hours per month, 512MB of RAM and Storage. The Spring boot application in the back end will be connected to MongoDB Atlas which is a Database as a service (DBaaS), or a database on its own cloud service. Limitations of the free M0 tier Atlas are: Shared RAM & vCPU, 512MB of Storage, 500 max collections, and 100 max connections. No specific port number to be used yet. 

Logical Solution:<br>
![image](https://user-images.githubusercontent.com/36085137/165024245-28c7fb8b-2027-4dc6-8686-2cda93da0bee.png)
> In this 3-layer design, the logical solution depicts all layers of the web application. The user will be redirected to a web application that contains and manages all the user interfaces. Vue.js is used to develop the entire frontend design. AXIOS API calls are used to communicate with the business layer in the second spring boot application, which subsequently renders the appropriate pages. The request is then passed up the ladder via business service, which ensures that everything is handled correctly. The request will eventually make its way up to the DAO, which will communicate with the MongoDB database, modifying data as appropriate, before returning to the front end. 

Flowchart/Process Flow:<br>
![image](https://user-images.githubusercontent.com/36085137/165024376-228fa41d-6076-4c24-9ddd-a403de10f70f.png)

DevOps:<br>
![image](https://user-images.githubusercontent.com/36085137/165024566-ea500484-d518-4ef3-a97a-c0850419c487.png)
> MongoDB Atlas has its own monitoring and metrics tracking. Can check the number of connections made, size of database overtime, network traffic, etc. 
<br>
Once the front-end is hosted, UptimeRobot will be to monitor the site. It can monitor a site every 5 minutes and notifies you when it’s down. You can get notifications in various ways, and it is a simple tool that anyone can use. 

<br>

## 📌 Pinned Repositories
<!-- Where can the other repositories be found? -->

<br>
Front-end<br>
<kbd>
  <a href="https://github.com/jackfire78/manzanita">
    <img align="center" style="margin:0.5rem" src="/Images/Front-end.JPG" />
  </a>
</kbd>

<br>
Back-end<br>
<kbd>
  <a href="https://github.com/jackfire78/manzanitaResidentualCommunities">
    <img align="center" style="margin:0.5rem" border=:"2" src="/Images/Back-end.JPG" />
  </a>
</kbd>

<br>
<br>

> ### More About me?
> [Check out my linked in.](https://www.linkedin.com/in/jacksetrak/)
