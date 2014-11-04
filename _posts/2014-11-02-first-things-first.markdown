---
layout: post
title: "First Things First"
date: 2014-11-02 13:16:1
categories: jekyll
tags: featured
image: /assets/article_images/jekyll/logo.png
---
So, here it is, my first post. 
I have reading lately the advantage of having a blog to keep yourself writing about what you like. Specially for PhD students is great way to develop better writing skills.  The purpose of this website is to present information about different topics including new technologies, language documentation project, linguistic issues in general and any other topic that can come into my mind. Having said this, some of the future posts can go more into research ideas, and some of them can be the result of traveling to interesting places and therefore leisure readings.    

On my way looking for a new blogging application, after trying most the well-known content manager systems out there like Drupal, Wordpress and Joomla, I came across jekyll. Since I’m already using github for at work I thought I will be convenient to give it a try. Jekyll is a blogging application (or if you prefer the term of *static website genrator*) based on Ruby that fits nicely with github-pages and can be used as free hosting place for your website and project. Another great thing about jekyll, is that it doesn’t require a database but just files that will be converted to HTML, the result is a static website, fast, secure and flexible. You can use markdown syntax for your text what allows you to concentrate on your content.

Jekyll also offers powerful support for code snippets, which is very handy when publishing blogs about programming languages. For example:

{% highlight python %}
"""
99 Bottles of Beer 
"""
for quant in range(99, 0, -1):
   if quant > 1:
      print(quant, "bottles of beer on the wall,", quant, "bottles of beer.")
      if quant > 2:
         suffix = str(quant - 1) + " bottles of beer on the wall."
      else:
         suffix = "1 bottle of beer on the wall."
   elif quant == 1:
      print("1 bottle of beer on the wall, 1 bottle of beer.")
      suffix = "no more beer on the wall!"
   print("Take one down, pass it around,", suffix)
   print("--")
   {% endhighlight %}


There are certaily many other interesting things to learn about jekyll that I just won't mention here, but feel free to check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

{% highlight js %}

<footer class="site-footer">
 <a class="subscribe" href="{{ "/feed.xml" | prepend: site.baseurl }}"> <span class="tooltip"> <i class="fa fa-rss"></i> Subscribe!</span></a>
  <div class="inner">a
   <section class="copyright">All content copyright <a href="mailto:{{ site.email}}">{{ site.name }}</a> &copy; 2014 &bull; All rights reserved.</section>
   <section class="poweredby">Made with <a href="http://jekyllrb.com"> Jekyll</a></section>
  </div>
</footer>
{% endhighlight %}


[jekyll]:		http://jekyllrb.com
[jekyll-gh]:   	https://github.com/jekyll/jekyll
[jekyll-help]: 	https://github.com/jekyll/jekyll-help
[github]:	   	https://github.com/          