source 'https://rubygems.org'

gem 'rails', '4.2.6'
gem 'bootstrap-sass', '2.3.2.0'
gem 'bcrypt'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate', '0.0.9'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails', '~> 3.4'
  # The following optional lines are part of the advanced setup.
  # gem 'guard-rspec'
  gem 'spork-rails'
  # gem 'guard-spork'
  #gem 'childprocess'
  # gem 'spork-rails', '4.0.0'
  # gem 'guard-spork', '1.5.0'
  # gem 'childprocess', '0.3.6'
end

group :test do
  gem 'selenium-webdriver'
  gem 'factory_girl_rails', '4.2.1'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
  gem 'capybara'
  # Uncomment this line on OS X.
  # gem 'growl', '1.0.3'

  # Uncomment these lines on Linux.
  gem 'libnotify'

  # Uncomment these lines on Windows.
  # gem 'rb-notifu', '0.0.4'
  # gem 'win32console', '1.3.2'
  # gem 'wdm', '0.1.0'
end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :doc do
  gem 'sdoc', require: false
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end