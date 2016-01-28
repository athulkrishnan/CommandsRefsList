# References


Azure Commands:

git remote add azure https://username@needsmoregit.scm.azurewebsites.net:443/NeedsMoreGit.git

git push azure master


Change heorku remote:

- Remove old remote:
git remote rm heroku

- Add new remote:
heroku git:remote -a appname

-Clone Heroku App:
heroku git:clone -a theirapp
