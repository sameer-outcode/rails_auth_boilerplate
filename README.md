# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
   - 3.0.1

* System dependencies

* Configuration

* Database creatin

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# Steps to run the app
* run bundler
  - `bundle install`
* create and migrate db
  - `rails db:create && rails db:migrate`
* run rails server
  - `rails s` 

# For the api documentation
- PLease go through the json file provided at the root folder. That contains detailed information regarding how the uathentication is handled and is an automatd task for operating api.

# how to create controllers
- `rails g controller api/v1/<controller_name>`

# Note 
This is an authentication boilerplate made with rails 6 and ruby 3.0.1 with created with only api flag. This involved handling of authentication of users using devise_token_auth gem and versioning of api.

