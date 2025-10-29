# frozen_string_literal: true

source 'https://rubygems.org'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 8.1.1'

ruby '3.2.0'
# Use sqlite3 as the database for Active Record
gem 'bootsnap', '>= 1.4.4', require: false
gem 'pg', '~> 1.6'
gem 'puma', '>=  6'
gem 'rack-cors'
gem 'sqlite3', '>= 2.1'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'         # Test data creation
  gem 'faker'                     # Realistic test data
  gem 'rspec-rails', '~> 6.0'     # Testing framework
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'rubocop', require: false   # Code quality
  gem 'rubocop-factory_bot', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'rubocop-rspec_rails', require: false
  gem 'spring'
end

group :test do
  gem 'database_cleaner-active_record'
  gem 'shoulda-matchers', '~> 5.0' # Testing helpers
end
