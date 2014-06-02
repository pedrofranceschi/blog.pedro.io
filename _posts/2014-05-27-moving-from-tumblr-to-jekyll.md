---
layout: post
title: Moving from Tumblr to Jekyll
---

When I started blogging, back in 2011, choosing Tumblr as my blog engine seemed
a good idea.  All I needed was a simple, [WYSIWYG][wysiwyg] blog system, that
took care of the pains of web hosting (i.e. servers, security, uptime, backups,
etc.) while I took care of what a blog is all about: writing.

### Why not Tumblr?

Since 2011, a lot of things changed.  First, I moved from TextMate to Vim, and
suddenly writing even a few lines using anything *but* Vim meant suffering.  As
the posts needed to be written in Tumblr's poor web interface, and usually had
more than a few lines, I had the perfect excuse to stop writing at that time.
Not anymore.

Also, Tumblr *sucks* for writing technical content.  There's no way to paste
code with decent syntax-highlighting.  You can't use `iframes`, neither most of
the modern HTML tags, such as `video`.  Using `embeddeds` destroys the text
formatting and font sizes.  I could keep listing for days the dozens of
troubles I faced while using Tumblr...

I needed a _Vim-like_ blogging system. Luckly, Jekyll is to Tumblr as Vim is to
TextMate.

### Jekyll + GitHub Pages

I read about [a][moved-1] [lot][moved-2] [of][moved-3] [people][moved-4]
[who][moved-5] [moved][moved-6] [from][moved-7] dynamic-generated blogs to
"semi-static" sites powered by [Jekyll][jekyll] (Ruby) and [Hyde][hyde]
(Python).  I never _needed_ a dynamic blog engine, so why not giving Jekyll a
try?

Since Jekyll is written in Ruby, has Markdown support out-of-the-box and [a
pretty decent integration with GitHub Pages][jekyll-github-pages], it seemed a
no-brainer.  I could write in the comfort of Vim, commit with
[fugitive][fugitive] and have my post online instantly. Minimalistic and
pain-free blogging.

[wysiwyg]:http://en.wikipedia.org/wiki/WYSIWYG
[moved-1]:http://stevelosh.com/blog/2010/01/moving-from-django-to-hyde/
[moved-2]:http://joshualande.com/jekyll-github-pages-poole/
[moved-3]:http://ocramius.github.io/blog/moving-my-blog-to-jekyll/
[moved-4]:http://hadihariri.com/2013/12/24/migrating-from-wordpress-to-jekyll/
[moved-5]:http://tobiasahlin.com/blog/moving-from-wordpress-to-jekyll/
[moved-6]:http://gastonsanchez.com/blog/opinion/2013/12/29/moving-to-jekyll.html
[moved-7]:http://blog.davidebbo.com/2014/01/moving-to-github-pages.html
[jekyll]:http://jekyllrb.com
[hyde]:http://hyde.github.io
[fugitive]:https://github.com/tpope/vim-fugitive
[jekyll-github-pages]:https://help.github.com/articles/using-jekyll-with-pages
