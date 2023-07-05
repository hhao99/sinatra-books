# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }
gem 'rake'

# sinatra package
gem 'sinatra'
gem 'sinatra-contrib'
gem 'sinatra-partial'

# use thin as a web server or puma
gem 'thin'

# database driver, sqlite or postgresql

#use ActiveRecord orm 
gem 'activerecord'
gem 'activesupport'

#include ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# test
group :test do
  gem 'shoulda-matchers'
  gem 'rack-test'
  gem 'rspec'
end

group :development, :test do
  gem 'faker'
  gem 'factory_girl'
  gem 'tux'
  gem 'pry'
end

