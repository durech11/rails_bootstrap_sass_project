# Rails Bootstrap App

## Book Source: Bootstrap for Rails

## Setup
* Add the **bootstrap-sass gem** in the gemfile. `gem 'bootstrap-sass', '~> 3.3', '>= 3.3.6'`. For the latest version, check out [rubygems bootstrap sass page](https://rubygems.org/gems/bootstrap-sass/versions/3.3.6)
* Run `bundle install`
* Generate scaffold `rails g scaffold todos title:string description:text completed:boolean`
* Migrate `rails db:migrate`
* Link **Bootstrap's** `css` and `js` files from **Rails'** default `css` and `js` files. Edit `app/assets/stylesheets/todos.scss` to include bootstrap by adding `@import "bootstrap";`. Edit `app/assets/javascripts/application.js` to include bootstrap by adding `//= require bootstrap`
