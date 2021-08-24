# Heroku Notes

```js
// create heroku app with name of your choice
heroku create app-name

// adding heroku configs from the command line
heroku config:set DATABASE_URI=database_uri_here

// check if there is heroku app on your git project repo.
git remote -v

// remove heroku from current project  
git remote rm heroku

 // delete a heroku app
 heroku apps:destroy app-name

// Connect already made heroku app to git project
heroku git:remote -a heroku-app-name 
```
