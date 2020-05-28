source 'https://rubygems.org'

gem 'dotenv'

gem 'factory_bot'

# Enable non-transactional database cleaning in tests which require a shared DB connection
gem 'database_cleaner'

# Some nice rails helpers
gem 'activesupport'

# Tasks
gem 'rake'

# Database
gem 'mysql2'

# Newrelic
gem 'newrelic_rpm'

# Web DSL
gem 'sinatra', '~> 2', require: 'sinatra/base'
gem 'sinatra-activerecord'
gem 'sinatra-contrib'

# Crons
gem 'whenever', require: false

group :development do
  # Debugger
  gem 'byebug'

  # Better console
  gem 'pry'
  gem 'pry-byebug'

  # Reloads on changes
  gem 'rerun'

  # Web server
  gem 'thin'
end


group :test do
  gem 'mocha'
  gem 'shoulda-context'
  gem 'shoulda-matchers', git: 'https://github.com/thoughtbot/shoulda-matchers', branch: 'master'
end
