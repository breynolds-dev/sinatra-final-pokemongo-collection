source 'http://rubygems.org'

gem 'sinatra'
gem 'activerecord', require: 'active_record'
gem 'sinatra-activerecord', require: 'sinatra/activerecord'
gem 'rake'
gem 'require_all'
gem 'sqlite3'
gem 'thin'
gem 'shotgun'
gem 'pry'
gem 'bcrypt'
gem 'tux'
gem 'httparty'
gem 'poke-api'
gem 'sinatra-flash'

group :test do
  gem 'rspec'
  gem 'capybara'
  gem 'rack-test'
  gem 'database_cleaner', git: 'https://github.com/bmabey/database_cleaner.git'
end

# Tells heroku to use postgreSQL in production/live
group :production do
  gem 'pg'
end
