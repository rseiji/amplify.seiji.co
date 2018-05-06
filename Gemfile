source "https://rubygems.org"
ruby '2.3.3'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem "jekyll", "3.7.3"
gem 'github-pages'

group :jekyll_plugins do
  gem "jekyll-hyphenate_filter"
end
