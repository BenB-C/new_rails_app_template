# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version: 2.5.1

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## Creating a Rails Application
```
gem install rails
rails new app_name -d postgresql -T
```
## Setting Up Rspec
```
bundle exec rails generate rspec:install
```
## Database initialization
```
rake db:create
rails generate migration create_albums
rake db:migrate
rake db:test:prepare
```
https://guides.rubyonrails.org/v3.2/migrations.html
https://guides.rubyonrails.org/command_line.html#rails-generate

## Running the rails server
```
rails server
rails s
open http://localhost:3000
```
