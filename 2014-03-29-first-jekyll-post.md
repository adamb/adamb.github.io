---
layout: post
title: First Jekyll Post
---

ok, so this is a post?
======================

So the CNAME file needs to have one line, the line of the domain name you want to use, in this case adam.beguelin.com is in the CNAME file. This page is a bit confusing: https://help.github.com/articles/setting-up-a-custom-domain-with-pages

I was surprised that the .gitignore file should include \_site since I was expecting this to be something that would be checked into git and rendered on the Github pages.  It must be that Github will render this automatically when the pages are pushed there.

Was also surprised that there was no index.html file generated.  

Markdown versus Textile?
------------------------

The Plain Text Wiki in textmate uses [Markdown](http://daringfireball.net/projects/markdown/syntax), so I should probably use that.



*How do I generate the homepage with an index of articles?*

Running it so it will show the changes automatically as I save the file

	jekyll serve --watch
