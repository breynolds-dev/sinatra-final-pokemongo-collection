source 'http://rubygems.org'

gem 'sinatra'
gem 'activerecord', require: 'active_record'
gem 'sinatra-activerecord', require: 'sinatra/activerecord'
gem 'rake'
gem 'require_all'
gem 'thin'
gem 'bcrypt'
gem 'httparty'
gem 'poke-api'
gem 'sinatra-flash'

group :development do
  gem 'sqlite3'
  gem 'tux'
  gem 'pry'
  gem 'pry-byebug'
  gem 'shotgun'
end

group :production do
  gem 'pg'
end

group :test do
  gem 'rspec'
  gem 'capybara'
  gem 'rack-test'
  gem 'database_cleaner', git: 'https://github.com/bmabey/database_cleaner.git'
end
