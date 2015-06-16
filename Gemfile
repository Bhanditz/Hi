source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

gem 'haml', '~> 4.0.6'

gem 'bootstrap-sass', '~> 3.3.4'

# Timezone fix for Windows 
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development do
  # Added to improve gaurd responsiveness
  gem 'rb-readline', '~> 0.5.2'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'pry-rails', '~> 0.3.3'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-commands-rspec', '~> 1.0.4'
  gem 'spring-commands-teaspoon', '~> 0.0.2'

  # Testing
  gem 'teaspoon', '~> 0.9.0'
  gem 'jasmine-jquery-rails', '~> 1.4.2'
  gem 'rspec-rails', '~> 3.2.0'
end

group :test do
  gem 'fuubar', '~> 2.0.0'
  gem 'fabrication', '~> 2.12.2'
  gem 'database_cleaner', '~> 1.4.0'
  gem 'capybara', '~> 2.4.4'
  gem 'capybara-screenshot', '~> 1.0.5'
  gem 'capybara-email', '~> 2.4.0'
  # depends on phantomjs 1.9.x: brew install phantomjs
  gem 'poltergeist', '~> 1.6.0'
  gem 'selenium-webdriver', '~> 2.44.0'

  # mocking
  gem 'webmock', '~> 1.20.4'
  gem 'vcr', '~> 2.9.3'
  gem 'timecop', '~> 0.7.1'
  gem 'resque_spec', '~> 0.16.0'
  gem 'faker', '~> 1.4.3'

  # CI
  gem 'codeclimate-test-reporter', '~> 0.4.6'

  # TDD
  gem 'guard-rspec', '~> 4.5.0'
  gem 'guard-teaspoon', '~> 0.8.0'
  gem 'guard-minitest', '~> 2.4.4'
  gem 'guard-shell', '~> 0.7.1'
  gem 'rb-fsevent', '~> 0.9.4'
  # Make sure to have Growl and GrowlNotify installed for this to work
  gem 'growl', '~> 1.0.3'
end
