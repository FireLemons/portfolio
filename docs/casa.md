# CASA
## About CASA
CASA or **C**ourt **A**ppointed **S**pecial **A**dvocate is a national nonprofit organization serving children in the foster care system. CASA volunteers help chidren by looking out for the child's best interests while they're in the foster care program. Some examples of what CASA volunteers do include making sure their youth has all their identifying documents and making sure their youth has permanent family or other adult connections.
  
## About the App
This casa app is maintained by volunteers from the [RubyForGood](https://rubyforgood.org/) community. RubyForGood maintains this app with the goal of saving money for CASA organizations so it does not charge for app features if it can help it. It serves about 100-200 monthly users across 4 counties in Maryland.  

[:octicons-mark-github-16: Github repo here](https://github.com/rubyforgood/casa)  
  
### App Summary
The primary functions of this app are to  

 - record work done by the volunteer
 - remind volunteers about upcoming deadlines for tasks
 - generate reports from data stored in the app
 - allow monitoring of cases and volunteers by supervisors

### App Archetecture
#### Backend
The main framework for RubyForGood's CASA is ruby on rails. Some major rails dependencies that define the app are:

 - [:octicons-mark-github-16: devise](https://github.com/heartcombo/devise) for all our authentication needs
 - [:octicons-mark-github-16: pundit](https://github.com/varvet/pundit) for controlling access to data
 - [twilio](https://www.twilio.com/) for SMS messaging
 - [rspec](https://rspec.info/) for unit tests
 - [:octicons-mark-github-16: capybara](https://github.com/teamcapybara/capybara) for system tests

 [Postgres](https://www.postgresql.org/) is our database management system.

#### Hosting
The app is hosted on [Heroku](https://dashboard.heroku.com). Heroku's built in Github integration is used for our QA(quality assurance) environment meaning our QA envirnment contains the latest changes from the main branch of our repository on github. From the Herkou dashboard the production environment can be manually updated to match QA.

#### Frontend
CASA is a multi page website with [AJAX](https://en.wikipedia.org/wiki/Ajax_(programming)) mixed in. CASA's main javascript framework is [jQuery](https://jquery.com/). [Sass](https://sass-lang.com/) is used to organize css. We use the [plainadmin theme](https://plainadmin.com/) which is built on top of bootstrap 5. Using this theme allows the app to be mobile friendly.  
  
CASA is a [progressive web app](https://web.dev/what-are-pwas/) and has an android app as a [trusted web activity](https://developer.chrome.com/docs/android/trusted-web-activity/). This means the website can have app like features like offline mode without having to be remade as an app.

## My CASA Contributions

### Code Contributions


### Other Contributions
#### Weekly Deploy
#### Helping Contributors
