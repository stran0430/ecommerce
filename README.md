# E-Commerce Back-End

## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
## Description
The back end for an e-commerce site that uses Express.js API and Sequelize to interact with a MySQL database.

## Table of Contents
- [Deployment URL](#Deployment-URL)
- [Repo URL](#Repo-URL)
- [Features](#Features)
- [Pre-Requisites](#Pre-Requisites)
- [Usage](#Usage)
- [Technologies Used](#Technologies-Used)


### Deployment URL
This is a back-end application. It is not deployed online.

### Repo URL
https://github.com/stran0430/ecommerce

## Features
1. Easy-to-use back-end application.
1. Manages database of online store.

## Pre-Requisites
1. Install `node.js`.
1. Install `MySQL`

## Usage
1. Run: `npm start`.
1. Open Insomnia Core, Postman, or a similar application.
1. Make API requests as demonstrated in the video (linked below).

### Screenshot
<img width="1276" alt="Screen Shot 2023-04-04 at 22 31 31" src="https://user-images.githubusercontent.com/115510413/229966801-4aca8726-78e1-434b-ab43-2587007d99e7.png">
<img width="1270" alt="Screen Shot 2023-04-04 at 22 34 43" src="https://user-images.githubusercontent.com/115510413/229966805-7880fa50-47a0-4a38-ac73-97c7b19c61a3.png">
<img width="1272" alt="Screen Shot 2023-04-04 at 22 34 53" src="https://user-images.githubusercontent.com/115510413/229966807-d632b99a-2e08-4451-9fa6-8aed13471a14.png">


### Video Demo
[Untitled_ Apr 4, 2023 10_33 PM.webm](https://user-images.githubusercontent.com/115510413/229966502-af89432c-6cec-4a4a-a83e-02d52dad2db0.webm)

[Untitled_ Apr 4, 2023 10_27 PM.webm](https://user-images.githubusercontent.com/115510413/229966048-c0290726-a5f8-44a3-8501-65a3d8cfe90c.webm)


## Technologies Used
1. JavaScript
1. [Node.js](https://nodejs.org/en/)
1. [Express.js](https://www.npmjs.com/package/express)
1. [MySQL2](https://www.npmjs.com/package/mysql2)
1. [Sequelize](https://www.npmjs.com/package/sequelize)
1. [Dotenv](https://www.npmjs.com/package/dotenv)
