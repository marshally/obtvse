source 'https://rubygems.org'

gem 'rails', '~> 3'

gem 'jquery-rails', '~> 2'
gem 'stringex', '~> 1', :git => 'git://github.com/rsl/stringex.git'
gem 'redcarpet'
gem 'pygments.rb'
gem 'language_sniffer', :git => 'https://github.com/grosser/language_sniffer.git'
gem 'kaminari', '~> 0.13'
gem 'paperclip', '~> 3.0'
gem 'slim'
gem 'sorcery'
gem 'bcrypt-ruby', '~> 3', require: 'bcrypt'

group :production do
  gem 'pg', '~> 0.13'
  gem 'aws-sdk', '~> 1.3.4'
end

group :development, :test do
  gem 'sqlite3', '~> 1', platform: [:ruby, :mswin, :mingw]
  gem 'capistrano'
end

group :assets do
  gem 'sass-rails', '~> 3'
  gem 'coffee-rails', '~> 3'
  gem 'uglifier', '~> 1'
end
