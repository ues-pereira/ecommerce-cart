source "https://rubygems.org"

ruby "3.3.1"
gem "rails", "~> 7.1.3", ">= 7.1.3.2"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false
gem 'active_model_serializers'
gem 'redis', '~> 5.2'
gem 'sidekiq', '~> 7.2', '>= 7.2.4'
gem 'sidekiq-scheduler', '~> 5.0', '>= 5.0.3'
gem 'guard'
gem 'guard-livereload', require: false
gem 'whenever', require: false



group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
  gem 'rspec-rails', '~> 6.1.0'
  gem 'factory_bot_rails'
  gem 'pry-rails'
end

group :test do
  gem 'database_cleaner-active_record'
end

group :development do
end
