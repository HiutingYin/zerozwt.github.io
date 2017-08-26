source "https://rubygems.org"
# gemspec
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

gem 'jekyll', versions['jekyll']

group :jekyll_plugins do
gem "jekyll-seo-tag", versions['jekyll-seo-tag']
gem "jekyll-paginate", versions['jekyll-paginate']
gem "jekyll-feed", versions['jekyll-feed']
end