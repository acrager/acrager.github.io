# Specify the source for Ruby gems
source "https://rubygems.org"

# # Jekyll version
# gem "jekyll", "~> 4.3.4"

# GitHub Pages (includes themes and plugins)
gem "github-pages", group: :jekyll_plugins

# # Theme and Plugins
# gem "minima", "~> 2.5" # Default theme
# group :jekyll_plugins do
#   gem "jekyll-feed", "~> 0.12" # RSS feed generator
# end

# Platform-specific dependencies
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data" # Timezone data for Windows
end

platforms :mingw, :x64_mingw, :mswin do
  gem "wdm", "~> 0.1" # File watching optimization for Windows
end

platforms :jruby do
  gem "http_parser.rb", "~> 0.6.0" # Locked version for JRuby compatibility
end

# Additional dependencies
gem "csv" # CSV file support
gem "base64" # Base64 encoding and decoding
gem "faraday-retry" # Faraday middleware for retries