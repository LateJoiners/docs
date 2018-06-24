# Assignment 1 - Late Joiners

## Part 1 - *What*

### Project Name:
#### Late Joiners Sports Tipping App

### Project Description:

A Web application that will allow users to sign up and place their predictions of the results of a variety of sporting tournaments, and track their success against other users.

Users will be able to select from a variety of upcoming matches, with the option not just to choose the outcome, but predict scores/results as well.

When the next round of a tournament begins, Users will receive a notification that the time has come for them to make their picks for the next round.

At the end of the tournament, the user (or users) with the best record can claim bragging rights for their prescience!

The application will be available to users across a variety of devices, from desktop browsers, to tablets and mobile devices.

### The Team

#### Luke Warren
##### s3409172@student.rmit.edu.au

##### Background

I am a software engineer with 5 years experience. I specialise mainly in web based technologies but have also worked on mobile apps as well as purely backend services.

The start of my career saw me work mainly in the CMS smace. Augmenting .NET based CMSs like DNN and and Umbraco for brochure and ecommerce websites.

At the moment, I am co-lead on a large team working on an online quotation application for a large insurance provider in South Africa.

I also talk and conferences and user groups - at the moment about functional programming in JavaScript and run a number of training initiatives at work.

##### Strong Points

I am a natural leader and am happy to step up when decisions need to be made. I also have strong technical ability - especially in the web development space.

I pick up technologies quickly and am able to communicate complicated concepts quickly and simply to both technical and none technical clients/colleagues.

##### Challenges

My challenges for the project mainly revolve around organising and communicating with a dispersed team with significant time zone differences.

I feel it will stretch my communication skills.

##### Contributes to The Team

* Technical Lead
* DevOps

#### Matt Greig
##### s3439728@student.rmit.edu.au
I've spent the best part of the last two decades in the film and television industry, beginning with on-set production work, and then for the past 14 years in Visual Effects (VFX) and post-production. In that time I have worked as an artist and a lead, and for the past 6 years have been an on-set and departmental supervisor. VFX, by it's nature, is a constantly evolving field, progressing technologically with each new production and as such I've found myself relying on self-taught skills in Python and C++ to develop new tools and plugins to existing platforms, as well as automating the production pipeline to squeeze every last bit of efficiency.

The film industry has certainly provided plentiful experience in working to set-in-stone schedules, and spending most of my career in post-production, at the compressed end of a delivery schedule, I've certainly learned a lot about *getting the job done*. Deadlines aren't something I find intimidating. I'm certainly interested in this project; as a keen user of the web, and dynamic platforms, I'm looking forward to the opportunity to experience the development of one first-hand.

To my mind, the challenge for this assignment will be translating many of the experiences I've had working Pythonically with database API's and front-end UI's using QT, to JavaScript and the Node, Express and (especially) Angular frameworks.

With experience in team-management in my professional career, and to mitigate our geographic and timezone separation with our lead, Luke, I'm happy to help guide the project forward. I especially look forward to getting elbows-deep in the codebase once we commence.

#### Blair Fraser (s3641830@student.rmit.edu.au)
I have some prior experience with Java, Perl, PHP, Python (the latter of which I’m using occasionally in my current non-programming job to automate workloads). I enjoy programming in general, with a current preference towards backend development using dynamically typed languages (although I have not at this stage had much call to involve myself in frontend coding).

As well as the above languages, I have some experience working with RDBMSes, but am looking forward to getting experience with technologies I have not previously been exposed to (version control systems (specifically git)), NoSQL and javascript frontend and backend frameworks (the MEAN stack).

Challenges during the project will be getting up to speed on these new (to me) technologies to the point that I am able to contribute as effectively as I want to.

Tasks that I would envisage myself working on are could be anything applicable to my level of skill at the time utilizing technologies belonging to the MEAN stack (frontend or backend-oriented tasks), leveraging my existing python knowledge to write a script to harvest data from APIs, transform it to the required format and write it to the mongoDB instance (though something like this wouldn’t be required at the extended functionality stage), helping generate and manage documentation.


#### Tyrone Cook
##### s3731802@student.rmit.edu.au
My background in IT is very brief, only having recently completed the foundation subjects for this degree. I have a basic understanding of C and Java programming languages. Although I have very little experience especially in developing web applications, I'm eager to diversify my skillset by learning the new languages, programs and methods that I will require to complete my tasks in this project.

