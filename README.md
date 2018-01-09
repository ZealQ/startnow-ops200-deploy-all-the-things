DEPLOY ALL THE THINGS

- Open a terminal like (gitbash)

- Type cd ~/oca/, hit enter

- Type cd startnow-ops200-deploy-all-the-things, hit enter

-(When loading up project to work on in terminal after loading the cd startnow)
 Type npm install with out this  step you will not have your node moduals and all will be lost.

 Summery

 Today, the Dev is  going to push their work live to the internet!
As always, don't worry if some of this workshop doesn't make sense yet or if it uses unfamiliar tools. 
there will be learning on how to deploy an application step by step throughout this tutorial.

How to Follow Along

Download the matching starting project from the Origin App.
Once it's downloaded, make sure to initialize a git repository for this project and push it to GitHub.
Setup

First, sign up for a free Heroku account. It's also a good idea to enter a payment method at this time so projects can be deploy unlimitedly with  free apps.there won't be a charge unless there are explicit increases to the size of a dyno (a very manual process).
You should take this opportunity to explore Heroku's dashboard and get familiar with the site and it's functionality.
Next, follow the instructions in this guide to install the Heroku CLI - a tool we'll use to talk to Heroku via CLI.

Sidenote: Almost everything that can be done using Heroku CLI can also be done visually in the browser, it's just quicker to enter a command than it is to navigate through a web application.

Once it has been downloaded and installed, login to Heroku via CLI. This is done because we will be executing commands that are specific to the Dev account. 

Open a terminal and run the following command to login to Heroku in the CLI:

$ heroku login

# Enter credentials and 2FA code if requested
After you've logged in, you're ready
