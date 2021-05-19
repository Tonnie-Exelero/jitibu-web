source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.7'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.4'
# Use Puma as the app server
gem 'puma', '~> 4.3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
gem 'jbuilder', '2.9.1'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

gem 'pg', '1.1.4'
gem 'uglifier', '4.2.0'
gem 'coffee-rails', '5.0.0'
gem 'jquery-rails', '4.3.5'
# gem 'unicorn', '5.5.1'
gem 'will_paginate', '3.2.1'
gem 'will_paginate-bootstrap', '1.0.2'
gem 'devise', '4.7.1'
gem 'cancancan', '3.0.1'
gem 'jwt', '2.2.1'
gem 'omniauth-facebook', '5.0.0'
gem 'authbuttons-rails', '0.1.2'
gem 'font-awesome-rails', '4.7.0.5'
gem 'validates_formatting_of', '0.9.0'
gem 'graphql', '1.9.15'
gem 'exponent-server-sdk', '0.0.7'
gem 'bootstrap-datepicker-rails', '1.8.0.1'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rb-readline', '0.5.5'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

# Gems for Production environment
group :production do
  # Serve static assets from Heroku
  gem 'rails_12factor'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'graphiql-rails', group: :development
