source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "4.3.1"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "2.5"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end


# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
gem "jekyll-remote-theme" 
gem "webrick", "~> 1.7"
gem "csv"
gem "base64"
gem "bigdecimal"
gem "jemoji"
gem "fiddle"
gem "jekyll-seo-tag"
gem 'wdm', '>= 0.1.0'
gem "kramdown-parser-gfm", "~> 1.1"

# By default, Jekyll uses an older SASS converter. Without this line, Jekyll will
# default to DART which will warn about deprecated issues see:
# https://github.com/jekyll/minima/pull/705#issuecomment-1387157504
# Force the use of Jekyll's SASS converter
gem "jekyll-sass-converter", "< 3.0"