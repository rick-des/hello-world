# Milestone 1 - Instructions to the Instructors

* Team: Daily Survey Reminder
* GitHub Repo URL: [Repo link](https://github.com/memphis-cs-projects/capstone-Daily-Survey-Reminder/ "Repo")
* Demo Video URL: 	[Back-end html](https://www.youtube.com/watch?v=v8UAT7fb4M0), [Survey form](https://www.youtube.com/watch?v=JSaWdVA5L1E)
* Git Tag for Demo Video Version of Code: [v1.0-prql](https://github.com/memphis-cs-projects/capstone-Daily-Survey-Reminder/releases)


## File Locations in Repository ##

**Shane**
*	https://github.com/memphis-cs-projects/capstone-Daily-Survey-Reminder/tree/v1.0/Project/Web/	
*		mentor_home.html
*		qform1.html
*		qform2.html
*		qform3.html
*		style.css
*		config.php
*		index.html
*		login.php
*		questions.html

	*From the web folder, open index.html. This is the login page. From here, you can navigate to the mentor home page. You don't need a password at this point, just click the submit button. From the mentor home page you can select "edit surveys" fromt the menu and navigate the different editing pages.* 

*Rick
https://github.com/memphis-cs-projects/capstone-Daily-Survey-Reminder/tree/master/Project/Survey
*                Survey.css
*                Survey.html
	*The main file is "Survey.html", which is the prototype of the entire HTML form thwt will be implemented into the Android WebView. Survey.css is primarily for Survey.html, which will provide color and border schemes. NOTE: at the time of this writing, Survey.html was a prototype for "hard-coding" all provided questions into an HTML format. Dynamic implementation of questions from a JSON or XML are to be added shortly within the current iteration.*
	
* Milestone 1 Individual Assignment Outcomes: 

__Shane:__ Created back-end login page, home page and survey editing pages. 

__Umair:__https://github.com/memphis-cs-projects/capstone-Daily-Survey-Reminder/tree/master/Project/QuizApp1
	1. You'll need to import this project into Android Studio
	2. Once imported, you'll need to run this either on an emulator on android phone.
	3. Android phone is preferred, since emulator requires a lot of PC resources, and may not work on all computers.

__Rick:__ Created front-end html for Survey (prototype; see above). CSS prototype or design and hiding questions based on previous selections.

__Clayton:__

* Who-Did-What Document for Demo Video: [Video doc](https://github.com/memphis-cs-projects/capstone-Daily-Survey-Reminder/blob/master/Documents%20and%20Diagrams/Iteration%201/Video%20doc.md)

* Up-to-Date Feedback: 
- Summary: "Yikes" , your output does not reflect the time and your effort
- Do more. Integrate all the parts.
- Talk to mentor before incorporating FireBase; *give pros _and_ cons*
- Make sure _every_ team member has entry-level knowledge of each other member's assignments
- possibly create local web server for testing
- (Completed) Make a clear, proper directory for your project
- Security Risks/Concerns
- - Could people access these web pages in any way besides the app?
- - You should consider hashed passwords
- - Is the web server (sic; web app) the _entire_ interface? 
- - - If not, and you are considering a "mixed approach", it may lead to a significant security risk
- - - make it "wholey" one way or the other


* Up-to-Date Plan and Design Artifacts:https://github.com/memphis-cs-projects/capstone-Daily-Survey-Reminder/tree/master/Documents%20and%20Diagrams

* Requirements specifications and their statuses: 
	1. Develop a login page for an android app - Status: Complete
	2. Create database in MYSQL to user and store survey data. - Status: Incomplete. Specifications have changed, using a different database.
	3. Integrate database into login page. - Status: Complete
	4. Develop HTML survey form - Status: Complete
	5. Implement push notifications using Android Notification API - Status: incomplete, working independently but not implemented in app. 
  

  
  - Prioritization and Schedule of Requirements Implementation: xxx
  Tasks sorted by highest priority first

	1. Develop a login page for an android app - Due by 3/12
	2. Create database in MYSQL to user and store survey data. - Due by 2/21
	3. Integrate database into login page. - Due by 2/28
	4. Develop HTML survey form - Due by 2/28
	5. Implement push notifications using Android Notification API - Due by 3/10


  
  - Architectural design: xxx On github: https://github.com/memphis-cs-projects/capstone-Daily-Survey-Reminder/blob/master/Documents%20and%20Diagrams/Passive%20MVC%20architecture.png

  - Database design (if system will have a DB): xxx  https://github.com/memphis-cs-projects/capstone-Daily-Survey-Reminder/blob/master/Documents%20and%20Diagrams/DB%20ER%20Diagram.png
  - Risks and their statuses: 
  - - Technical (technology instability, etc)
  - - - Moderate unfamiliarity with Android Development Kit
  - - - > Tutorials, generating "dummy" forms
  - - - Keeping users' progress saved in case of premature closure
  - - - - phone dies
  - - - - leaving app before saving
  - - - - > Difficult
  - - - - > Use of Database function
  - - - Configuring Google FireBase
  - - - - Creating and handling JSON files
  - - - - > Moderate Risk
  - - Volatility (changing requirements)
  - - - The wording of the questions may shorten, depending on their length
  - - - > Little to no risk
  - - - > Revisions via mentor input
  - - Difficulty
  - - - Setting up a database to connect to an app
  - - - > Moderate
  - - - Android app development 
  - - - > Moderate risk
  
  - Quality assurance plan: xxx
  - - good coding practices
  - - - sensible variable, method and class names
  - - - lots of comments
  - - frequent testing
  - - - messaging team for all integration and updates on accomplishments or "breakthroughs"
  - - refactoring  
 
  
  - Feedback management plan and setup: xxx
  - - taken and discussed among the team in:
  - - - in-person during one of our class times
  - - - outside meetings group text 
  - - - discord channel used for project discussion,
  - - then we will decide how to incorporate feedback into our designs
  
  - Collaboration plan: 
  - - physical meeting: 
  - - - Fridays 12PM-2PM
  - - - Mondays, Wednesdays normal class time
  - - Non-physical communication
  - - - text group (frequent)
  - - - Discord server (moderately)
  - - Mentor meetings

