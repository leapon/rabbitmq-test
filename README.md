Git Setup
---------
```
git config user.name $GIT_USER_NAME
git config user.email $GIT_USER_EMAIL

git config credential.helper 'cache --timeout=3600'
git config credential.helper store

git config --global push.default simple

git config --list
```

NPM package update
------------------
```
npm install -g npm-check-updates
ncu -u

npm shrinkwrap
```
