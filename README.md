## Pre-Requisites:

Sign Up:

- Google Analytics:
  - https://analytics.google.com/analytics/web/#/provision/create
- Google Optimize
  - https://optimize.google.com/?utm_source=marketingplatform.google.com&utm_medium=et&utm_campaign=marketingplatform.google.com%2Fabout%2Foptimize%2F

Website:

- Go to https://github.com/new and create a new public repository named username.github.io where username is your username on github
- clone repo locally
- clone files from git@github.com:jeanfarmer126/abtesting-site.git into your new repo
  - (make sure they live at the top level of the github repo)
- commit and push up your files

Google Analytics:

- Navigate to google analytics
  - https://analytics.google.com/
- Select admin in the bottom of the toolbar
- Select create account
- Give an account name
- Create a property for what you will be measuring
- Give a property name
  - Show advanced options
    - Input the URL of your website
    - Create universal property only
- Answer the questions about your company size (this doesn't matter)
- Create
- Copy global site tag and copy into the head of your index.html
- Commit and push up your changes

## Lab

Optimize

- Create Account
- Add container
- Go to settings
- Link to analytics
- Select the property that was just created
- Link
- Create an experience
- Input a name
- Add your website
- Using the editor create at least one variant to target
- Select the checkout button and modify the color
  - navigate to the background section and change the rgb value
- Create an objective
- Install optimize
  - Select view instructions
  - Copy the script snippet and paste in the head of your index.html
  - Commit and push up the changes
- Start
