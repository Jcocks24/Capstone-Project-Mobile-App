BACKGROUND
==========

PROJECT TITLE:  Android App - Nenekara
CLIENT:         Te Wānanga Māori, Whitireia Community Polytechnic
CLIENT REP:		Eruera Ruwhiu (Te Wānanga Māori, Whitireia Commmunity Polytechnic)
PROJECT SUPERVISOR:     Kevin Shedlock
PROJECT TEAM:    Jayson Cocks, Patricia Nellas, Marina Kerschbaumer
                (Bachelor of IT students, Whitireia Community Polytechnic)

MOTIVATION:     This application is being created to help Māori language students practice sentence structures.  
PROTOTYPE:
The initial prototype has been created in ITERATIONS 1.0 - 1.3 (Created July-October 2018)


TECHNICAL SPECIFICATIONS of PROTOTYPE:

- Development environment: Android Studio 3.1.4
- Compile SDK version: 28
- Minimum SDK version: 23
- Target SDK version: 28

Devices used for development: Nexus 5 running Android 6.0.1  (the application may not be fully functional on other versions of Android) 

Repository:
http://20020584@git.pcsupport.ac.nz/21100124/TeReoApp_2018.git

Database:
SQLite used in conjunction with DB Browser for SQLite.
https://www.sqlite.org/index.html
http://sqlitebrowser.org/




ITERATION 1.0
Completed: 10 September 2018
- basic start screen
- category screen provides categories
- sentence loading to screen
- basic drag and drop working
- clear and OK buttons added
- image added to database


ITERATION 1.1
Completed: 24 September 2018
- fixed duplication of words when screen is reloaded.
- drag and drop made easier by adding padding around the words and putting border around file.
- Layout: moved buttons to the bottom of the screen, so drag and drop does go over the buttons. 
- Basic instructions for general app use added (hardcoded).
- question is hard-coded into the app.

ITERATION 1.2
Completed:15 October 2018
-About text updated.
-Category specific instructions added (hardcoded).
-question loads from database.
26/9/2018
-red-herring word (kāore/ehara) included when sentence is loaded onto the screen
3/10/2018
-layout has been updated
-populateTable has been updated so that the words from each sentence has an ID. This will eventually help identify if the sentences are correct or not.
-app loads multiple sentences sequentially 
9/10/2018
-audio hard-coded for each sentence.
-hard-coded incorrect/correct is working.
-buttons rearranged and renamed: 'clear' is now 'reset', 'ok' is now 'confirm'.  'Confirm' button has been moved to the left and 'Reset' moved to the middle.  'Home' stays on the right.
-hard-coded images are working.
-look and feel of application added to provide more of a Māori feel.


	



