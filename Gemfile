source 'https://rubygems.org'

ruby '2.1.1'
gem 'rails', '4.0.3'

group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.11.0'
end

# assetsでは使うが、
# 本番環境ではデフォルトで不要なGem
group :assets do
  gem 'sass-rails',   '4.0.1'
  gem 'coffee-rails', '4.0.1'
  gem 'uglifier', '2.1.1'
end

gem 'jquery-rails', '3.0.4'

group :test do
  gem 'capybara', '1.1.2'
end

gem 'therubyracer'
gem 'turbolinks'

group :production do
  gem 'pg', '0.15.1'
	gem 'rails_12factor', '0.0.2'
end