The challenges for me in this project will be mainly focused around familiarizing myself with a subject I have no prior experience with (web applications). Being a relatively more inexperienced member of this group when it comes to programming, the challenge will be for me to keep up with the rest of the group and making a meaningful contribution to this project.

The types of tasks that that I will be contributing to this project will be limited by my abilities, being so new to this area. As stated previously I'll be a member of this group that is very foreign to the work required in this project so my tasks will be to learn as much as I can from the more experienced members and contribute to this project where required.


#### Shae Tatlock
##### s3655740@student.rmit.edu.au

##### Background
After I finished high school I spent 3 months doing a computer assembly and repair course, this is where my interests in programming began. I followed up that course with a year in Accounting during this time I spent part of my free time programming, this sparked my love for it.

During this time and before my current course I taught myself to be literate with Java, Python, Javascript, as well as HTML5 and CSS3. I am also very interested in the server side and can see that being in my future.

I am yet to work in an IT role, although every job I have worked I have helped out in that space.

##### Strong Points

I am a team player, I have spent my life in teams. I have the rare ability to ask if I am not sure about something, communication is key and one of my strengths.

I also learn quickly, if something needs to be picked up by one of us I will be able to put my hand up and take the responsibility.

##### Challenges
I have not worked with a group in programming before, I will have to learn how my teammates program and how they work for me to accomplish the goals we have set.

##### Contributes
* Design
* front end programming.

### Demonstrable Outcomes

#### Features

1. Our system should be able to store information about user accounts, and allow users to create new accounts or delete their currently existing account.

   Once implemented this can be tested by attempting to create a number of new accounts, and manually inspecting the database contents after that has been done, then deleting an account and manually inspecting database contents to ensure they match expectations.

2. Our system should be capable of storing information on various soccer tournaments in a mongoDB instance.

   Once implemented, we can test this by attempting to populate the database with static data and subsequently manually inspecting database contents to ensure they are what they should be.

3. Our system should be able to display information on overall tournaments as well as individual matches to the user.

   Once implemented, we can test this by manually checking the database to see what tournaments should be displayed to the user, and then using the system to verify that that does occur. Same process can be followed to perform a spot check on an individual match to ensure the system is showing the user the information it should be.

4. Our system should allow the user to nominate their picks for the currently chosen match (whether simply picking who they think will win or the final score), with this data then being saved in the database.

   Once implemented, we can test this by manually inspecting the database and ensuring that the picks data we have entered via the website has in fact been saved to the database as it should have been.

5. Our system should display to users the actual results for games that have concluded where that user had a pick, as well as data about their overall picking record.

   Manual inspection of the database can be used to ensure that data shown on the results page is correct, both in terms of the game result and the user's pick/whether or not the user's pick was correct/that user's overall picking record to this point

At each stage, a more technical testing process could be followed - i.e. selenium (or something similar) could be used to automate the process of extensively testing objective #3 (i.e. to ensure that ALL tournaments in the database are displayed, and that ALL information for those tournaments is viewable, and the same for individual games, as opposed to manual spot checks of individual tournaments/games)

#### Extended features

1. Our system should source tournament and game data in real-time from APIs for tournaments where an API is available.

   This can be tested by entering static data into the database that differs from that currently being reported by an API, and using the website to see if it displays that static data or if it has retrieved data using the API and displayed that instead.
2. The system should have the ability to 'crowd-source' result information. i.e. Users can enter the score for a game and once a threshold of submitted results have been submitted, the results for the game will be updated and players scored on their picks

   Validation of this functionality could come from a separate testing script which logs the current status of submitted results vis a vis whether the threshold has been reached or not (having interacted directly with the database to retrieve that information) as well as retrieving a particular page from our site and parsing it to ensure that the results are shown (and pick-scoring has occurred) if the threshold has been reached, and that neither results nor pick-scoring is shown otherwise.

   Alternatively (and probably more likely), this functionality could be built into the application itself, wrapped in if clauses that only trigger if a debug flag/variable is set.

3. Our system should have a suitable schedule and process for automatic backups of the database. This can be integrated as part of the Heroku platform we plan to deploy on.


### Project Motivation

- We felt it was a good opportunity to get exposure to a stack we wanted experience in.
- Touches a variety of important and current technologies involved in web development: front-end, Styling frameworks, Javascript, back-end, databases, Angular
- Provides a potentially handy portfolio item post-degree
- Was pertinent given the popularity of sporting results in modern culture
- A variety of existing sites in this field, from which inspiration (both positive and negative) can be drawn

