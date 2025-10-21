source "https://rubygems.org"

# Jekyll
gem "jekyll", "~> 4.3"

# Plugins
group :jekyll_plugins do
  gem "jekyll-archives"
  gem "jekyll-email-protect"
  gem "jekyll-feed"
  gem "jekyll-get-json"
  gem "jekyll-imagemagick"
  gem "jekyll-jupyter-notebook"
  gem "jekyll-link-attributes"
  gem "jekyll-minifier"
  gem "jekyll-paginate-v2"
  gem "jekyll-regex-replace"
  gem "jekyll-remote-theme"
  gem "jekyll-scholar"
  gem "jekyll-sitemap"
  gem "jekyll-toc"
  gem "jekyll-twitter-plugin"
  gem "jemoji"
end

# Windows and JRuby does not include zoneinfo files
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Webrick for Ruby 3.0+
gem "webrick", "~> 1.8"
