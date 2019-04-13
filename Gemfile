# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'

gem 'bootsnap', '~> 1.4.3', require: false
gem 'figaro', '~> 1.1.1'
gem 'pg', '~> 1.1.4'
gem 'puma', '~> 3.12.1'
gem 'rack-cors', '~> 1.0.3'
gem 'rails', '~> 5.2.3'

group :development, :test do
  gem 'factory_bot_rails', '~> 5.0.1'
  gem 'pry', '~> 0.12.2'
  gem 'rspec-rails', '~> 3.8.2'
  gem 'rubocop', '~> 0.67.2', require: false
  gem 'rubocop-rspec', '~> 1.32.0'
end

group :development do
  gem 'letter_opener', '~> 1.7.0'
  gem 'listen', '~> 3.1.5'
  gem 'spring', '~> 2.0.2'
  gem 'spring-watcher-listen', '~> 2.0.1'
end

group :test do
  gem 'faker', '~> 1.9.3'
  gem 'shoulda-matchers', '~> 4.0.1'
  gem 'simplecov', '~> 0.16.1', require: false
end
