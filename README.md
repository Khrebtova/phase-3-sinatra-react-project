# Phase-3 Project "Bucket list" Backend
This is a backend application for Bucket list app I created for the end of phase-3 at Flatiron school. 
The focus of this project is building a Sinatra API backend that uses Active Record to access and persist data in a database, which will be used by a separate React frontend that interacts with the database via the API.

## Overview
I used Sinatra and Active Record to create models and seed them with starter data needed for my application - Bucket List.
I created 2 models with one-to-many relationship : 
 1. Category (Seeded with Travel, Experience, LifeStyle)
 2. Item (Seeded with starter data, every item belongs to one category)
Set up the server so frontend can send GET, POST, DELETE, PATCH  requests.

## Requirements
* ruby 2.7.4
* sqlite3 3.31.1

## Get started
* Fork and clone this repository into your local environment. Navigate into its directory in the terminal, then run `code .` to open the files in Visual Studio Code.
* Run `bundle install` to set up the dependencies.
* Run `bundle exec rake db:migrate db:seed` to set up and add data to the database.
* Run `bundle exec rake server` to start server
* If you haven't already, follow directions for [Frontend](https://github.com/Khrebtova/phase-3-project-bucket-list)

