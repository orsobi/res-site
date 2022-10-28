source("https://rubygems.org")
gem("jekyll", "~> 4.2.2")
gem("minima", "~> 2.5")

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
group(:jekyll_plugins) do
  gem("jekyll-feed", "~> 0.12")
end

platforms(:mingw, :x64_mingw, :mswin, :jruby) do
  gem("tzinfo", "~> 1.2")
  gem("tzinfo-data")
end

gem("wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin])
gem("http_parser.rb", "~> 0.6.0", :platforms => [:jruby])
gem("webrick")
gem("execjs", "= 2.7")
