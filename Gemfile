source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'
gem 'capistrano-ext'

# To use debugger
# gem 'debugger'

gem 'umn_bootstrap_rails', :git => 'git@github.umn.edu:oir/umn_bootstrap_rails'

# Testing
group :development, :test do
  gem 'rspec-rails', '~> 2.0'
  gem 'capybara'
  gem 'factory_girl_rails'
end

gem "spreadsheet", "~> 0.8.5"
gem "formtastic-bootstrap"

# Oracle gems
gem 'ruby-oci8'
gem 'activerecord-oracle_enhanced-adapter'

# Other useful gems
gem 'will_paginate'

#temporariy for rspec Testing
group :test do
	gem 'sqlite3'
	gem 'database_cleaner', '1.0.1'
end