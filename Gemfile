# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.2', '>= 6.0.2.1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Use bulma.io as framework
gem 'bulma-extensions-rails'
gem 'bulma-rails', '~> 0.8.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Provides the Font-Awesome web fonts and stylesheets as a Rails engine for use
# with the asset pipeline.
gem 'font-awesome-rails'
# This gem helps you to add this fantastic icon collection.
gem 'material_icons'
# Haml is a templating engine for HTML.
gem 'haml', '~> 5.0', '>= 5.0.4'
# Tool for writing clean and consistent HAML
gem 'haml-lint', '~> 0.999.999'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster.
# Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Simple, efficient background processing for Ruby
gem 'sidekiq'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
# Flexible authentication solution for Rails with Warden.
gem 'devise'
# Whenever is a Ruby gem that provides a clear syntax for writing and deploying
# cron jobs.
gem 'whenever', require: false
# Ruby gem for reporting errors to honeybadger.io
gem 'honeybadger', '~> 4.0'
# This gem provides a simple and extremely flexible way to upload files from
# Ruby applications. It works well with Rack based web applications, such as
# Ruby on Rails.
gem 'carrierwave', '~> 2.0'
# A ruby wrapper for ImageMagick or GraphicsMagick command line.
gem 'mini_magick'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# Use Active Storage variant
# gem 'image_processing', '~> 1.2'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false
# RouteTranslator is a gem to allow you to manage the translations of your app
# routes with a simple dictionary format.
gem 'route_translator'
# Customizable and sophisticated paginator for modern web app frameworks.
gem 'kaminari'
# A set of common locale data and translations to internationalize and/or
# localize your Rails applications.
gem 'rails-i18n', '~> 6.0.0'
# The travis gem includes both a command line client and a Ruby library to
# interface with a Travis CI service. 
gem 'travis', '~> 1.8', '>= 1.8.8'
gem 'travis-lint', '~> 2.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger
  # console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  # Great Ruby dubugging companion: pretty print Ruby objects to visualize their
  # structure. Supports custom object formatting via plugins
  gem 'awesome_print', require: 'ap'
  # Great Ruby dubugging companion: pretty print Ruby objects to visualize their
  # structure. Supports custom object formatting via plugins
  # gem 'awesome_print', require: 'ap'
  # Provides a better error page for Rails and other Rack apps.
  gem 'better_errors', '~> 2.1', '>= 2.1.1'
  # Retrieve the binding of a method's caller. Can also retrieve bindings even
  # further up the stack.
  gem 'binding_of_caller', '~> 0.7.2'
  # Brakeman is a static analysis tool which checks Ruby on Rails applications
  # for security vulnerabilities.
  gem 'brakeman'
  # Autoload dotenv in Rails.
  gem 'dotenv-rails'
  # Provides a framework and DSL for defining and using factories - less
  # error-prone, more explicit, and all-around easier to work with than fixtures
  gem 'factory_bot'
  # Automatically run your specs
  gem 'guard-rspec'
  # Automatically checks Ruby code style with RuboCop when files are modified.
  gem 'guard-rubocop'
  # Ruby Critic is a tool that listens to modifications in Ruby classes,
  # modules and methods and reports any new code smells it finds.
  gem 'guard-rubycritic'
  # Irbtools make Ruby's IRB more productive.
  gem 'irbtools', require: 'irbtools/binding'
  # When mail is sent from your application, Letter Opener will open a preview
  # in the browser instead of sending.
  gem 'letter_opener'
  # Listens to file modifications and notifies you about the changes.
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Use Pry as your rails console
  gem 'pry-rails', group: :development
  # Profiling toolkit for Rack applications with Rails integration.
  # Client Side profiling, DB profiling and Server profiling.
  # gem 'rack-mini-profiler'
  # Rails performance tests (removed from core in Rails 4.0)
  gem 'rails-perftest'
  # RSpec testing framework to Ruby on Rails as a drop-in alternative to its
  # default testing framework, Minitest.
  gem 'rspec-rails', '~> 3.4', '>= 3.4.2'
  # Automatic Ruby code style checking tool. Aims to enforce the
  # community-driven Ruby Style Guide.
  gem 'rubocop', require: false
  # An extension of RuboCop focused on code performance checks.
  gem 'rubocop-performance'
  # Is a fast code profiler for Ruby
  gem 'ruby-prof'
  # Making tests easy on the fingers and eyes
  gem 'shoulda-matchers'
  # Code coverage for Ruby 1.9+ with a powerful configuration library and
  # automatic merging of coverage across test suites
  gem 'simplecov', require: false, group: :test
  # For memory profiling
  gem 'memory_profiler'
  # For call-stack profiling flamegraphs
  gem 'flamegraph'
  # Is a fast sampling profiler for ruby code, with cpu, wallclock and object
  # allocation samplers.
  gem 'stackprof'
  # A debugging tool for your Ruby on Rails applications.
  gem 'web-console', '>= 3.3.0'
  # Capistrano is a framework for building automated deployment scripts.
  gem 'capistrano', '~> 3.12'
  gem 'capistrano-rails', '~> 1.1', '>= 1.1.7'
  # This gem provides idiomatic rbenv support for Capistrano 3.x (and 3.x only).
  gem 'capistrano-rbenv', '~> 2.1', '>= 2.1.6'
  # Spring speeds up development by keeping your application running in the
  # background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end
