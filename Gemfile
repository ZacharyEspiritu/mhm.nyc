source 'https://rubygems.org'
ruby '2.2.2'

gem 'rails', '~> 5.0.0'
gem 'pg'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'

gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'bootstrap-sass', '~> 3.2.0'
gem 'autoprefixer-rails'

gem 'annotate'
gem 'faker'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :production do
  gem 'rails_12factor'
end

group :development, :test do
  gem 'pry'
  gem 'pry-byebug'
  gem 'byebug'
end

group :development do
  gem 'bullet'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'spring'
  gem 'spring-commands-rspec'
end

group :test do
  gem 'rspec-rails', '~> 3.5'
  gem 'factory_girl_rails'
  gem 'simplecov', require: false
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'fuubar'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
