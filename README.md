# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


- Users - create users table and model

    - add validations
    * username must be present and unique, min 3 max 25
    * email address must be present and inique, max 105
    * emial must be valid email format, check with email regex