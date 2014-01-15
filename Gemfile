source 'https://rubygems.org'
ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

group :production do 
	gem 'rails_12factor'
	gem 'thin'
	gem 'pg'
end

group :development, :test do
  gem "sqlite3-ruby", "~> 1.3.0", :require => "sqlite3"
end

gem 'spree', '2.1.3'
gem 'spree_gateway', :git => 'https://github.com/spree/spree_gateway.git', :branch => '2-1-stable'
gem 'spree_auth_devise', :git => 'https://github.com/spree/spree_auth_devise.git', :branch => '2-1-stable'

gem 'spree_static_content', :github => 'spree/spree_static_content', :branch => '2-1-stable'
gem 'spree_active_shipping', :git => "git://github.com/spree/spree_active_shipping", :branch => "2-1-stable"
gem "spree_comments", github: 'spree/spree_comments', :branch => '2-1-stable'
gem 'spree_related_products', :git => 'git://github.com/spree/spree_related_products.git', :branch => '2-1-stable'
gem 'spree_paypal_express', :github => "radar/better_spree_paypal_express", :branch => "2-1-stable"
gem "spree_social", :git => "git://github.com/spree/spree_social.git", :branch => '2-1-stable'
gem 'spree_reviews', github: 'spree/spree_reviews', :branch => '2-1-stable'
gem 'spree_digital', :git => 'git://github.com/halo/spree_digital.git', :branch => '2-1-stable'
gem 'spree_store_credits', :git => 'https://github.com/spree/spree_store_credits.git', :branch => '2-1-stable'

gem 'spree_fancy', :git => 'https://github.com/wag0325/spree_fancy.git', :branch => '2-1-stable'