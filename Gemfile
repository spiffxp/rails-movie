source 'https://rubygems.org'

# rake needs to be before rails for stackato
gem 'rake', '10.1.0'
gem 'rails', '3.2.13'
gem 'nokogiri', '1.6.0'
gem 'thin'
gem 'activeadmin', '0.6.0'
gem 'af', '0.3.18.12'
gem 'bunny', git: 'https://github.com/ruby-amqp/bunny.git'
gem 'ci_reporter', '1.9.0'

gem 'dont_validate', '0.0.1'
gem 'doorkeeper', '0.6.7'
gem 'jquery-rails', '2.2.1'
gem 'whenever', '0.8.4', :require => false

group :assets do
  gem 'coffee-rails', '~> 3.2.1'
  gem 'less-rails'
  gem 'sass-rails',   '~> 3.2.3'
  gem 'therubyracer'
  gem 'twitter-bootstrap-rails'
  gem 'uglifier', '>= 1.0.3'
end

group :demo, :stage, :production do
  gem 'mysql2', '0.3.11'
end

group :test, :development do
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'debugger'
  gem 'guard-rspec'
  gem 'rb-fsevent'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'sqlite3'
  gem 'terminal-notifier-guard'
end

group :test, :development, :demo do
  gem 'factory_girl_rails'
  gem 'forgery'
  gem 'vcr'
end

group :test do
  gem 'launchy'
  gem 'webmock'
end

