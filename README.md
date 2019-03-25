# Green Print

## A profile to help determine the users carbon footprint and how to decrease it.

### App Name : Green Print

The functionality of this app will feature a profile of the user and a score of their carbon footprint. The user would then able to see their progression of decreasing their score by submitting daily/weekly tasks like using the air conditioner few days out of the year or riding their bicycle to work. The user would then be able to notify friends of their progress. 
This app will need some internet to access the API to process the initial survey, some updates and accessing a potential online community. But notifications could be sent using the app and most tips could be held within the app.
+ The survey will determine initial carbon footprint score. 
+ The User can submit daily/weekly tasks to decrease their carbon footprint.
Environmental foward users would find this app useful and help people understand their environmental impact.

## Current Development of GreenPrint
The current state of GreenPrint is running well, the user is able to switch between fragments, the survey allows for input which is applied to the overall score, the survey is able to save inputs in shared preferences, and the local database is saving footproint scores every time the survey is submitted.
### Unimplemented/Incomplete Elements of GreenPrint
+ Need to have submit button go from survey to the score screen
+ Need the footprint score to be pulled from database and displayed
+ Need retake survey button to clear survey to filled out again.
+ Need update screen to have working checkboxes
+ Need update button to decrease score by appropriate amount and update the footprint score
+ Would like a history fragment/screen to display previous scores
### Known Issues/Bugs
+ If survey is blank and submit button is used, the app crashes
+ Rotating screen returns to the home screen instead of staying on current screen
+ Keyboard on survey covers some of the answer boxes as the screen auto-scrolls

## Android API version and Hardware
For this application, the following were used to test UI and function.
+ Android API 27
+ Nexus 5x emulator

## Third Party Libraries
+ okHttp
+ Retrofit
+ Stetho
+ Google Play Services
+ Room


## External Services
This app accesses the CoolClimate API carbon footprint calculator from the CoolClimate Network.
+ [CoolClimate Network](https://coolclimate.org/index)
+ [CoolClimate API](https://coolclimate.org/api)

## Potential Future of GreenPrint
As this application progresses in development, the focus will start to implement a community based functionality. Users will be able to make a user profile, connect with friends and share. User will be able to receive helpful tips to decrease their footprint, as well as, getting kudos for each time they update their footprint in the form of enviormental equivalencies saved; e.i. amount of trees saved or amount of plastic bottles removed from ciculation per volume of carbon output decreased.
### Goals
+ Main User Profile: upload photo of username, summary, and initial carbon footprint score.
+ Notification Capable: Push notifications to friends to show progress.
+ Maybe be accessible to make a local community to increase environmental awareness.
+ Tips: User can receive tips on what they can do to decrease carbon footprint
+ Fun facts that give them knowledge of what effects decreasing their foot print has on the environment. 
### User Interface Improvements
+ Use Google Signin API 
+ Improvement of GreenPrint logo
+ Use of images as background
+ History fragment that displays dates updated and score


## Wireframes
+ [GreenPrint Wireframe 1](Green_Print_WireFrame1.pdf)
+ [GreenPrint Wireframe 2](Green_Print_WireFrame2.pdf)

## ERD
+ [GreenPrint ERD](GreenPrint_ERD.pdf)

## DDL?

## User Stories
+ [User Story 1](UserStory1.md)
+ [User Story 2](UserStory2.md)

## Javadoc Page
![Javadoc Page](docs/api/)

## Licenses?
TBD

## Instructions for Building GreenPrint
TBD

## Instructions for Using GreenPrint
TBD
