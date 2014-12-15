ContainerSiteApi
================

##What is this Container Site all about?

There are a number of solutions available for creating a web site with such things as content management, blogging, email address collection and management, and email marketing systems. However, many of these systems do not use industry leading best practices when it comes to testing, deployment, scaling, and operations management.


##How to contribute

[Go with the Flow](Github_flow.png)

We have a suggested workflow for contributing to this and other git based projects. Try it out!

- First use Github to Fork this project. In the upper right hand corner, click "Fork".
- On your own machine use `git clone` to clone your forked repo.
	- `git clone https://github.com/<your github username here>/ContainerSiteApi.git` 
- On your local machine, move to the ContainerSiteApi folder and add the main project as an upsteam repo.
	- `git remote -v` : this will show you your current remote repositories. Your forked version of the repo should be "origin".
	- `git remote add upstream https://github.com/trcollinson/ContainerSiteApi.git` : this will add the main repo as a new remote called upsteam.
	- `git remote -v` : you will now see 4 lines that look like the following:

		```
		origin  git@github.com:<your github username>/ContainerSiteApi.git (fetch)
		origin  git@github.com:<your github username>/ContainerSiteApi.git (push)
		upstream        git@github.com:trcollinson/ContainerSiteApi.git (fetch)
		upstream        git@github.com:trcollinson/ContainerSiteApi.git (push)
		```

- Checkout the development branch to start working on a change, bug, or feature you would like to see.
	- `git checkout development`
- Make sure to check for changes from the main project before you start development.
	- `git pull upstream development` : this will pull all changes from the main projects development branch into your local environment.
- When you are done, make sure to add your changes to a commit and commit them.
	- `git status` : to see which files have been marked by git as changed.
	- `git add <files you changed>` : to add your changed files to a commit or : `git add .` : to add all of your changed files to a commit.
	- `git commit -m "your message here"` : to commit the changes. Make sure your message is descriptive.
- Don't forget to check for changes from the main project before pushing your changes up.
	- `git pull upstream development` : again, this pulls changes from the main project down to your local. Make sure to fix any merge conflicts before moving to the next step. Feel free to ask for help if you need it!
- Now push to your fork. Do not try to commit directly to the main project.
	- `git push origin development` : this pushes your changes to your forked repo on github.
- Finally, make a pull request to add them to the main project.
	- Go to your forked repo on github and click on "Pull Requests" in the right hand menu. This will give you an option to make a pull request to the main project.

Note: If a maintainer of the main project makes a note for you to fix something on your pull request, you do not need to make a new pull request. Simply make more changes, commit them as above, and push them to your fork of the project. The new commit will automatically be added to the pull request.
