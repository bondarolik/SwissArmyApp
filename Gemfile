source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.1"
gem "rails", "~> 7.0.2", ">= 7.0.2.4"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"


# Assets
gem "sprockets-rails"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "requestjs-rails"
gem "view_component"
gem "simple_form"
gem "meta-tags"

# Background jobs
gem "redis", "~> 4.0"
# gem "redis-namespace"
# gem "sidekiq"
# gem "sidekiq-scheduler"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Authentication
gem "bcrypt", "~> 3.1.7"
gem "devise", git: "https://github.com/heartcombo/devise", branch: "main"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
gem "image_processing", "~> 1.2"
gem "mini_magick"

# Utilities
# gem "valid_email2"
# gem 'httparty'
# gem 'active_hash'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "brakeman" # security tests https://github.com/presidentbeef/brakeman
  gem "dotenv-rails"
  gem "rspec-rails", "~> 5.0.0"
  gem "factory_bot"
end

group :development do
  gem "amazing_print"
  gem "foreman"
  gem "letter_opener"
  gem "pry"
  gem "pry-rails"
  gem "better_errors"
  gem "binding_of_caller"
  gem "web-console"
  gem "listen"

  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false
  gem "rubocop-shopify", require: false

  # gem "capistrano", "~> 3.11"
  # gem "capistrano-rails", "~> 1.4"
  # gem "capistrano-rails-console", require: false
  # gem "capistrano-rails-collection"
  # gem "capistrano-passenger", "~> 0.2.0"
  # gem "capistrano-rbenv", "~> 2.1", ">= 2.1.4"
  # gem "capistrano-master-key", "~> 1.0.0"
  # gem "capistrano-sidekiq"  
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]