source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails",            "~> 7.0.3"
gem "sprockets-rails"
gem "puma",             "~> 5.0"
gem "importmap-rails"
gem "webpacker"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "bootsnap", require: false
gem "tzinfo-data"

group :development, :test do
  gem "sqlite3",    "1.4.4"
  gem "byebug",     "11.0.1", platforms: [:mri, :mingw, :x64_mingw]
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
  gem "listen"
  gem "spring"
  gem "spring-watcher-listen"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "rails-controller-testing"
  gem "minitest"
  gem "minitest-reporters"
  gem "guard"
  gem "guard-minitest"
end

group :production do
  gem "pg",   '1.1.4'
end
