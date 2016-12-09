source 'https://rubygems.org'

ruby '2.2.2'

gem 'rails', '4.2.4'
gem 'pg'
gem 'activerecord-postgis-adapter'
gem 'geocoder'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'active_model_serializers', '~> 0.9.3'
gem 'httparty'
gem 'kaminari'
gem 'ejs'

gem 'puma'
gem 'rack-timeout'

group :development, :test do
  gem 'byebug'
  gem 'dotenv-rails'
end

group :development do
  gem 'web-console', '~> 2.0'
  gem 'spring'

  # Deployments
  gem 'capistrano',  '~> 3.4.0'
  gem 'capistrano-rails', '~> 1.1.3'
  gem 'capistrano-rbenv', '~> 2.0'
  gem 'capistrano-passenger', '~> 0.1.1'
end

group :production do
  gem 'rails_12factor'
end