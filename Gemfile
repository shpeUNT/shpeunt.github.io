# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 4.2.2"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo"
  gem "tzinfo-data"
end

gem "listen", "~> 3.8"
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# Needed for Ruby 3.4 (no longer included by default)
gem "csv"
gem "base64"
gem "bigdecimal"

gem "webrick"
gem "jekyll-sass-converter"
gem "faraday-retry"
gem "eventmachine"
