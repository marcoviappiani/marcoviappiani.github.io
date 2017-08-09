---
layout: post
title: Why I'm using Jekyll
feature-img: "img/jekyll-logo.png"
---

Here are my thoughts on Jekyll and why I'm using it to develop this site.

### What is Jekyll?

[Jekyll](https://jekyllrb.com/docs/home/) is a simple, blog-aware, static site generator.

## TL;DR

If you want a short summary:
* It's a common tool and I'd like to learn it
* It uses simple markdown
* It can be fully customised and it looks nice thanks to the Liquid template engine
* It can be hosted for free with Github
* Many websites don't need to be overly complicated nowadays. Jekyll's simplicity is useful in many cases

## If you have more time

So there you have it. Proceed at your own risk


### It's a common tool
First of all, let me start by saying that it's a common tool and it's always useful to have some idea of what's available

### It uses simple markdown
The nice think about using simple [markdown](http://daringfireball.net/projects/markdown/syntax) is that it makes it quicker to write with structure. People nowadays only skim pages, so a blog post shouldn't look like a research paper.

For instance, to make this table I didn't have to use any complex html.

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell


### It can be fully customised
Jekyll uses the "Liquit" templating enging. This is a simple set of tools to customise the look and feel of a website. Liquid is used by many frameworks and companies, not just Jekyll. Notable examples include Shopify, Zendesk, Desk.com, customer.io, GoDaddy and many more. 

As an example of customisation, this theme makes use of Pygments to highlight code.

{% highlight js %}
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}
{% endhighlight %}

Also, this theme uses KaTeX to display maths so that equations such as $$S_n = a \times \frac{1-r^n}{1-r}$$ can be displayed inline.


### It can be hosted for free with Github
Hosting can be expensive and difficult to manage. If what you need is a simple static site, you shouldn't be spending a lot of your time managing a server.

### Many websites don't need to be overly complicated nowadays
In the end what you should use depends on your objectives. If all you need is a simple static website without any major interactivity element, Jekyll may be just what you need.


Thank you for reading!