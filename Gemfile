source "https://rubygems.org"

# Use GitHub Pages gem for GitHub Pages hosting
gem "github-pages", group: :jekyll_plugins

# Plugin for feed generation
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# For Windows compatibility
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows performance boost for file watching
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# For JRuby builds (if you're using JRuby)
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
