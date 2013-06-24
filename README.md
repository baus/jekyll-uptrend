# Uptrend

## Download Uptrend

Uptrend is a [Jekyll](http://jekyllrb.com/) theme which makes it easy to get a decent 
looking personal Jekyll site up and running quickly. It works well with 
[GitHub Pages](http://pages.github.com/) which offers free Jekyll hosting. If you 
want to change providers, it is trivial to move your data since it is all stored in
a Git repo. 

Uptrend started as a fork of Carlos Becker's [Up Theme](http://carlosbecker.com/posts/up-a-jekyll-theme/), which
also uses ideas from [Jekyll Bootstrap](http://jekyllbootstrap.com/), but has deviated fairly significantly and 
mostly shares some common typography elements. 

While the theme uses Bootstrap 3 under the covers, I have attempted to make it not look bootstrappy. For an example
of the theme in action, see [my website](http://baus.net). 

## Installation

If you have Jekyll on your machine the installation is rather trivial.

```

```

Edit _config.yml to contain information about your site. Some of the information in the author section is used
by the resume template. 

There are two static pages that you should modify (/about and /resume). The contents of these pages is specified
in markdown, unlike most Jekyll templates which specify static files in pure HTML. The trick is they are processed 
as includes, and hence they are in the _includes directory. 

The /resume page is not linked from the main navigation, but you can give this link out to anyone you want to share it 
with. The layout used on the page is a little more friendly for printing. 

To deploy to github pages, you simply need to create a repo as follows:

```

```

## Notes

Up and Jekyll Bootstrap include a Rakefile for handling some tasks such as creating new posts. I decided to omit
those from this release, primarily because getting all the dependencies working properly is a bit tricky, and they
aren't needed to get up and running. A similar mechanism maybe re-introduced in a future release.

