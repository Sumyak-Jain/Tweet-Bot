# Tweet-Bot
## A twitter bot (client type ) is made using JAVA which is going to have functionality like
- [x] Tweet

- [ ] Like

- [ ] Comment 

- [x] Showing the latest timeline 

- [x] Get particular tweets
 
- [ ] Retweet

## How to contribute

It is an open source project you are free to contribute , you can use the following way to contribute.

1. Fork the repository to your own GitHub account.

2. Clone the repository to your local machine
```
$ git clone "https://www.github.com/{Username}/Tweet-Bot.git"
```
where username is your GitHub account username.

3. Create a branch where you can do your local work.
Never work on **master** branch as we do not allow master commits except by admins.
```
$ git branch {branchname}
$ git checkout branchname
```

4. Do your work and stage your changes.
```
$ git add <filename>
```

5. Commit you changes with a commit message containing your name, file(s) worked upon, changes added.
```
$ git commit -m "Name| files| Changes"
```

6. Push changes to your forked repository
```
$ git push -u origin branchname
```
7. Create a pull request to the upstream repository.

## Synchronize forked repository with Upstream repository

1. Create upstream as our repository
```
$ git remote add upstream "https://github.com/ReTweetDevOps/Tweet-Bot"
```

2. Fetch upstream changes in local machine
```
$ git fetch upstream
```

3. Switch to master branch
```
$ git checkout master
```

4. Merge changes in local machine
```
$ git merge upstream/master
```

5. Push changes to your forked GitHub repository
```
$ git push -f origin master
```

