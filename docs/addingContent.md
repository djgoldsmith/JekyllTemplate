# Adding Content to the Site

Lets look at adding some content to the site.

## Posts

The ```_posts``` directory is scanned and its contents added to the rendered
output.

!!! note

    Jekyll appears to be quite picky about filenames for posts
    We need to have the name as [DATE]-[Title].md  for it to render

### Post Structure

A Typical post will look something like this.

~~~
---
layout: post
title:  "Hello World"
date:   2020-07-10 12:39:12 +0100
categories: firstpost
---

This is our first post.  
I suppose saying **Hello World** is appropriate.

## Saying it in other Languages

```python
def helloWorld():
  print("hello world")
  
if __name__ == "__main__":
  helloWorld()
```
~~~

The part surrounded by dashes ```---``` is the post header.
This is metadata about the post and is used when rendering.

The rest of the content is **markdown** formatted text
You can find an nice [markdown primer](https://gamejolt.com/help/markdown)

