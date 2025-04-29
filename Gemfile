source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in calcdate-ruby.gemspec
gemspec

gem 'rspec', '~> 3.12', require: false
gem 'rake', '~> 13.0', require: false
gem 'standard', '~> 1.3', require: false
gem 'debug'

group :test, :development do
  gem 'pry-byebug', '~> 3.9'
end
