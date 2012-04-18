source 'http://rubygems.org'

gem 'rails', '~> 3.2.2'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

#gem 'pg'
gem 'sqlite3-ruby', :require => 'sqlite3'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug'

gem 'rails3-generators'

gem "bson_ext"
gem "haml"
gem "haml-rails"
gem "jquery-rails"

gem "formtastic"
gem "cocoon"
gem 'client_side_validations', :git => 'https://github.com/bcardarella/client_side_validations.git'
#gem 'client_side_validations', :git => 'https://github.com/pkmiec/client_side_validations.git', :branch => 'nested_attributes'
gem 'client_side_validations-formtastic', :git => "https://github.com/dockyard/client_side_validations-formtastic.git"


# we need this here, see http://blog.davidchelimsky.net/2010/07/11/rspec-rails-2-generators-and-rake-tasks/
group :development, :test do
  gem "rspec-rails", ">= 2.2.0"
  gem "simplecov", :require => false
end

# test-environment gems
group :test, :spec, :cucumber do
  gem "factory_girl_rails"
  gem "rspec",                   ">= 2.2.0"
  gem "remarkable",              ">=4.0.0.alpha2"
  gem "remarkable_activemodel",  ">=4.0.0.alpha2"
  gem "remarkable_activerecord", ">=4.0.0.alpha2"
end
