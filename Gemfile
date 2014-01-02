source 'https://rubygems.org'

ruby '2.0.0'

	
gem 'rails', '4.0.2'
gem 'jquery-rails'
gem 'devise'
gem 'simple_form'


group :production do
	gem 'pg'
end

gem 'quiet_assets', :group => :development

group :development do
  gem 'rails_layout'
end

group :development, :test do
	gem 'sqlite3'
end 

group :assets do
	gem 'sass-rails', '>= 3.2' 
	gem 'coffee-rails', '~> 4.0.0'
	gem 'uglifier', '>= 1.3.0'
	gem 'bootstrap-sass', '~> 3.0.3.0'
	gem 'turbolinks'
	gem 'jbuilder', '~> 1.2'
	gem 'rails_12factor'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
