source "https://rubygems.org"

ruby "3.2.0"

gem "rails", "~> 7.1.1"
gem "sprockets-rails"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder" 
gem "sqlite3", "~> 1.4"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false
gem 'devise', '~> 4.9', '>= 4.9.3'

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
  gem "sqlite3", "~> 1.4"
end

group :development do
  gem "web-console"
end

group :production do
  gem 'pg', '~> 1.5', '>= 1.5.4'
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
end
gem "dockerfile-rails", ">= 1.5", :group => :development

gem "sentry-ruby", "~> 5.13"

gem "sentry-rails", "~> 5.13"
