source 'https://rubygems.org'



ruby '2.3.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '7.0.8.1'
#gem 'rails', '4.2.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0', '>= 5.0.8'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'haml'

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.1.0'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '>= 2.5.4'

gem 'jquery-turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
group :doc do
  gem 'sdoc', '~> 1.0.0'
end

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

gem 'devise', '~> 4.7.0'
gem 'devise_invitable', '~> 2.0.9'

gem 'figaro'

gem 'will_paginate'
gem 'bootstrap-will_paginate'

# gem 'ajax_pagination'

## Authorization gem
gem "pundit"

gem 'pusher'

gem 'js_cookie_rails', '>= 2.1.2'

# gem 'nokogiri', '~> 1.6', '>= 1.6.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'active_record-acts_as'

gem 'delayed_job_active_record'

gem 'json'
gem 'rest-client'

gem 'cocoon'

# later we can strict the faker
# to staging && development
gem 'ffaker'
gem 'faker'

gem 'ransack', '>= 1.8.0'

gem 'mailgun_rails', '>= 0.9.0'

group :development do
  gem 'haml-rails', '>= 1.0.0'
  gem 'bullet'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.3', '>= 2.3.0'
end

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # RSPEC testing
  gem 'rspec-rails', '~> 3.5', '>= 3.5.0'

  # Factory girl to add factories
  gem 'factory_girl_rails', '~> 4.6', '>= 4.6.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'jasmine', '>= 2.5.0'
  gem 'jasmine-jquery-rails'
end

group :test do
  gem 'cucumber-rails', '>= 1.4.3', :require => false
  gem 'database_cleaner'
  gem 'shoulda-matchers', git: 'https://github.com/thoughtbot/shoulda-matchers', require: false
  gem 'email_spec'
  gem 'poltergeist', '>= 1.9.0'
  gem 'codeclimate-test-reporter'
  gem 'launchy'
  gem 'selenium-webdriver' # Enables running cuke tests with browser (see env.rb)
  gem 'webmock'
end

gem 'airbrake', '~> 5.4'
group :production do
  # Use Postgres as the database for Active Record
  gem 'pg'
  gem 'rails_12factor'
  gem 'puma', '>= 2.12.0'
end
