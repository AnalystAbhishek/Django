# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...
- https://rubygems.org/ to use and install gems and use `bundle install` after adding into gemfile\

`rails s` to start puma server\
`rails g controller home index` to make boiler plate in which we get controller,view,router\
`rails routes` to show all routes\
`rails g scaffold users first_name:string la st_name:string email:string phone:string twit ter:string` to generate database migration CRUD template with rouer\
`rails db:migrate` to generate schemma of migration
