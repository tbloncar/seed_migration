source 'https://rubygems.org'

gemspec

gem "rails", ">= 3.2.17"

case ENV['DB']
when 'postgresql'
  gem 'pg'
when 'mysql'
  gem 'mysql2'
when 'sqlite'
  gem 'sqlite3'
else
  gem 'sqlite3'
end
