source 'http://rubygems.org'

ruby '2.2.2'
gem 'rails', '4.2.1'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
  gem 'cucumber-rails', :require => false
  gem 'rspec-rails', '>= 2.0.0.beta.22'
  gem 'capybara'
  gem "cucumber-rails-training-wheels"
  gem 'database_cleaner'
end


group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
# Upgrading to Rails 4
#group :assets do
  gem 'therubyracer'              
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
#end

gem 'protected_attributes'
gem 'jquery-rails'
gem 'haml'

gem 'activeresource'
gem 'ZenTest'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'
