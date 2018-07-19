# Static site template

A simple, batteries-included static site template. Use this as a baseline
to create a free static website on GitHub Pages. Hosting and github.io domain name
are free, or you can use your own domain.

I've used a variation of this template to make a half-dozen static websites.
It should help you make a great site in just 10 minutes. Again, zero hosting
costs!

## What's inside

* Jekyll
* Bootstrap
* Font Awesome
* jQuery

## Running

Once you've cloned the repo, run the following in your terminal. You'll need to have Ruby installed (it's pre-installed on macOS and most Linux distributions.)

```
sudo gem install bundler
bundle install
```

To run the app, run this in your terminal:

```
bundle exec jekyll serve
```

Then open up <http://127.0.0.1:4000> in your browser to view the site.

## Making your static site in 10 minutes

Here's how to set up your very own static website in 10 minutes. This assumes you
will buy your own domain name instead of using a free github.io URL.

1. Buy a domain name. [Google Domains](https://domains.google/#/), [GoDaddy](https://www.godaddy.com/), and [NameCheap](https://www.namecheap.com/) are all good.
1. Fork this repository and rename it. You can name it whatever you want, as long as the github.io name is available. [Follow this article](https://pages.github.com/) - see the "User or organization site" example.
1. [Follow this article](https://help.github.com/articles/setting-up-an-apex-domain/) to connect your github.io URL with your actual domain name.
1. Put your real domain name in the `CNAME` file. [See instructions at number 5 here](https://hackernoon.com/how-to-set-up-godaddy-domain-with-github-pages-a9300366c7b).
1. Customize this repository. Each time you push, the website should be updated.


## Customizing

You can customize this freely with your own styles and templates. (Bootswatch
  and HTML5 are among my favorite places to look.) This template provides the
  skeleton more than an enforced style.
