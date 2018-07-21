# Assignment 2 - Late Joiners

## Part 1 - Design

### Database Design and Storage

The project will be using a NoSQL databased called MongoDB. This means stepping back from normalisation in favour of fast reads and easy data manipulation.

The following is the proposed data structure for the for our MVFs:

_Note - Underscores indicate a link to another piece of data in the same collection or from another collection_

#### Users
 - _id (GUID)
 - name (string)
 - password-hash (string)
 - email (string)
 - permissions (array of strings)
 - _tournaments (array of GUIDs)
 - updated by (ISO date string)
 - created by (GUID)
 - update on (ISO date string)
 - created on (GUID)

#### Tournaments
 - _id (GUID)
 - name (string)
 - sport (string)
 - teams (array)
    - _id (GUID)
    - name (string)
    - venues (array)
        - name
        - default
 - games (array)
    - _id 
    - _home team (GUID)
    - _away team (GUID)
    - venue (string)
    - score
        - home team score (number)
        - away team score (number)
        - crowd provided scores (array)
            - home team score (number)
            - away team score (number)
 - results (array)
    - competition leaderboard (array)
        - _team (GUID)
        - score (number)
    - picker leaderboard (array)
        - _user (GUID)
        - score (number)
 - updated by (GUID)
 - created by (GUID)
 - update on (ISO date)
 - created on (ISO date)

!!!INSERT mongo-database-design.jpg image here!!!

#### User Picks
_id (GUID)
_user (GUID)
_tournament (GUID)
picks (array)
    _game (GUID)
    home team score (number)
    away team score (number)

### EVF Design

#### Automatic Backups

Automatic backups with will happen on a daily basis by our database hosting provider MLab (see resources section for more info).

MLab makes it easy to automate backups of MongoDB database instances.

## Part 2 - Plan

#### Resources and Tools

##### Git
######  A version control system

* Ensure easy rollback of code changes
* Merging of changes
    * Contributors can work concurrently without getting in each others way
* Forking and branching allows for non-destructive experimentation
* Easy tracking of contributions

###### Alternatives

* SVN
* Mecurial
* TFS

##### Node
###### A JavaScript engine for the server

* Will allow us to write both JavaScript on the front-end and the server
* Code reuse on client and server results in reduced language switching
* A plethora of open source packages easily installable via NPM
* Cross platform
    * Team members use Windows, Linux and Mac

###### Alternatives
* PHP
* Java
* Python


##### Angular
###### A front-end single page application framework

* Allows for rapid creation of SPA applications
* Small learning curve
* Comes with a CLI tool to handle generation of boilerplate code and building of the application
* Simple local-server allows for quick feedback on changes

###### Alternatives

##### Mongo
###### NoSQL database

* Easily stores JSON objects as documents coming from the frontend
* Cross-platform
* Handful of applications to *peek-in* to the database and inspect the contents

###### Alternatives

* NeDB
* PostGres

##### Express
###### A REST API routing framework for node

* Makes it easy to create a backend API in Node
* Non-opinionated
* Easy to use

#### Bootstrap
##### A front-end, CSS framework for easy-to-start UI customisation

* Easy-to-use grid layout
* Facilitates responsive design out-of-the-box
* Actively developed and updated

###### Alternatives
* Semantic
* Material CSS

#### Netlify
##### An hosting platform for front-end applications

* Extremely easy to get up and running
* Automatic deployments

###### Alternatives
* Azure

#### Heroku
##### An hosting platform for and backend applications

* Easy to get up and running with backend node application
* Automatic deployments

###### Alternatives
* Azure

#### Circle CI
##### Online continuous integration and delivery service

* Live builds
* Automatic builds
* Automatic deployments to heroku

###### Alternatives
* Jenkins
* Visual Studio Team Services

#### MLab
##### MongoDB database provider online
* Free tier for dev and QA environments
* Automatic backups
* [mlab.com](https://mlab.com/)

#### Collaborative Workspaces
* [Trello](https://trello.com/b/hO83Xzoj/latejoiners)
* [github](https://github.com/LateJoiners)
* [Slack](https://rmitlatejoiners.slack.com)
* [Google Docs](https://docs.google.com)
* Google Hangouts

#### Software

##### Code Editors
* VS Code
* Atom

