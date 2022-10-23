+++
layout = 'post'
title = 'From Jekyll to Hugo'
categories = 'blog'
draft = true
+++

Not that there’s anything wrong with Jekyll, in my opinion, but I don’t spend any time with Ruby anymore. Conversely, at Snyk, we’ve made Go the second language to be a first-class citizen. So when I was looking at my Jekyll-based personal site, it seemed like a good idea to move it over to Hugo and keep myself in an ecosystem I which makes the most sense, day to day.

I will caveat the above by saying, with Hugo, you aren’t really spending much time with Go as a language. It’s mostly the Go templating language.

I spend a while experimenting until I was happy that Hugo could do everything Jekyll could do and achieved complete feature parity between the two sites, meaning functionally, to the user, nothing is different, including a few things under the hood, which suprised me. Hugo is incredibly flexible, provided you can navigate the documention which I found more confusing than it needed to be. All the information was there somewhere, it just often hid it away.

Hopefully, this might help someone else making the same journey.

## Getting started with Hugo

As I’m on a Mac, I simply used

```
brew install hugo
```

Check the [documentation](https://gohugo.io/getting-started/installing/) for other systems and ways to install.

Once it’s installed, use

```
hugo new site my_site
cd my_site
```

then use `hugo` to start a server for the site.

## Template and Content

## Deploying
