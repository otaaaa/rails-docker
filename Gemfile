source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 5.2.0'
gem 'mysql2', '>= 0.4.4', '< 0.6.0'
gem 'puma', '~> 3.11'
gem 'jbuilder', '~> 2.5'
gem 'redis', '~> 4.0'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'ridgepole', '~> 0.7.2'
gem 'devise', '~> 4.4'

group :development, :test do
  gem 'byebug', '~> 10.0', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry-rails', '~> 0.3.6'
  gem 'pry-byebug', '~> 3.6'
  gem 'pry-coolline', '~> 0.2.5'
  gem 'rubocop', '~> 0.57.2', require: false
  gem 'rspec-rails', '~> 3.7'
  gem 'factory_bot_rails', '~> 4.10'
  gem 'faker', '~> 1.8'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors', '~> 2.4'
  gem 'binding_of_caller', '~> 0.8.0'
end

group :test do
  gem 'simplecov', '~> 0.16.1'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

