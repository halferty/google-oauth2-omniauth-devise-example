source 'https://rubygems.org'

gem 'sqlite3', '~> 1.3.7'
gem 'rake', '~> 10.0.0'
gem 'rails', '~> 3.2.13'
gem 'jquery-rails', '~> 2.3.0'
gem 'rename'

# TeamworkPM API calls
gem 'faraday', '~> 0.8.0'
gem 'faraday_middleware', '~> 0.9.0'

# Auth
gem 'devise', '~> 3.0.0'
gem 'omniauth', '~> 1.1.4'
gem 'omniauth-google-oauth2', '~> 0.2.0'

# Forms
gem 'simple_form', '~> 2.0.1'
gem 'cocoon', '~> 1.2'
gem 'haml', '~> 4.0.3'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'bootstrap-sass', '~> 2.3.0'
  gem 'jquery-datatables-rails', '~> 1.11.2'

  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'brakeman'
  gem 'better_errors'
  gem 'pry-rails'
  gem 'pry-nav'
  gem 'quiet_assets'
  gem 'sextant'
  gem 'thin'
  gem 'xray-rails'
end

# rspec related gems, only required in the test environment
group :rspec do
  gem 'capybara', '~> 2.0.0'
  gem 'rspec-rails', '~> 2.12.0'
  gem 'simplecov', '~> 0.7.1', :require => false
  gem 'simplecov-rcov', '~> 0.2.3', :require => false
  gem 'spork', '~> 1.0.0rc2'
  gem 'webmock', '~> 1.9.0', :require => false
  gem 'rb-fsevent', '~> 0.9.1'
end

# testing tools, not required in any environment
group :testing_tools do
  gem 'ruby_gntp'
  gem 'guard'
  gem 'guard-brakeman'
  gem 'guard-bundler'
  gem 'guard-rspec'
  gem 'guard-spork'
end

# monitoring tools, only required in production
group :monitoring do
  gem 'newrelic_rpm', '~> 3.6.0'
end

