# Note-Taker

![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)
![badge](https://img.shields.io/badge/license-MIT-orange)

User Story
```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```

Acceptance Criteria
```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```
## Description

This application, called Note Taker,  can be used to write and save notes. This application uses an Express.js back end and will save and retrieve note data from a JSON file.It has been deployed using [Heroku](https://note-taker-basic.herokuapp.com/) .

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [License](#license)

## Installation
 
To run the app from your local machine, you must first download all necessary files. Then, open the app folder and type 'npm start' in the command line to initialize the PORT. Once the PORT has been initialized, the app can be opened in the browser by navigating to 'localhost:3001'. 
Alternatively, for an easier method of accessing the app, use the heroku link.

## Usage 

When the app is opened, the user will be brought to a landing page with a 'Get Started' button. Clicking this button will take the user to the Notes App, where they can enter and save notes. Saved notes will be displayed in the left-hand sidebar, and when one of these notes is clicked, it will appear in the main notes section. If the user would like to enter a new note, they can click the pencil icon in the top right corner, which will clear all the input fields. To delete a note, the user can click the delete icon which is next to each note in the sidebar.![landing page demo](images/demo1.png)

![note taking demo](images/demo2.png)

![note taking demo](images/demo3.png)


 
## License
![badge](https://img.shields.io/badge/license-MIT-orange)
   

Heroku link : https://note-taker-basic.herokuapp.com/

For any questions or to report issues, email me at: jloya7557@gmail.com
