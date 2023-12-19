# Blood Alley Tours API

## What is it?

The project was built for Blood Alley Tours, a new company offering walking tours in the Gastown neighbourhood of Vancouver, British Columbia. They requested for a simply designed booking site.

It was bootstrapped with [rails new blood_alley_tours_api](https://guides.rubyonrails.org/getting_started.html) and the front end is built on a seperate repository called "[blood_alley_tours](https://github.com/ryo-soren/blood_alley_tours)". 

The two projects are to be run at the same time.

## What does it do?

The site has the ability for potential customers to both book and pay for a walking tour, as well as reaching out to the Blood Alley Tours team for any general inquiries. Upon booking, customers get an email with the details of their booking.

## Notable Features

* Active-Mailer gem is being used to handle email communication with customers, on all new booking as well as for general inquiries
* Ensured protection of user's payment information using Ruby on Rails environment variables 

## How is it build?

* Back-End: Ruby on Rails API, Active-Mailer
* Database: PostgreSQL
* Dependencies: 
  * gem "pg", "~> 1.1"
  * gem "bcrypt", "~> 3.1.7"
  * gem 'active_model_serializers', '~> 0.10.2'
  * gem 'rack-cors'
  * gem 'stripe'
  * gem "letter_opener"

## Clone the repository

Follow the steps in [this link](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) to clone the repository

## Set up the project for development

### `bundle install`

Installs all dependencies required for the project's full functionality

### `rails s`

Runs the app in the development mode.
Open [http://localhost:3300](http://localhost:3300) to view it in your browser.