source "https://rubygems.org" # source "https://gems.ruby-china.com"

gemspec

# Using Jekyll 4.x directly to allow for a newer version of Liquid
# compatible with Ruby 3.2+
gem "jekyll", "~> 4.3.0"
gem "liquid", "~> 4.0.4" # Require Liquid >= 4.0.4 but < 5.0 to fix tainted? bug for Ruby 3.2+

# Common plugins that were previously included by github-pages
gem "jekyll-feed", "~> 0.15"
gem "jekyll-seo-tag", "~> 2.6"
gem "jekyll-sitemap", "~> 1.4"
gem "jemoji", "~> 0.12"
gem "jekyll-mentions", "~> 1.6"
gem "jekyll-avatar", "~> 0.7"
gem "jekyll-gist", "~> 1.5"
# kramdown-parser-gfm is often needed for GitHub Flavored Markdown, alternative to jekyll-commonmark-ghpages
gem "kramdown-parser-gfm", "~> 1.1"

# Additional plugins often included with github-pages
gem "jekyll-coffeescript", "~> 1.1"
gem "jekyll-default-layout", "~> 0.1.4"
gem "jekyll-github-metadata", "~> 2.13"
gem "jekyll-optional-front-matter", "~> 0.3.2"
gem "jekyll-readme-index", "~> 0.3.0"
gem "jekyll-relative-links", "~> 0.6.1"
gem "jekyll-titles-from-headings", "~> 0.5.3"

gem "webrick", "~> 1.8" # Required for jekyll serve in Ruby 3+
