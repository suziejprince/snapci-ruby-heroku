[![Build Status](https://snap-ci.com/snap-ci-examples/snapci-ruby-heroku/branch/master/build_image)](https://snap-ci.com/snap-ci-examples/snapci-ruby-heroku/branch/master)

A barebones Rails app which can easily be deployed to Heroku using [Snap CI] (snap-ci.com).

This application supports the [Getting Started with Snap CI - simple deployment example] (https://docs.snap-ci.com/getting-started/simple-deployment-to-heroku/).

# Deploying this app to Heroku using Snap CI

##Get setup 

Sign up for:
* [Github] (www.github.com) and validate your email address
* [Heroku] (www.heroku.com) and choose Ruby as your primary development langauge
* [Snap CI] (www.snap-ci.com) and authorize Snap CI to access your Github account

##Fork this repository 

* Login to Github and fork this repository
* You should now see the snapci-ruby-heroku as one of your Github repositories as: github-userid/snapci-ruby-heroku

##Add forked repository to Snap CI

* Go to [Snap CI] (www.snap-ci.com)
* Add the snapci-ruby-heroku build. The build should start and run the two default stages - FastFeedback and Integration. 

##Customise your build

* Select “Customize it here” 
* From the build pipeline screen click on the "Add Stage" button 
* From the commonly used stages click on “Deploy” and select “Ruby” 
* Then select “Basic” under “Heroku” 
* Supply your Heroku credentials
* Specify an application name. Don't use upper case characters and make it unique (we suggest you include your user ID)
* Save the configuration


##Your app is deployed to Heroku using Snap CI

* Snap CI will build and deploy your app to Heroku
* Navigate to your new app (e.g. heroku-app-name.heroku.com).  
* Celebrate!

# Running locally

Make sure you have Ruby installed. 

      $ git clone git@github.com:snap-ci-examples/snapci-ruby-heroku
      $ cd ruby-getting-started
      $ bundle install
      $ bundle exec rake db:create db:migrate

Your app should now be running on localhost:5000

