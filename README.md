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
