source 'https://rubygems.org'

gemspec

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development do
  gem 'rb-fsevent', :require => RUBY_PLATFORM.include?('darwin') && 'rb-fsevent'
  gem 'rb-inotify', :require => RUBY_PLATFORM.include?('linux') && 'rb-inotify'
  gem 'guard'
  gem 'guard-livereload', require: false
  gem 'guard-minitest'
end

group :test do
  gem 'capybara-webkit'
  gem 'launchy'
  gem 'vcr'
  gem 'webmock'
  gem 'sqlite3'
end

group :development, :test do
  gem "better_errors"
  gem "binding_of_caller"
  gem 'thin'
  gem 'pry-rails'
  gem 'capistrano', '~> 3.1', require: false
  gem 'capistrano-rails', '~> 1.1.2', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-rvm', '~> 0.1.2', require: false
end
