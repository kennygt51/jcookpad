source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.1.0'
# Use sqlite3 as the database for Active Record
# gem 'sqlite3', '~> 1.4'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'mysql2'
gem 'gon', '~> 6.2.0'
gem "jquery-rails"
gem 'kaminari'

#for debug
gem 'pry-rails'
# Use Active Storage variant
# gem 'image_processing', '~> 1.2'
#active admin
gem 'activeadmin'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false
gem 'chart-js-rails', '~> 0.1.4' 
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'sqlite3'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'listen', '~> 3.3'
  gem 'rack-mini-profiler', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'rubocop', require: false
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'rubocop-rubycw'
  gem 'spring'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem "factory_bot_rails"
  gem 'faker'
  gem 'rspec-rails'
end



#Devise
gem 'devise'
gem 'omniauth-twitter'
#image
gem 'carrierwave'
gem 'mini_magick'


group :production do
  gem 'pg', '~> 0.18'
end
