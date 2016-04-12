-# Recs With Parks

![Build Status](https://codeship.com/projects/4fb98df0-dcb7-0133-b68c-2e9843291021/status?branch=master)
![Code Climate](https://codeclimate.com/github/concreteface/recswithparks.png)
![Coverage Status](https://coveralls.io/repos/concreteface/recswithparks/badge.png)

 == README

(Placeholder for homepage screenshot including nice picture of Boston Public Garden)

Group project for Launch Academy developed by John, Meredith, Kevin and Evan.

This project is a web application that allows people looking for parks in the Boston area to look up parks by location and rating to find good parks near where they are. This way they are able to get outside more in places they want to be while still in the city.

This project is developed using Ruby on Rails with a PostGres database, accessed with ActiveRecord. It is intended to be used in a modern web browser.

Profile photos are uploaded with the CarrierWave gem, and results are paginated with the Kaminari gem.

Feature tests utilize RSpec/Capybara.

This app is hosted on Heroku. (Link TBD)

**Features**

* Create a park for reviews
* Rate a park and include a new reviews
* Vote on a review - upvote the ones you agree with, downvote the ones you don't
* Sign up for an account, with a profile picture
* Search for a specific park
* Sign up to be an administrator to help moderate the site
* Get an email when someone reviews a park you added
