source "https://rubygems.org"

# Jekyll for local development (no GitHub Pages dependency)
gem "jekyll", "~> 4.3.0"

# Ruby 3.4+ compatibility fixes
gem "csv"
gem "base64" 
gem "logger"
gem "fiddle"

# Jekyll plugins - minimal set for local development
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows performance booster
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Windows timezone data
platforms :mingw, :x64_mingw, :mswin do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end