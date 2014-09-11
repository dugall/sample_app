source 'https://rubygems.org'
ruby '2.0.0'
gem 'rails', '4.0.0'
gem "bootstrap-sass", "~> 3.1.1.0"
gem 'bcrypt-ruby', '~> 3.0.0'

group :development, :test do
   gem 'sqlite3', '1.3.9'
   gem 'rspec-rails', '2.13.1'
   gem 'guard-rspec', '2.5.0'
   gem 'spork-rails', '4.0.0'
   gem 'guard-spork', '1.5.0'
   gem 'childprocess', '0.5.3'

end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'factory_girl_rails', '4.2.1'
  gem 'cucumber-rails', '1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

gem 'sass-rails', '4.0.2'
gem 'uglifier', '2.5.0'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '2.2.1'
gem 'jbuilder', '1.5.3'

group :doc do
  gem 'sdoc', '0.4.0', require: false
end

group :production do
	gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end