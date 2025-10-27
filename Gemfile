source 'http://rubygems.org'

gemspec

case version = ENV['MONGOID_VERSION'] || '9.0'
when 'latest'
  gem 'mongoid'
else
  gem 'mongoid', "~> #{version}"
end

case version = ENV['RAILS_VERSION'] || '8.0'
when 'latest'
  gem 'rails'
else
  gem 'rails', "~> #{version}"
end

gem 'logger'
