source "https://rubygems.org"

gem "rails", "4.1.1"

gem "email_signup", path: "components/email_signup"
gem "event_counter", path: "components/event_counter"
gem "teaser", path: "components/teaser"
gem "annoyance", :path => "components/annoyance"

group :test, :development do
  gem "rspec-rails", "2.14"
  gem "capybara", "2.1.0"
  gem "sqlite3", "1.3.9"
end

group :production do
  gem "pg"
end