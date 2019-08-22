source "https://rubygems.org"

gem "github-pages"
gem "html-proofer"
gem "nokogiri", ">= 1.10.4"
gem "minima"

group :jekyll_plugins do
  gem "jekyll-coffeescript"
  gem "jekyll-gist"
  gem "jekyll-github-metadata"
  gem "jekyll-paginate"
  gem "jekyll-relative-links"
  gem "jekyll-optional-front-matter"
  gem "jekyll-readme-index"
  gem "jekyll-default-layout"
  gem "jekyll-titles-from-headings"
  gem "jekyll-feed"
  gem "jekyll-redirect-from"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-avatar"
  gem "jemoji"
  gem "jekyll-mentions"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
