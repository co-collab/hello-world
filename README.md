# Project Caleb
You need to familiarize yourself and learn a few modern, high-demand 
fundamentals. These fundamentals include:
* Version Control - learn one
* Languages - Back-end/Server-side - learn ONE
* Frameworks - Back-end/server-side - learn ONE based on the back-end/server-side language you plan to learn
* Languages - Front-end/client-side - learn BOTH (they're easy)
* Frameworks - Front-end/client-side - learn ONE (always JavaScript based)
* Databases - learn BOTH (they're not easy, but they're necessary)
* Integrated Development Enivornments - learn ONE

## Core Technologies
If you learn these layers/technologies, you will be able to apply for 
"Full Stack" positions. If you fail to learn one or more of these "layers", 
you will not be able to apply for a "Full Stack" position and your employment 
options will be severely limited. Generally, "Full Stack" refers to a web 
application stack. More about this at the end of the document.

Tedious as the following list may be, read it carefully and weigh the pros 
and cons. Do not make any decisions until you have read this entire document. 


### Version Control
* Git (free)
  - this is the one & only tool in this category that you *must* learn to use
  - relevant to all modern software development
  - programming language agnostic
  - [Git Basics](https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/)
  - [Git Branching & Workflow](https://nvie.com/posts/a-successful-git-branching-model/)
	

### Back-end Languages (high demand)
Pick ONE and learn as much of it as possible
* NodeJS - I highly recommend focusing on this language right now 
  - Basically JavaScript with a lot of additional functionality
  - Platform independent (will run on Linux, Windows, and Mac)
  - Well supported; lots of libraries
  - fastest way to start and develop a web application
  - [NodeJS 101](https://www.tutorialspoint.com/nodejs/index.htm)
 
* Python - I hate Python and I think the ecosystem is a wreck but its a high-demand language
  - well supported; lots of libraries
  - Platform independent (will run on Linux, Windows, and Mac)
  - easier for n00bs to develop web applications than Java
  - [Python 101](https://www.tutorialspoint.com/python/index.htm)

* Java - (I can help with this if necessary)
  - steep learning curve; very cumbersome for a n00b to develop a web application
  - a long term career investment language to learn
  - well supported; lots of libraries
  - Platform independent (will run on Linux, Windows, and Mac) 
  - [Java 101](https://www.tutorialspoint.com/java/index.htm)

### Back-end Frameworks
Choose ONE based on the back-end language you have chosen.

* Express.js 
  - most modern NodeJS-based web applications are based on this framework 
  - [Express.js 101](https://www.tutorialspoint.com/nodejs/nodejs_express_framework.htm)

* Django
  - Python-based
  - oldest & most mature Model-View-Controller framework for Python
  - [Django 101](https://www.tutorialspoint.com/django/index.htm)

* Flask  
  - Python-based 
  - newer, stripped down version of Django;
  - [Flask 101](https://www.tutorialspoint.com/flask/index.htm)

* Spring Boot
  - Java-based 
  - stripped down & streamlined version of plain on "Spring"
  - [Spring Boot 101](https://www.tutorialspoint.com/spring_boot/spring_boot_introduction.htm)

### Front-end Languages (high demand) - familiarize and learn ALL
* JavaScript
  - [JavaScript 101](https://www.tutorialspoint.com/javascript/index.htm)

* HTML - this is what *all* web pages are written in
  - [HTML 101](https://www.tutorialspoint.com/html/index.htm)	
	
### Front-end Frameworks (high demand) - pick ONE and learn as much of it as possible 
* React 
  - developed and maintained by Facebook (its not going away soon)
  - [React 101](https://www.tutorialspoint.com/reactjs/index.htm)
 
* Angular 
  - developed and maintained by Google
  - [Angular 101](https://www.tutorialspoint.com/angularjs/index.htm)


### Databases (high demand)
Familiarize yourself with and learn BOTH
* PostgreSQL
  - relational & SQL-based (as opposed to MongoDB, a "No-SQL" database)
  - traditional database paradigm 
  - both read & write access are very fast
  - [Postgres 101](https://www.tutorialspoint.com/postgresql/index.htm)

* MongoDB
  - a No-SQL database (as opposed to PostgreSQL, a relational database)
  - more intuitive to programmers 
  - extremely fast read-access at the cost of a slightly slower write-access
  - [MongoDB 101](https://www.tutorialspoint.com/mongodb/index.htm)
	
### Integrated Development Environments 
Choose based on the back-end language you plan to learn
* Microsoft VS Code (free)
  - perfect for developing NodeJS & Python 
  - lots of plugins for version control, deployment, etc
  - support for syntax highlighting 
  - this is probably the most commonly used IDE (Integrated Development Environment)

* Eclipse (free)
  - perfect for developing Java applications
  - industry standard 
  - well supported and lots of plugins & extensions

## Next Steps
Okay, now that you have made it through the menu of options, here's the 
approach I recommend you take to learn thse things, in order. I'm assuming 
you're taking my recommendation and choosing to learn NodeJS, so here are 
some links to use while stepping through this process.

1. Learn to use Git. You don't need to learn any new languages or even have a
software project to use Git. You can use Git to manage plain text documents if 
you so desire. I cannot stress how critical it is to know how to use Git. 
    - You have either a GitHub or BitBucket account (I recommend GitHub)
    - You have created one or more repositories on GitHub or BitBucket
    - You can "clone" a repository from GitHub or BitBucket to your local machine
    - You can "commit" changes to your locally cloned repository 
    - You can "push" changes from your locally cloned repository to GitHub or
      BitBucket

2. Decide which back-end language you want to learn because that is going to
determine many other decisions you will make. 

3. Decide which Integrated Development Environment you want to use. If you
chose Java, learn Eclipse. If you chose NodeJS or Python,
learn Microsoft VSCode 
    - a. install Git plugins for whichever IDE you choose 
    - b. Create a repository on GitHub or Bitbucket (I suggest a title like "first-nodejs-project" or something to that effect) 
    - c. use the Git plugins in your IDE to clone the project to your local machine 
    - d. use your IDE to develop a simple "Hello, world" application 
    - e. use the Git plugins in your IDE to commit the changes to your local repository 
    - f. use the Git plugins in your IDE to push the changes from your local repository to GitHub or BitBucket 

4. Use your IDE to integrate basic database connectivity into your "Hello, world" application 
    - a. create a table in PostgreSQL with the following attributes 
        - automatically generated index called "ID" 
        - a text field called "greeting" (the type could be VARCHAR, CHAR(64), or TEXT) 
    - b. insert a record into the table 
    - c. use source code to select the record from the table 
    - d. print the result to the screen 
    - e. repeat steps 3.e and 3.f 

5. Create a basic webserver application  
    - a. print the same result from step 4d to a browser 
    - b. repeat steps 3.e and 3.f 

7. Spend time experimenting 


