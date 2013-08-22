truth-or-lie
============

a game to detect whether people are lying

commands to set it up on heroku:

```
heroku apps:create truth-or-lie
heroku addons:add mongohq:sandbox

heroku config:set HOST=http://truth-or-lie.herokuapp.com
heroku config:set SESSION_SECRET=change_me

git push heroku master
```
