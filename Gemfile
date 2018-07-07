source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

group :development,:test do
  gem 'rspec-rails'
  gem 'rspec-its'
  gem 'simplecov', :require => false
  gem 'guard-rspec'
  #gem 'spork-rails'
  #gem 'guard-spork'
  gem 'childprocess'
  gem 'rails-erd'
  gem 'pry-rails'
  gem 'guard-rails'
  gem 'guard-livereload'
  gem 'guard-bundler'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'launchy'
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.7'
gem 'mysql2'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'bcrypt-ruby'
# Use SCSS for stylesheets
gem 'sass-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
gem 'jquery-turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
gem 'shoulda'
gem 'date_validator'
gem 'foreigner'
gem 'will_paginate'
gem 'will_paginate-bootstrap'
gem 'searchkick'
gem 'money'
gem 'money-rails'
gem 'elasticsearch-model'
gem 'elasticsearch-rails'
gem 'geocoder'
gem 'geo_ip'
gem 'stripe'
gem 'wkhtmltopdf-binary'
gem 'wicked_pdf'
gem 'premailer-rails'
gem 'nokogiri'
gem 'acts_as_votable'
gem 'aws-sdk-v1'
gem 'carrierwave'
#gem 'fog'
gem 'figaro'
gem 'mini_magick'
gem 'responders'
gem 'devise' # User management
gem 'elastic-beanstalk'
gem 'font-awesome-rails' # Font-awesome icon
gem 'mail_form' #Forms, mail
gem 'simple_form' #Forms, mail

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

group :production do
  gem 'pg'
  gem 'rails_12factor'
end