# Hang In there

### Developers
- [Kristi Miller](https://github.com/Kristiannmiller)
- [Estelle Staffieri](https://github.com/Estaffieri)
### Project Manager
- [Scott Ertmer](https://github.com/sertmer)
### Project Links
- [Repo](https://github.com/Kristiannmiller/hang-in-there-boilerplate)
- [Deployed Page](https://kristiannmiller.github.io/hang-in-there-boilerplate/)

## Set-up
- Fork the repo and clone down into terminal
- Open in text editor
- Read the README
- In terminal, run command "open index.html" to interact with app.

## Overview & Learning Goals
For our mod 1 paired project, we will build a webpage that randomly generates motivational posters with quotes. It should, eventually, also allow user a user save their own posters as well.

We will develop our skills and understanding in JS functionality and changing webpage views.

## Progression

7/7: Gave day one deliverables to instructors and reviewed the project scope. Created DTR version one.

7/8: Reviewed DOM, HTML connections. Discussed key functions that might be necessary for the project.

7/9: Fixed GitHub remote repo connection. Initial commit was created to load poster when window is refreshed with the displayCurrentPoster function. We created the functionality for the "show another random poster button". We then pushed these updates to our master branch. We then created the showFormView, showSavedPostersView, and sendToMainPage functions.

<p align="center">Image of Main Poster View </br>
  <img width="460" height="300" src="" alt="Screenshot of Main Poster View ">
</p>


7/10: Update the project README file and added project progression notes. Created createNewPoster function, with intention of revisiting ideas on 7/11.

7/11: Connected user inputs to arrays via a new Poster class instance. Displayed user created poster on mainPosterView. Corrected the eventListener for createNewPoster and deleted unneeded pseudocode. Added the savePosterToArray function removing duplicates.

7/12: Added savedPostersGrid global variable. Added savePosterToGrid function. Debugged and refactored the showMyPoster button. Conducted function review, found bugs.

7/13: Fixed duplication bug with savePosterToArray button. Renamed some confusing variable names. Added html to mini-poster class using interpolation to get saved posters page to populate.

7/14: Removed unneeded global variables. Analyzed ternary statements for array populating. Concluded that ternaries functioned correctly but did not express developer empathy. Created switchPages function to dry up repetitive functions. Declared a querySelector for switchPages. Looped over page views, adding or removing the hidden attribute as declared. Added it to the relevant eventListeners. Removed old code and fixed spacing.

## Functionality Showcase

<p align="center">What does it show</br>
  <img width="460" height="300" src="" alt="What does it show">
</p>

<p align="center"> What does it show</br>
  <img width="460" height="300" src="" alt="What does it show">
</p>

<p align="center">What does it show </br>
  <img width="460" height="300" src="" alt="What does it show">
</p>

<p align="center">What does it show</br>
  <img width="460" height="300" src="" alt="What does it show">
</p>

Project spec & rubric can be found [here](https://frontend.turing.io/projects/module-1/hang-in-there.html)
