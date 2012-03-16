---
title: "Use Cases"
authors: Harlan Knight Wood
layout: page
---

Open Your Project
=================

1. Convergence Network wants their users to be able to fork all of their transformational leadership content
  - could address with a "remix this" or "improve this" button on their content pages
  - could address with a core network browser that gives a view on all their remixable pages
  - users can fork the CN collection as a whole, or individual pages
  - users can post remixes to their blogs, including linking to the "diff"


ForkThis.cc
===========  

1. Free IP singularity geek Jake wants to remix the Acellerando wikipedia page into his own book review on his blog.
  - presses the "Fork This" browser button bar
  - he can edit, save, and paste markup or html into his blog
  
2. My Hot n Sticky Wiki
  - user presses the "fork my tale" button, to remix
  - is there an elegant way to choose your own adventure?  sure.  wiki-like links within content, any user can add new pages.  for the whole collection, then add new page.


collaborate.sunlightfoundation.com
==================================

1. World bank wants to accept public suggestions for proposed policy 
  - they post it to sunlight foundation
  - users can click "improve this" side tab, and save their suggested remix there (sunlight), for others to see and vote on


Technical Details Brainstorm
============================

Do we fork pages to html or markdown?  Or let the user choose?  Or both? 

We "fork" pages to Home/index.html

We store this page in a jekyll-compatible repository

By default we install the "freepress" theme -- octopress classic theme modified for pages not posts

If there is only one page, we show that.  Otherwise we show an index page, based on the octopress blog archives page

