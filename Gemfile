source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.3"
gem 'sassc-rails'
gem "rails", "~> 7.0.2", ">= 7.0.2.3"
gem 'bcrypt', '~> 3.1', '>= 3.1.17'
gem "sprockets-rails"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
gem 'bootstrap-sass', '~> 3.4', '>= 3.4.1'


group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "sqlite3", "~> 1.4"
  gem 'guard', '~> 2.18'
  
end

group :development do
  gem "web-console"
end

group :test do
  gem 'minitest-reporters'
  gem 'minitest'
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem 'rails-controller-testing'
end

group :production do
  gem 'pg', '~> 1.3', '>= 1.3.5'
end