### Project Justification

#### Justified Workload
*develop project schedule*

#### Beyond Current Capabilities
* Using Public APIs
  * practical experience with authentication processes
  * parsing JSON data from different sources
* Angular
  * experience with controllers and two-way data binding
* Using Node and Express as a backend API technology
* Using a NoSQL/non-relational database for data storage
* Managing and coordinating a distributed team across the different time zones
* Getting hands on experience with DevOps and Continuous Integration

#### Project Risks
##### Risks - Effect on Project Outcome
1. API goes offline/changes output format: After implementing the extended feature for real-time data integration utilizing an API/a number of APIs, it is possible that the API may go offline, or that the way it structures output data could change.

   We could attempt to limit this issue by designing our system to be capable of sourcing data for one tournament from a number of different APIs, to retain realtime functionality even when one API is unavailable. Otherwise the last retrieved realtime data would be stored in the database and accessed instead, thus limiting the problem (though not solving it completely). In a real-world solution we would also want a notification to be sent to an administrator when this issue is encountered.

2. Scope/Feature creep: It is conceivable that we might be tempted at some stage to add functionality beyond that we are originally planning on. If we end up attempting to add significant additional functionality that could divert effort away from fulfilling the originally planned features/extended features.

   We can minimize this issue by discussing any new ideas as we have them to determine whether implementing such ideas could cause this sort of problem, and if so whether we really want to work on it or not.

3. Key man dependencies: With certain individuals more experienced than others, we could see silos of responsibility. One person might end up being the only one able to solve certain tasks, putting pressure on the particular person and on project delivery.

	   It is important that all team members have, at the very least, a passing familiarity with the stack employed. Sprint code reviews will also provide an opportunity for less-experienced team members to learn from both successes and failures. It is important that all team members feel that they can contribute, even in the abstract, even if they feel unable to contribute directly to the codebase.

##### Risks - Team Dynamics
1. Time difference of team members: Having team members in significantly different timezones can make realtime collaboration hard.

   We can face this issue by ensuring that we fully leverage non realtime collaborative opportunities, and make the most of what time we are able to schedule that suits all team members.

2. Varied skill level of team members: As we have some team members who are much more experienced than others, it is not inconceivable that we may end up with the bulk of the technical work falling to them, with other team members feeling incapable of contributing in a meaningful way to a project using technologies they do not feel they fully understand.

   The best way to tackle this potential issue would be to both ensure that the less-experienced team members are contributing time regularly to the task of getting themselves up to speed on the chosen technologies, and that the more experienced team members take care to limit use of the most complex features provided by the technologies utilized.

3. Poor team member commitment has the potential to derail the project, putting far too much pressure on the more committed individuals of the team. This also shrinks the about of internal team feedback on both the end product and quality of code.

   All team members must have access to the codebase in the team repository. They should also have github integrations enabled with their Slack account in order to receive notification when new commits are merged and pushed. This will provide continuous impetus for contributions.


### Part 2 - *HOW*

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


