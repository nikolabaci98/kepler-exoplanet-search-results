# Building an Flask App

#### [Flask Documentation](https://flask.palletsprojects.com/en/1.1.x/quickstart/)
#### [Bootstrap Documentation](https://getbootstrap.com/docs/4.3/components/alerts/)
[Bootstrap Themes](https://getbootstrap.com/docs/4.0/examples/)


These instructions were adapted from [this tutorial blog](https://blog.cambridgespark.com/deploying-a-machine-learning-model-to-the-web-725688b851c7). 

1. Sign up for a free Heroku account at https://signup.heroku.com/signup/dc
2. Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed
3. For Mac Users: [Install Homebrew](https://brew.sh/) if you dont have it already
4. Install the [Heroku CLI tool](https://devcenter.heroku.com/articles/heroku-cli#download-and-install).  Mac users need homebrew to install Heroku, Window users don't need it to install Heroku

___

### STEP 1: Create a github repo with your webapp files.

1. Create a github repo for your app
2. Clone that repo to your local machine
3. Git add, commit, and push the webapp files to your repo

___
### STEP 2: Create and push files to Heroku.

1. From your github repo folder, in your terminal, type in `heroku login`.  Follow the login instructions
2. Next create your app using `heroku create your-webapp-name`
3. Then, add your git to heroku by using `heroku git:remote -a your-webapp-name`
4. Finally, push your files to heroku by using `git push heroku HEAD:master`

___
### Making changes to your app. 
1. Add, commit, and push all the changes to your github repo.
2. Run the `git push heroku HEAD:master` command. 


