# Getting Started

This template repository allows us to use Jekyll for Blogging with GitHub
pages.

## Static Site Generators

In the old days, creating a website would take the following steps.

  1. Pick a Hosting company
  2. Pick a Publishing framework (for example WordPress)
  3. Install whatever framework and supporting software is needed 
     - Framework
	 - Database
  4. Use the frameworks web interface to Create the content.
  
This is one heck of a lot of work for a simple website.  A lot of the
time we don't need the dded complexity of admin interfaces or
databases. 

Static Site Generators (SSG) were designed to get around this problem.
The SSG is a program that takes a collection of input files, and
converts them to a complete website.  It makes for a simple way of
getting text based content online.

### Benefits of SSG

  - Security.  As its all text based there should be nothing to hack.
    No databases for SQL Injection, or plugins to audit the security
    of.
  - Speed.  As we re note making API calls, and only serving text, it
    should be fast
  - Flexibly: We can host the site on a very basic web server. No
    need for plugins or extension
  - Simplicity:
     - No need to deal with complex CMS systems
	 - No need for software maintenance of framework
	 - We can write in plain text to get the output.
	 
On the flip side there are some downsides.

  - We cant really add dynamic content.  So things like comment are
    hard to support without a third party like Disqus
  - Paralysis of Choice: There are so many site generators, choosing
    one can be a nightmare.

## Jekyll 

[Jekyll](https://jekyllrb.com/) is a Static Site Generator (SSG) written in Ruby.

Its pretty easy to use and configure, and offers some nice
customisation.  Its allow pretty well supported in the "real world".

One of the great things about Jekyll is it integrates with GitHub
Pages.  This means we can use GitHub to develop and host the content
for us, without having to install any software.

## GitHub and GitHub Pages

While we may think of Git and GitHub for managing code, its actually
pretty good at dealing with any text based files.

Personally, I have been using it for holding most of my teaching material including:

  - Lecture Notes
  - Lecture Slides
  - Conference Papers
  - Student Dissertations.
  - My own personal blog [dan.quixote.codes](https://dan.quixote.codes)


One of the really nifty features of GitHub is GitHub pages.  These
allow us to create free static websites for our projects.  This is a
great feature, as it allows us to write documentation for our projects.
But GitHub have also integrated Jekyll, that allows is to write Blogs


!!! note

	These docs are also hosted using GitHub pages.
	We are not using Jekyll this time around (but the pretty awesome python based mkdocs project).
	It gives you an idea of the sort of things we can do.


## Starting a Jekyll Blog.

When it comes to starting a Jekyll blog we have 3 options
 
  1. Install Jekyll, and create a new blog
     - Install Ruby
	 - Jump through some hoops to get Jekyll Installed
     - Get working
  1. Use a pre made template for the Blog
  
While the first approach is great, and gives you a lot of control
over how you develop (and I would recommend it once you get used to
things), sometimes getting these things working is more hassle than
its worth.
