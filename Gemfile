source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.1"

gem "rails", "~> 7.0.3"

gem 'devise'
gem 'devise-i18n'
gem 'rails-i18n'

gem 'font-awesome-rails'

gem 'rails_admin', '~> 3.0'

gem "sprockets-rails"

gem "puma", "~> 5.0"

gem "jsbundling-rails"

gem "turbo-rails"

gem "stimulus-rails"

gem "cssbundling-rails"

gem "jbuilder"

gem "bootsnap", require: false

gem "sassc-rails"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "sqlite3", "~> 1.4"
  gem 'rspec-rails'
  gem 'factory_bot_rails', '~> 6.2'
  gem 'shoulda-matchers'
  gem 'rails-controller-testing'

  # Гем, который позволяет смотреть, что видит capybara
  gem 'launchy'
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem 'launchy'
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :production do
  # гем, улучшающий вывод логов на Heroku
  # https://devcenter.heroku.com/articles/getting-started-with-rails4#heroku-gems
  gem 'rails_12factor', '~> 0.0.3'
  gem 'pg'
end
