source 'https://rubygems.org'

#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.8'
gem 'bootstrap-sass', '3.2.0.1'
gem 'sprockets', '2.11.0'
gem 'bcrypt', '3.1.7'
gem 'faker', '1.4.2'
gem 'will_paginate', '3.0.4'
gem 'bootstrap-will_paginate', '0.0.10'
gem 'sprockets-rails', '~> 2.1.3'

group :development, :test do
  gem 'sqlite3', '1.3.9'
  gem 'rspec-rails', '3.0.2'
  # The following optional lines are part of the advanced setup.
  # gem 'guard-rspec', '2.5.0'
  # gem 'spork-rails', '4.0.0'
  # gem 'guard-spork', '1.5.0'
  # gem 'childprocess', '0.3.6'
end

group :test do
  gem 'selenium-webdriver', '2.42.0'
  gem 'capybara', '2.4.1'
  gem 'factory_girl_rails', '4.4.1'
  gem 'cucumber-rails', '1.4.1', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'

  # Uncomment this line on OS X.
  # gem 'growl', '1.0.3'

  # Uncomment these lines on Linux.
  gem 'libnotify', '0.8.3'

  # Uncomment these lines on Windows.
  # gem 'rb-notifu', '0.0.4'
  # gem 'wdm', '0.1.0'
end

gem 'sass-rails', '4.0.3'
gem 'uglifier', '2.5.3'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.1.1'
gem 'turbolinks', '2.2.2'
gem 'jbuilder', '2.1.3'

group :doc do
  gem 'sdoc', '0.4.0', require: false
end

group :production do
  gem 'pg', '~> 0.17.1'
  gem 'rails_12factor', '0.0.2'
end