source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end



gem 'rails',                   '5.1.4' # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'sqlite3',                 '1.3.13' # Use sqlite3 as the database for Active Record
gem 'puma',                    '3.10.0' # Use Puma as the app server
gem 'sass-rails',              '5.0.6' # Use SCSS for stylesheets
gem 'uglifier',                '3.2.0' # Use Uglifier as compressor for JavaScript assets
# gem 'therubyracer',          '>= 0', platforms: :ruby # See https://github.com/rails/execjs#readme for more supported runtimes
gem 'coffee-rails',            '4.2.2' # Use CoffeeScript for .coffee assets and views
gem 'turbolinks',              '5.0.1' # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'jbuilder',                '2.7.0' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'redis',                 '~> 3.0' # Use Redis adapter to run Action Cable in production
# gem 'bcrypt',                '~> 3.1.7' # Use ActiveModel has_secure_password
# gem 'capistrano-rails',      '>= 0', group: :development # Use Capistrano for deployment

group :development, :test do
  gem 'byebug',                '9.1.0', platforms: [:mri, :mingw, :x64_mingw] # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'capybara',              '2.15.4' # Adds support for Capybara system testing and selenium driver
  gem 'selenium-webdriver',    '3.6.0'
end

group :development do
  gem 'web-console',           '3.5.1' # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.0.2' # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '2.0.1'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
