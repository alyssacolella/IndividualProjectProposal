# Individual Project Proposal

The open source project I would like to contribute to is called ‘Book Project’. It is a web app that allows users to create an account, add books to read or already read, rate books, view statistics on reading habits, etc. The design is a simple one with navigation to book lists, goals, statistics, and settings. The project implements separate bookshelves, such as ‘to read’, ‘finished’, ‘reading’, etc to filter reading lists for a user. It tracks reading behavior and opinions to produce statistics like average rating, most and least liked book, and longest book read.

![]("https://github.com/alyssacolella/IndividualProjectProposal/blob/main/Screen%20Shot%202021-02-17%20at%2011.37.13%20AM.png")

The project can be found here: https://github.com/Project-Books/book-project

## Project Relevance
Adding a feature or two and solving some of the listed issues would relate to the topics of object oriented design, debugging, access to a database, JUnit testing, and even graphic user interface. I think these educational goals are important because we would be given the chance to experience working on a project from back-end to front-end, without the overwhelming amount of work it would be to start something like this from scratch.

## Contribution
I think it would be interesting to add a feature to start a reading session, in which Java’s timer class is implemented to set a timer to read for a certain time, and maybe even disable a user from leaving the web app until time is up. A user could enter what page they start and end on, and the total pages read can automatically be added to the statistics and goal tracker. If manageable, a feature could be implemented to suggest books based on previously read books. Furthermore, more statistics could be added to this project, like average rating by genre and active reading times.

If none of these features are acceptable for this assignment, there are also a few issues described on Github that I think could be solved in our timeline. They include a frontend bug with the login page, need for error messages on log in, failing tests, refactoring a few methods to be static, etc.



## Building and Running the Project
**To build:**
- Clone project from Github
- Change configuration to use JDK 11
- Install node (version 10.0 or later)
- Install Docker Desktop
- Import project as a Maven project
- On command line, run 
```bash
  (sudo) docker -compose up -d mysql phpmyadmin
```
- On command line, run
```bash
  ./mvnw spring-boot:run (unix) or mvnw.cmd spring-boot:run (windows)
```


**To run:**
- Go to http://localhost:8000
- Log in with the credentials: **username** - user, **password** - password