#### Collaborative Workspaces
- [Trello](https://trello.com/b/hO83Xzoj/latejoiners)
- [github](https://github.com/LateJoiners)
- [Slack](https://rmitlatejoiners.slack.com)
- [Google Docs](https://docs.google.com)
- Google Hangouts


#### Communications Expectations
Slack
- chat application
- all group members are a part of the **Slack team**
- multiple channels created within the workspace to provide themes to conversations and group threads according to topics.
- used daily for team members to converse, organise meetings, discuss assignment matters
- can launch additional integrated team applications (hangouts, github) to provide common launching place and place for teammates to join, or see notifications (ie. github pulls etc.)
- retains a history of the communications undertaken
- each team member should have Slack accessibility on their potable device with **notifications enabled**
- Direct messages or channel broadcasts should be responded to within a maximum of 8 hours before additional protocols kick in

Google Hangouts/Docs
- part of the google apps suite available to all RMIT students
- hangouts allows for group video/audio conferencing; including screensharing to allow for easy viewing of code demonstrations etc.
- shared documents allows for notes, minutes of meetings to be made available amongst team members

Version Control and Documentation
- All these applications track and define the contributions on individual team members. This keeps a record of the frequency and quality of contributions which will allow for easier review of which team members contributed *what* and *how much*.

Notifications
- push notifications, or integrated notifications (as per Slack) minimise the ignorance of notification of communications quite significantly. It is considered that any team member who does not respond to communications does so intentionally.
- intentionally ignoring communications will leave team members without a voice in the development of the application, and as alluded to in the note above, without a record of contribution

Emails
- to be used in the event of unsuccessful communications with a team member.
- emails will be sent in event of failure to respond to Slack messages(s)
- expected response time to emails is no more than 24 hours

Response Protocols
- Wait for response
- Send notification of MIA status to team for additional team members to ping
- Notify Sarah
- Seek guidance from Sarah and Rusel


#### Decision Making
- Decisions are based on a Majority-rule principle, where each members has a vote, and each vote has equal weighting
- Decisions must be made in a public (for the team) forum ie. Slack
- All team members have the right to question a decision, but both for *and* against decisions must be backed with empirical evidence to avoid decisions being made purely on taste
- Team members have a right to have their opinions heard in open communication channels.


### Part 3 - *WHEN*

##### Week 3:
 - Luke
 - Matt
   - [Complete skeleton of A1 as Markdown doc and push to repo](https://trello.com/c/zLrbHVaX)
	 - [Work on A1](https://trello.com/c/NyfkPtWJ)
 - Blair
   - [Get up to speed on git commandline basics](https://trello.com/c/ZCnaGG8U)
   - [Complete markdown tutorial](https://trello.com/c/Nl8Wuy7k)
 - Tyrone
 - Shae
 - Everyone
   - [Attend team meetings](https://trello.com/c/OFcKaBRi)
   - Ask for help and assist others on slack as required
   - [Commence work on A1](https://trello.com/c/NyfkPtWJ)

##### Week 4:
 - Luke
 - Matt
   - [Angular CLI; download locally and familiarise with platform](https://trello.com/c/UtqNinJp)
	 - [Complete work on A1](https://trello.com/c/wZsXDKRw)
 - Blair
   - [Start working on official angular tutorial](https://trello.com/c/VBvodFEy)
   - [Start reading up on mongodb](https://trello.com/c/TELPP1kc)
 - Tyrone
 - Shae
 - Everyone
    - [Attend mentor meetings](https://trello.com/c/mflqUv3Z)
    - [Attend team meetings](https://trello.com/c/n0tX0yuz)
    - Ask for help and assist others on slack as required
    - [Continue work on A1](https://trello.com/c/DoRR0T8H)

##### Week 5:
- Luke
- Matt
  - [Angular CLI; adapt existing knowledge to web paradigm](https://trello.com/c/mcKUmMWh)
	- [Angular CLI; controllers and routing, two-way data binding](https://trello.com/c/mcKUmMWh)
	- [Gather reference material from existing sites](https://trello.com/c/IQTfktQm)
	- [Commence work on A2](https://trello.com/c/v4crUofR)
- Blair
  - [Install git gui application(s) and practise basic operations, and merging](https://trello.com/c/8StRyM9K)
  - [Practise merging using commandline git tools](https://trello.com/c/SpEFaXSM)
  - [Complete work on official angular tutorial](https://trello.com/c/wRwx59ap)
  - [Find mongoDB tutorial and start working on it](https://trello.com/c/zevU1ayZ)
  - [Determine if some knowledge is required of any other frameworks (i.e. bootstrap) and if so formulate plan to attain it](https://trello.com/c/ZmpI8BiM)
- Tyrone
- Shae
- Everyone
  - Attend mentor meetings
  - Attend team meetings
  - Ask for help and assist others on slack as required
  - Contribute to A2

##### Week 6:
- Luke
- Matt
  - [mongoDB; familarise with DB and mongoose integration APIs](https://trello.com/c/XkazyeO9)
	- [A2 initial prototyping](https://trello.com/c/8IExsoHR)
	- [Investigate API resources](https://trello.com/c/sE7T0qWs)
- Blair
  - [Complete mongoDB tutorial](https://trello.com/c/Fd15PYlj)
  - [Find and complete express tutorial](https://trello.com/c/hQ4LdysR)
  - [Find and start working on nodejs tutorial](https://trello.com/c/wZ0KdEzV)
  - [Find and start working on mean whole-stack tutorial](https://trello.com/c/4LjyC7UG)
  - [Expand angular knowledge by practising with small personal project](https://trello.com/c/WQ50eJhg)
- Tyrone
- Shae
- Everyone
  - [Attend mentor meetings](https://trello.com/c/almyY9fs)
  - [Attend team meetings](https://trello.com/c/v9JO6rU8)
  - Ask for help and assist others on slack as required
  - Contribute to A2

##### Week 7:
- Luke
- Matt
  - [A2 Prototyping continued](https://trello.com/c/uYFiC4PN)
	- [Bootstrap customisation testing](https://trello.com/c/8Nv1ypBL)
	- [Prototype models](https://trello.com/c/KFtLsDAq)
- Blair
  - [Expand mongoDB and express knowledge by working on small personal projects](https://trello.com/c/hbAgJXfq)
  - [Complete nodejs tutorial](https://trello.com/c/0ilcDCYL)
  - [Complete whole-stack tutorial](https://trello.com/c/zPqQt8o2)
  - [Complete small personal project utilizing the whole mean stack](https://trello.com/c/QnALAryM)
- Tyrone
- Shae
- Everyone
  - [Attend mentor meetings](https://trello.com/c/HqnmBPOP)
  - [Attend team meetings](https://trello.com/c/TrvxvxBO)
  - Ask for help and assist others on slack as required
  - Contribute to A2

##### Week 8:
- Luke
- Matt
  - [Complete collation and submission of A2](https://trello.com/c/mpRa02Oe)
	- [Responsive design testing with bootstrap](https://trello.com/c/OdUYQdQG)
	- [Prototype Component Templates](https://trello.com/c/J8g34RzN)

- Blair
- Tyrone
- Shae
- Everyone
  - [Attend mentor meetings](https://trello.com/c/YspwXIpZ)
  - [Attend team meetings](https://trello.com/c/j7RVoRqX)
  - Ask for help and assist others on slack as required
  - Contribute to A2

##### Week 9:
- Luke
- Matt
  - [Integrate Static Data for testing](https://trello.com/c/2fKunXlC)
- Blair
- Tyrone
- Shae
- Everyone
  - [Attend mentor meetings](https://trello.com/c/4i0G28QB)
  - [Attend team meetings](https://trello.com/c/qI56jS2b)
  - Ask for help and assist others on slack as required

##### Week 10:
- Luke
- Matt
  - [Commence User Testing](https://trello.com/c/EHpkm8ku)
- Blair
- Tyrone
- Shae
- Everyone
  - [Attend mentor meetings](https://trello.com/c/zFQ5vYRf)
  - [Attend team meetings](https://trello.com/c/Hu83jXih)
  - Ask for help and assist others on slack as required

##### Week 11:
- Luke
- Matt
  - [Final bug-list](https://trello.com/c/31zwUYlO)
- Blair
- Tyrone
- Shae
- Everyone
  - [Attend mentor meetings](https://trello.com/c/RQYXKaMy)
  - [Attend team meetings](https://trello.com/c/B8HgbfnZ)
  - Ask for help and assist others on slack as required

##### Week 12:
- Luke
- Matt
  - [Final Testing](https://trello.com/c/U3JsEpDL)
  - [Submit A3](https://trello.com/c/iMvQNgmN)
- Blair
- Tyrone
- Shae
- Everyone
  - [Attend mentor meetings](https://trello.com/c/1MAZpAlO)
  - [Attend team meetings](https://trello.com/c/KQm3WGR2)
  - Ask for help and assist others on slack as required


#### User stories

 - As a user I should be able to register on the site
 - As a registered user I should be able to login to the site with my details
 - As a user I should be able to logout
 - As a user I should not be able to see data I am unauthorised to see
 - As a user I should be able to view all the tournaments I can enter
 - As a user I should be able enter a tournament
 - As a user I should be able to make my picks for the tournament
 - As a user I should be notified when I need to make picks
 - As a user I should be able to see my score for the week
 - As a user I should be able to view where I stand on the leaderboard
 - As a user I should be able to edit my profile information
 - As a user I should be notified of my placing at the end of a tournament
 - As a user I should be able to delete my account
 - As a user I should be able to view the site on my mobile device
 - As a user I should be able to view the site on the desktop browser of my choice
 - As a user I should have a choice of avatar to represent me on the site
 - As a user I should have the ability to select a unique handle which identifies me on the site

#### Infrastructure Tasks
 - Setup continuous integration pipeline
 - Setup Dev and QA environments
 - Setup 'one-click' deployments
