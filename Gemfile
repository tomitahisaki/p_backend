source "https://rubygems.org"

gem "rails", "~> 7.2.1"
gem "mysql2", "~> 0.5"
gem "puma", ">= 5.0"
# Use Redis adapter to run Action Cable in production
# gem "redis", ">= 4.0.1"
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]
# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false
# gem "rack-cors"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman"
  gem "factory_bot_rails"
  gem "rspec-rails"
  gem "rubocop"
  gem "rubocop-rails-omakase"
  gem "rubocop-performance"
  gem "rubocop-rails"
  gem "rubocop-rspec"
  gem "bullet"
  gem "annotate"
end

group :test do
  gem "simplecov"
  gem "simplecov-cobertura"
end
