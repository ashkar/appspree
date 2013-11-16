source 'https://rubygems.org'

ruby '1.9.3'
gem 'rails', '3.2.14'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :development, :test do

	gem 'sqlite3', '1.3.5'
	#gem 'rspec-rails', '2.10.0'
end
group :production do
	gem 'pg', '0.12.2'
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

gem 'jquery-rails','~> 2.2.0'
gem 'rails_12factor', group: :production

gem 'spree', :github => "spree/spree", :branch => "1-3-stable"
gem 'spree_auth_devise', :github => "spree/spree_auth_devise", :branch => "1-3-stable"
gem 'spree_fancy', :github => "spree/spree_fancy", :branch => "1-3-stable"
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
