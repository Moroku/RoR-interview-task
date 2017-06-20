# Ruby on Rails interview exercise

The purpose of this exercise is to showcase your ruby on rails skills to show us you know your stuff. 

We've setup a series of tasks for you to complete that will test the things we're looking for.

You'll be communicating with the Moroku GameSystem. The GameSystem Server is a Ruby on Rails application that provides 
gamification to clients via APIs built here at Moroku. You'll be interacting with GameSystem via our API. Take a look at
the [client](http://docs.gamesystemclientapi.apiary.io/#) and [admin](http://docs.gamesystemadminapi.apiary.io/#) API docs. 
on Apiary.

If something is not clear (or in the unfortunate case, if something is not working) please email mat@moroku.com

#### What you get

You'll be given an API token and shared secret to allow making requests to the admin API

##### In this app
In this project you'll find that we've created a helper class called AuthenticationHelper which
will be used to construct the correct authorisation headers needed to access GameSystem. You'll use that in conjunction with
the API token and secret key which we will email to you separately (if you've not received one, please email mat@moroku.com)


#### Let's get started

All of the steps will involve using the Admin API docs.

1. You'll start off by creating a player with the API.

2. We'd like to see the information about your player, so you'll need to display some information about your player
including, their name, the number of points they have and any achievements they might have.

3. We'll need to create a point type, it can be called whatever you like.

4. You'll then need to create a rule, which will contain one predicate and one consequent. The predicate for this rule should be
triggered when an external event is created. The consequent should award some number of points, of the point type you created in step 2.

5. Now you will need to create an external event, once that is created, you need to log that external event against the player. This should 
trigger the rule you made in step 3 and award the number of points to that player

6. Now you need to create a new piece of functionality, players can now have something called an accessory (this is not in the API, you will be building this)
An accessory can be a shield or a sword, or some thing that a player might equip, build a model and create some appropriate fields that an accessory might have.
A page will be needed to display all the accessories a player has available. To help we will also need an API for creating and updating accessories.

7. Show us some other ways you could interact with the api i.e. creating a badge or creating more players and displaying a leaderboard.


#### Outcomes

It would be great if we could see:

* Your resulting app deployed to heroku
* A github repo that we can look at to see your code base
* And some tests around some of the functionality you've created
 





