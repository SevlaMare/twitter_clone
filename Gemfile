source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# core
ruby '~> 2.6'
gem 'rails', '~> 5.2'
gem 'sqlite3'
gem 'puma', '~> 3.11'

# generators
gem 'devise', '~> 4.7', '>= 4.7.1'
gem 'simple_form', '~> 5.0', '>= 5.0.2'
gem 'gravatar_image_tag', '~> 1.2'

# assets
gem 'bulma-rails', '~> 0.8.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'

# cache
gem 'turbolinks', '~> 5'
gem 'bootsnap', '>= 1.1.0', require: false

# group :development, :test do
#   gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
#   gem 'selenium-webdriver'
#   # gem 'capybara', '>= 2.15'
#   # gem 'chromedriver-helper'
# end

# group :development do
#   gem 'rubocop'
#   gem 'rspec-rails', ">= 3.9.0"
#   gem 'web-console', '>= 3.3.0'
#   gem 'listen', '>= 3.0.5', '< 3.2'
#   gem 'spring'
#   gem 'spring-watcher-listen', '~> 2.0.0'
# end

group :production do
  gem 'pg'
end

# Windows compatible
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]