source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails'
  gem "better_errors"
  gem "binding_of_caller"
end

group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
# group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

# Allow handlebars templates as part of the asset pipeline
gem 'handlebars_assets'

#For Ember.js <-> Rails
gem 'active_model_serializers', github: 'rails-api/active_model_serializers'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', :platforms => :ruby

gem 'uglifier', '>= 1.0.3'
gem 'compass-rails' # you need this or you get an err

# end

# Tag things
gem 'acts-as-taggable-on'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

# OmniAuth, for user authentication
gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-facebook'
gem 'omniauth-linkedin'

# FontAwesome, for awesome iconographic FontAwesome
gem "font-awesome-rails"