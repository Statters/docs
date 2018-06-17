### Part 1 - *What*

#### Project Name:
##### Late Joiners Sports Tipping App

#### Project Description:
A Web application that will allow users to sign up and place their predictions of the results of a variety of sporting tournaments, and track their success against other users.

Users will be able to select from a variety of upcoming matches, with the option not just to choose the outcome, but predict scores/results as well.

When the next round of a tournament begins, Users will receive a notification that the time has come for them to make their picks for the next round.

At the end of the tournament, the user (or users) with the best record can claim bragging rights for their prescience!

The application will be available to users across a variety of devices, from desktop browsers, to tablets and mobile devices.

#### The Team

##### Luke Warren
bio

##### Matt Greig
bio

##### Blair Fraser (s3641830@student.rmit.edu.au)
I have some prior experience with Java, Perl, PHP, Python (the latter of which I’m using occasionally in my current non-programming job to automate workloads). I enjoy programming in general, with a current preference towards backend development using dynamically typed languages (although I have not at this stage had much call to involve myself in frontend coding).

As well as the above languages, I have some experience working with RDBMSes, but am looking forward to getting experience with technologies I have not previously been exposed to (version control systems (specifically git), NoSQL and javascript frontend and backend frameworks (the MEAN stack).

Challenges during the project will be getting up to speed on these new (to me) technologies to the point that I am able to contribute as effectively as I want to.

Tasks that I would envisage myself working on are could be anything applicable to my level of skill at the time utilizing technologies belonging to the MEAN stack (frontend or backend-oriented tasks), leveraging my existing python knowledge to write a script to harvest data from APIs, transform it to the required format and write it to the mongoDB instance (though something like this wouldn’t be required at the extended functionality stage), helping generate and manage documentation.


##### Tyrone Cook
bio

##### Adam Rowsell
bio

##### ????
bio

#### Demonstrable Outcomes

##### Features
*describe the features that can be demonstrated*
*list 5 features and explain how we will validate it has been implemented*

1. Our system should be able to store information about user accounts, and allow users to create new accounts or delete their currently existing account
Once implemented this can be tested by attempting to create a number of new accounts, and manually inspecting the database contents after that has been done, then deleting an account and manually inspecting database contents to ensure they match expectations.

2. Our system should be capable of storing information on various soccer tournaments in a mongoDB instance
Once implemented, we can test this by attempting to populate the database with static data and subsequently manually inspecting database contents to ensure they are what they should be.

3. Our system should be able to display information on overall tournaments as well as individual matches to the user
Once implemented, we can test this by manually checking the database to see what tournaments should be displayed to the user, and then using the system to verify that that does occur. Same process can be followed to perform a spot check on an individual match to ensure the system is showing the user the information it should be.

4. Our system should allow the user to nominate their picks for the currently chosen match (whether simply picking who they think will win or the final score), with this data then being saved in the database
Once implemented, we can test this by manually inspecting the database and ensuring that the picks data we have entered via the website has in fact been saved to the database as it should have been.

5. Our system should display to users the actual results for games that have concluded where that user had a pick, as well as data about their overall picking record
Manual inspection of the database can be used to ensure that data shown on the results page is correct, both in terms of the game result and the user's pick/whether or not the user's pick was correct/that user's overall picking record to this point

At each stage, a more technical testing process could be followed - i.e. selenium (or something similar) could be used to automate the process of extensively testing objective #3 (i.e. to ensure that ALL tournaments in the database are displayed, and that ALL information for those tournaments is viewable, and the same for individual games, as opposed to manual spot checks of individual tournaments/games)



##### Extended features
*features to be added if time permits*
*list at least 3 and explain how we will validate it has been implemented*

1. Our system should source tournament and game data in real-time from APIs for tournaments where an API is available.
This can be tested by entering static data into the database that differs from that currently being reported by an API, and using the website to see if it displays that static data or if it has retrieved data using the API and displayed that instead.


#### Project Motivation
*describe what motivated the group to choose this project*

- We felt it was a good opportunity to get exposure to a stack we wanted experience in.
- Provides a potentially handy portfolio item post-degree
- Was pertinent given the popularity of sporting results in modern culture

#### Project Justification
*explain how project scope fulfills below criteria*

##### Justified Workload
*develop project schedule*

##### Beyond Current Capabilities
*explain how it will extend current IT knowledge*

##### Project Risks
*list 3 project risks that would majorly interfere with project outcome*
1. API goes offline

*list 3 team dynamics related challenges that would delay project's progress*
1. Time difference of team members

*for each risk and challenge indicate how we propose to monitor and minimise the issue arising* [MG this sure sounds a lot like SEPM in 3rd year!]

### Part 2 - *HOW*

#### Resources and Tools
*list the technology, tools and resources you will use for each phase of the project*

*Each tool/resource needs*
- Name
- short Description
- rationale for using
- specific version and cost (if any?)
- describe any alternatives not used

#### Collaborative Workspaces
*Describe workspaces used to collaborate*
*List workspaces*
- [Trello](https://trello.com/b/hO83Xzoj/latejoiners)
- [github](https://github.com/LateJoiners)
- [Slack](https://rmitlatejoiners.slack.com)
- [Google Docs](https://docs.google.com)
- Google Hangouts

#### Communications Expectations
- *List tools to communicate*
- *Describe expected frequency of responses*
- *Describe use of tools in weekly workflow*
- *Detail action plan in event of communications not being responded to by a team member or members*

#### Decision Making
Majority-rule where each vote members' vote has equal weighting.

*Describe decision-making process*
*Describe dispute resolution process*


### Part 3 - *WHEN*
*List Tasks with enough detail so assessor can see what's expected from **each** team member **each** week*
*List tasks to be completed between Wk 3 - 12 with a hyperlink to the corresponding [Trello](https://trello.com/b/hO83Xzoj/latejoiners) card*
*Each task needs*
- Descriptive Title
- Planned Start and End Date
- Lead by (member's name)

*Linked Trello card should include*
- A descriptive title
- A planned start and due date
- The estimated time required to complete the task
- A precise description of the task that is to be completed with any necessary contextual information.
- A description of the artefact the task will produce.
- Who is responsible for managing the task to completion.

### Part 4 - *Professionalism*
*Font **must** be Arial 12*
*Figures must be clearly labelled*
*Include a Table of Contents with page numbers*
*Where possible use **bullet points** *
