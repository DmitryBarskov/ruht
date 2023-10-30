# frozen_string_literal: true

source 'https://rubygems.org'

gemspec

gem 'rake', '~> 13.1'

group :development do
  gem 'rubocop', require: false
  gem 'rubocop-rake', require: false
  gem 'rubocop-rspec', require: false

  gem 'steep', require: false
  gem 'typeprof', require: false
end

group :test do
  gem 'rspec', '~> 3.0'
end

group :development, :test do
  gem 'byebug'
end
