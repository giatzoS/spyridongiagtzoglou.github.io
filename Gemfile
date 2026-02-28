source "https://rubygems.org"

gem "jekyll", "~> 4.3"

group :jekyll_plugins do
  gem "jekyll-feed",    "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Required for Jekyll 4 on Ruby 3+
gem "webrick", "~> 1.8"

# Windows / JRuby timezone data
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo",      ">= 1", "< 3"
  gem "tzinfo-data"
end
