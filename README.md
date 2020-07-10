# Template for Jekyll Blogs

## Prereqs

 - ruby
 - gem
 
~~~
dang@dang-laptop ~/Github/IOC/JekyllTemplate$ ruby -v
ruby 2.7.1p83 (2020-03-31 revision a0c7c23c9c) [x86_64-linux]
dang@dang-laptop ~/Github/IOC/JekyllTemplate$ gem -v
3.1.3
dang@dang-laptop ~/Github/IOC/JekyllTemplate$ 
~~~

## Installing everything fro Scratch

SEupt the Bundler

(Optioal) set local Jekyl storeage
```bundle config set --local path 'vendor/bundle'```


~~~
dang@dang-laptop ~/Github/IOC/JekyllTemplate$ bundle init                         10 ↵  ✹ ✭master 
Writing new Gemfile to /home/dang/Github/IOC/JekyllTemplate/Gemfile
~~~

Add Jekyll to it

~~~
dang@dang-laptop ~/Github/IOC/JekyllTemplate$ bundle add jekyll --version 3.8.5         ✹ ✭master
~~~

And Create a new Jekyll site. 

~~~
bundle exec jekyll new . --force
~~~

NOTE:  This will overwrite your gitignore....

Update the Gemfile

~~~
source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
#gem "jekyll", "~> 3.8.5"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.0"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?
~~~

And install the rest of the dependences

~~~
bundle install
~~~


## Local Development

~~~
bundle exec jekyll serve
~~

