---
title: "Create a GitHub Pages blog on Ubuntu Linux with local build"
date: 2020-09-26
layout: post
---

![Laptop](https://user-images.githubusercontent.com/4943215/74586452-bcb15780-4fe7-11ea-94a8-7a9b52bf04b3.jpeg)

Big, big shout out to [Arya Murali](https://aryamurali.com/) and her comprehensive guide on Medium to [Creating your blog for free using Jekyll + Github pages](https://medium.com/20percentwork/creating-your-blog-for-free-using-jekyll-github-pages-dba37272730a). That's the definitive and really spot on guide to how to do this.

I could attempt to rewrite the whole of that article in my own words and I've had a go but it's so well written and clear that I'll just direct you to [that tutorial](https://medium.com/20percentwork/creating-your-blog-for-free-using-jekyll-github-pages-dba37272730a). 

[The GitHub Pages welcome page](https://pages.github.com/) provides an easier method to setting up a blog on GitHub Pages but it won't enable you to build your website locally on your machine and push the changes from there. [This tutorial](https://medium.com/20percentwork/creating-your-blog-for-free-using-jekyll-github-pages-dba37272730a) is a thorough guide to how to do that.

I'm running on a Ubuntu 18.04 Linux platform so in terms of installing packages and dependencies start with this at the command line.

{% highlight bash %}
$ sudo apt-get install ruby  
$ gem install jekyll bundler
{% endhighlight %}

Everything else [here](https://medium.com/20percentwork/creating-your-blog-for-free-using-jekyll-github-pages-dba37272730a) should be straight-forward enough. It is a kind of complicated process. One of the confusing things is you build offline *before* creating a repository on GitHub Pages. Another issue that's often mentioned in similar guides (I've read quite a lot) is checking out to the gh-pages branch. I don't understand any of that but it's all set out in [the guide](https://medium.com/20percentwork/creating-your-blog-for-free-using-jekyll-github-pages-dba37272730a).

<!-- From the browser or command line go to [http://127.0.0.1:4000](http://127.0.0.1:4000) and check out your new blog.  

These are the essential instructions that are frustratingly absent from a lot of guides but were made explicit in [the marvellous tutorial/guide mentioned above](https://medium.com/20percentwork/creating-your-blog-for-free-using-jekyll-github-pages-dba37272730a). I'm just passing on some useful information. We're kind of only halfway there because the blog is not yet set up on GitHub Pages. Again this is confusing because the trick is to set up create the repository offline (as we just did with the jekyll serve command) before creating the repository on GitHub Pages. [Arya's tutorial](https://medium.com/20percentwork/creating-your-blog-for-free-using-jekyll-github-pages-dba37272730a) takes you carefully step-by-step through that process.  

So on GitHub Pages you create a new repository. This is achieved via the plus button at the top right of the screen. You enter your_blog_name exactly as you set it up with jekyll earlier in the Repository name box. Don't initialize the repository with a README. Just hit the Create repository green button and stop right there. We're going to 'push an existing repository from the command line'. -->

So I'm not exactly new to blogging or using GitHub but I do get a bit tied up in knots when trying to work my way through this stuff. Jekyll has a decent and not too long [Step by Step Tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/) which I'll have to read again. I jump into these things and only really understand what's happening after I've haphazardly come across and typed in [the correct instructions](https://medium.com/20percentwork/creating-your-blog-for-free-using-jekyll-github-pages-dba37272730a) I needed to get it to work. That's pretty much my amateur way in. The GitHub Pages docs were maddening. [Liquid templating](https://jekyllrb.com/docs/step-by-step/02-liquid/) looks tricky. It's all coded in Ruby this static website stuff, Jekyll and so forth. I remember that fantastic comic guide to Ruby - Why's comic guide or something? What was that called? [Why's (Poignant) Guide to Ruby](https://poignant.guide/). There are static site generators for Python, such as [Pelican](https://blog.getpelican.com/) and now I understand a bit more how it works I could have a look at that maybe or perhaps just stick with Ruby and Jekyll and a just about working website.  

OK, [how do I justify paragraphs?](https://stackoverflow.com/questions/35077507/how-to-right-align-and-justify-align-in-markdown) This is gonna' be harder than I thought...