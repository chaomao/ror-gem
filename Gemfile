source 'https://ruby.taobao.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '< 5.1'
gem 'mysql2'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.0'
# Use Redis adapter to run Action Cable in production
gem 'redis'
gem 'sidekiq'
gem 'mini_magick'
gem 'active_model_serializers'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

#Omniauth
gem 'devise_token_auth', github:"lynndylanhurley/devise_token_auth", branch: "master"
gem 'devise', '~> 4.0.1'

gem 'omniauth-qq-connect'
gem 'omniauth-weibo-oauth2'

# upload file
gem 'carrierwave-qiniu', '~> 0.2.3'
gem 'carrierwave', '~> 0.11.2'
gem 'qiniu'

# lock nokogiri
gem 'nokogiri', '1.6.8'

# api doc
gem 'apipie-rails'

group :development, :test do
  gem 'annotate'
  gem 'awesome_print'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'pry'
  gem 'pry-nav'
  gem 'rspec-rails', '~> 3.5', '>= 3.5.1'
  gem 'rspec', '~> 3.5'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
end

group :test do
  gem 'fakeredis'
end

group :development do
  gem 'thin'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'unicorn'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
