Git/GitHub Checklist

One person on each team
  1. Create a new repo on gitHub
  2. clone it to your local computer
  3. create .gitignore and add node_modules and .env
  4. create package.json
  5. add public/index.html with a basic html skeleton
  6. add team as collaborators

Each person on the team
  1. clone the repo
  2. create your own branch git checkout -b YOURBRANCHNAME
  3. from the branch you're working on
    1. gitcheckoutmaster
    2. gitpulloriginmaster
    3. gitcheckoutYOURBRANCHNAME
    4. git pull origin master This will sync any new master code into your local branch
  4. Fix any merge conflicts.
  5. work on code in your branch. add/commit as necessary.
  6. If the feature is done and tested and you are getting ready to submit a pull request:
    1. gitadd-A
    2. gitcommit-m"commitmessage"
    3. gitpulloriginmaster
    4. Fix any merge conflicts
    5. gitpushoriginYOURBRANCHNAME
    6. Go to GitHub and submit a pull request from your branch to master
