source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :production, :staging do
# gem 'therubyracer-heroku', '0.8.1.pre3' # you will need this too
  gem 'pg'
end
  
group :development do
    gem 'sqlite3'
    gem 'rspec-rails'
    gem 'annotate'
end

group :test do
    gem 'rspec-rails'
    gem 'webrat'
    gem 'factory_girl_rails'
    gem 'spork'
    gem 'rspec'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'execjs'

gem 'therubyracer'
gem 'jquery-rails'


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
gem 'spree', '1.3.2'
gem 'spree_gateway', :git => 'https://github.com/spree/spree_gateway', :branch => '1-3-stable'
gem 'spree_auth_devise', :git => 'https://github.com/spree/spree_auth_devise', :branch => '1-3-stable'
gem 'spree_i18n', :git => 'https://github.com/spree/spree_i18n.git'