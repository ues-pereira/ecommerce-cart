# frozen_string_literal: true

source 'https://rubygems.org'

ruby '3.3.1'
gem 'active_model_serializers'
gem 'bootsnap', require: false
gem 'guard'
gem 'guard-livereload', require: false
gem 'pg', '~> 1.1'
gem 'puma', '>= 5.0'
gem 'rails', '~> 7.1.3', '>= 7.1.3.2'
gem 'redis', '~> 5.2'
gem 'sidekiq', '~> 7.2', '>= 7.2.4'
gem 'sidekiq-scheduler', '~> 5.0', '>= 5.0.3'
gem 'tzinfo-data', platforms: %i[windows jruby]
gem 'whenever', require: false
gem "sidekiq-cron"

group :development, :test do
  gem 'debug', platforms: %i[mri windows]
  gem 'factory_bot_rails'
  gem 'pry-rails'
  gem 'rspec-rails', '~> 6.1.0'
  gem 'rubocop-rails-omakase', require: false
end

group :test do
  gem 'database_cleaner-active_record'
end

group :development do
end
