# Ruby on Rails interview exercise

The purpose of this exercise is to showcase your ruby on rails skills to show us you know your stuff. 

We've setup a series of tasks for you to complete that will test the things we're looking for.

You'll be communicating with the Moroku GameSystem. The GameSystem Server is a Ruby on Rails application that provides 
gamification to clients via APIs built here at Moroku. You'll be interacting with GameSystem via our API. Take a look at
the [client](http://docs.gamesystemclientapi.apiary.io/#) and [admin](http://docs.gamesystemadminapi.apiary.io/#) API docs. 
on Apiary.

If something is not clear (or in the unfortunate case, if something is not working) please email mat@moroku.com

#### What you get

You'll be given an API token and shared secret to allow making requests to the admin API and a second API token and shared
secret pair to allow making requests to the child API.

##### In this app
In this project you'll find that we've created a helper class called AuthenticationHelper which
will be used to construct the correct authorisation headers needed to access GameSystem. You'll use that in conjunction with
the API token and secret key which we will email to you separately (if you've not received one, please email mat@moroku.com)

##### On GameSystem
You'll be setup with:
* Your own tenant - This will most likely be your name
* A single player - This will be the player you'll be interacting with on GameSystem
* Rules - We'll have created some rules for you

#### Let's get started

1. Firstly we'd like to see the information about your player, so you'll need to display some information about your player
including, their name, the number of points they have and any achievements they might have


2. With the help of the Apiary docs, you'll need to create an external event on game server, the name of that event is "GIVE-ME-BADGE".
This should trigger the rule setup for you already on GameSystem, refreshing your player view, you should see they now have a badge 
awarded to them





