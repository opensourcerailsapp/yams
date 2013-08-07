source 'https://rubygems.org'
ruby '1.9.3' # for heroku
gem 'rails', '4.0.0'
gem 'pg'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'therubyracer', '~> 0.11.4', platforms: :ruby
gem 'jquery-rails', '~> 3.0.4'
gem 'jbuilder', '~> 1.2'
gem 'bcrypt-ruby', '~> 3.0.0'


group :development do 
  gem 'thin', '~> 1.5.1'
  gem 'annotate', '~> 2.5.0'
end

group :production do 
  gem 'unicorn', '~> 4.6.3'
  gem 'rails_12factor'
end

group :development, :test do 
  gem 'debugger', '~> 1.6.1'
  gem 'rspec-rails', '~> 2.14.0'
  gem 'ffaker', '~>1.18.0'
end

group :test do 
  gem 'shoulda-matchers', '~> 2.2.0'
end

group :doc do
  gem 'sdoc', '~> 0.3.20', require: false
end
