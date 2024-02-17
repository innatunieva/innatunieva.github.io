source "https://rubygems.org"
gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end
install_if -> { ENV["GITHUB_ACTIONS"] != "true" } do
    puts "Is GitHub action: #{ENV["GITHUB_ACTIONS"] == "true"}"
    gem "webrick", "~> 1.8"
end
