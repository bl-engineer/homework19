# homework19: Text Editor

## Your Task

As you have progressed through this course, you have put together a number of impressive projects that you can show off to potential employers. This project is no exception; in fact, it features some of the most impressive expressions of the concepts you have learned so far.

Your task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

To build this text editor, you will start with an existing application and implement methods for getting and storing data to an IndexedDB database. You will use a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

You will deploy this full-stack application to Heroku using the [Heroku Deployment Guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide).

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```


## Review

You are required to submit the following for review:

* The URL of the deployed application

* The URL of the GitHub repository, with a unique name and a README describing the project


## Screenshot of Result: Text Editor

<img width="1276" alt="Screen Shot 2022-10-05 at 8 38 55 PM" src="https://user-images.githubusercontent.com/15242022/194188696-c4fee447-5e2e-44f3-8cc1-56bc33ccfd72.png">


<img width="1200" alt="Screen Shot 2022-10-05 at 8 37 50 PM" src="https://user-images.githubusercontent.com/15242022/194188889-52429a5e-3c78-4036-8627-11f14f422458.png">

<img width="1616" alt="Screen Shot 2022-10-05 at 8 47 01 PM" src="https://user-images.githubusercontent.com/15242022/194189189-bd84c03b-e1f1-4b4f-affb-6825b9e28521.png">

<img width="1616" alt="Screen Shot 2022-10-05 at 8 46 34 PM" src="https://user-images.githubusercontent.com/15242022/194189222-0745d300-872c-4e40-84b1-84b26e32e3a6.png">


---
© Done by: Bocar Ly
Assigment: Week 19 Homework 

[Github_URL](https://github.com/bl-engineer/homework19/)

[Heroku_Deployment_URL](https://text-editor-bl.herokuapp.com/)
