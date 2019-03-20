BACKGROUND
==========
PROJECT TITLE:  	Android App - Nenekara
CLIENT:         	Te Wānanga Māori, Whitireia Community Polytechnic
CLIENT REP:		Eruera Ruwhiu (Te Wānanga Māori, Whitireia Commmunity Polytechnic)
PROJECT SUPERVISOR:     Kevin Shedlock
PROJECT TEAM:    	Jayson Cocks, Patricia Nellas, Marina Kerschbaumer
                	(Bachelor of IT students, Whitireia Community Polytechnic)
VOICE RECORDINGS:	Kevin Hotu (Tutor, Te Wānanga Māori)

MOTIVATION:This application is being created to help Māori language students from Whitireia's Wānanga Māori practice sentence structures.  
PROTOTYPE: The initial Android prototype  was created in dev iterations 1.0 - 1.3 (Semester 2: July-October 2018)


TECHNICAL SPECIFICATIONS OF PROTOTYPE:
======================================
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

Images:
https://designassembly.org.nz/2017/09/11/cultural-relevance-in-the-digital-age-emotiki/?fbclid=IwAR2qdI7UVns_S2ec7tSgxTtFyG-N3EEGw5dL47SStGT5K1nMpVyic3cxvQM

Note on macrons:
In order to easily type macrons (ā,ē,ī,ō,ū etc) it is best to install the Māori keyboard. 
Once the keyboard is installed users simply need to type '`' and then the relevent vowel.
Instructions on how to do this can be found at https://kupu.maori.nz/about/macrons-keyboard-setup  

DEV INTERATION SUMMARY
======================
DEV ITERATION 1.0
Completed: 10 September 2018
- basic start screen
- category screen provides categories
- sentence loading to screen
- basic drag and drop working
- clear and OK buttons added
- image added to database


DEV ITERATION 1.1
Completed: 24 September 2018
- fixed duplication of words when screen is reloaded.
- drag and drop made easier by adding padding around the words and putting border around file.
- Layout: moved buttons to the bottom of the screen, so drag and drop does go over the buttons. 
- Basic instructions for general app use added (hardcoded).
- question is hard-coded into the app.

DEV ITERATION 1.2
Completed:15 October 2018
-About text updated.
-Category specific instructions added (hardcoded).
-question loads from database.
-red-herring word (kāore/ehara) included when sentence is loaded onto the screen
-layout has been updated
-populateTable has been updated so that the words from each sentence has an ID. This can eventually help identify if the sentences are correct or not.
-app loads multiple sentences sequentially 
-audio hard-coded for each sentence.
-hard-coded incorrect/correct is working.
-buttons rearranged and renamed
-hard-coded images are working.
-look and feel of application changed to include traditional Māori colours and designs.

DEV ITERATION 1.3
Completed and client signed-off: 23 October 2018
-appearance of UI refined
-client provided sentences and audio recordings.
-added images that reflect the new sentences (hardcoded)
-audio added to the Correct/Incorrect popups.

OUTSTANDING ISSUES/TO DO
=======================
- Drag and Drop:  the drag and drop functionality needs to be modified so that users are able to reposition words in the answer panel by dragging the individual words.  Currently, if a user taps a word it will send that word to the far right of the line, but the user cannot chose where the word is placed .
- Full implementation of the RDBMS: The category table needs to be added to the database and associated with the sentence table.  As there is currrently only one category being used, this has been hardcoded in the prototype.
- Incorporation of images and audio columns into the Sentences table. Currently the audio and images for the three example sentences are hardcoded.
- Investigate the ablity of SQLite to deal with larger quantities of data, including images and audio.
- Useability needs to be tested on actual end users (i.e Te Reo students).  Working within the constraints of the project, the user testing for the prototype iteration was done by the client.
- Obtain feedback on the UI from end-users. As with useability, feedback and approval were only obtained from the client about the UI in the prototype iteration.






