source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.7'
gem 'rails', '~> 5.2.1'
gem 'sqlite3'
gem 'puma', '~> 4.3'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'loofah', '~> 2.3', '>= 2.3.1'

# CSS framework based on Flexbox
gem 'bulma-rails', '~> 0.7.5'

# Simple form
gem "simple_form", ">= 5.0.0"


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Live reloading when file system modifications
  gem 'guard', '~> 2.15', '>= 2.15.1'
  # Reloads browser when 'view' files are modified
  gem 'guard-livereload', '~> 2.5', '>= 2.5.2'
  # Make errors better looking
  gem 'better_errors', '~> 2.5', '>= 2.5.1' 
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
