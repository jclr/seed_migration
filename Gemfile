source "https://rubygems.org"

gemspec

gem "rails", ">= 6.0.0"
gem "rack", ">= 1.4.5"

case ENV["DB"]
when "postgresql"
  gem "pg"
when "mysql"
  gem "mysql2"
when "sqlite"
  gem "sqlite3"
else
  gem "sqlite3"
end
