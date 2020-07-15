# Getting Started

This template repository allows us to use Jekyll for Blogging with Github
pages.

In the old days, creating a website would take the following steps.

  1. Pick a Hosting company
  2. Pick a Publishing framework (for exmaple wordpress)
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

There are a few benefits to using SSG:

  - Security.  As its all text based there should be nothing to hack.  No databases for SQL Injection, or plugins to audit the security of.
  - Speed.  As we re note makingg API calls, and only serving text, it should be fast
  - Flexiblilyt:  We can host the site on a very basic web server. No need for plugins or extenstion
  - Simplicity:
     - No need to deal with complex CMS systems
	 - No need for software maintanance of framework
	 - We can write in plain text to get the outptut.
	 
On the flip side there are some downsides.

  - We cant really add dynamic content.  So things like comment are
    hard to support without a third party like Disquess
  - Paralasis of Choice: There are so many site generators, choosing
    one can be a nightmare.

## Jekyll 

[Jekyll](TODO: LINK) is a Static Site Generator (SSG) written in Ruby.

Its pretty easy to use and configure, and offers some nice
customisations.  Its allo pretty well supported in the "real world".

One of the great things about Jekyll is it intergrates with Github
Pages.  This means we can use Githob to develop and host the content
for us, without having to install any software.

## Github and GitHub Pages

While we may think of Git and Github for managing code, its actually
pretty good at dealing with any text based files.

Personally, I have been using it for holding most of my teaching materal including:

  - Lecture Notes
  - Lecture Slides
  - Conference Papers
  - Student Dissertations.
  - My own personal blog [dan.quixote.codes](dan.quixote.codes)


One of the really nifty features of GitHub is Github pages.  These
allow us to create free static websites for our projects.  This is a
great feature, as it allows us to weite documenttion for our prjects.
But Github have also intergrated Jekyll, that allows is to write Blogs


!!! note

	These docs are also hosted using github pages.
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
