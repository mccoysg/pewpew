source "https://rubygems.org"

gem "rake"
gem "rails", "4.0"
gem "simple_form"
gem "browser_details"
gem "sprockets-rails"

group :assets do
  gem "sass-rails", "4.0.3"
  gem "compass-rails"
  gem "bootstrap-sass"
  gem "coffee-rails"
  gem "uglifier"
end

group :development, :test do
  gem "pry"
  gem "pry-nav"
  gem "pry-stack_explorer"
  gem "pry-vterm_aliases"
  gem "pry-remote"
  gem "sqlite3"
  gem "launchy" # Allows save_and_open_page to work in Capybara.
end

group :development do
  gem "wirb"
  gem "hirb"
  gem "awesome_print"
  gem "capistrano"
  gem "sextant"
  gem "active_sanity"
  gem "quiet_assets"
  gem "rails-erd"
  gem "railroady"
  gem "license_finder"
  gem "better_errors"
  gem "meta_request" # Required by the RailsPanel browser extension.
  gem "rb-fsevent" # Guard file events for OSX.
  gem "guard-rspec"
  gem "rack-livereload"
  gem "guard-livereload"
end

group :test do
  gem "rspec-rails"
end

group :production do
  gem "pg"
end
