---
title: 
---
# My Web Site using Github Pages & Jekyll

I have the distinct impression of starting a silly job again.

**Url de publication:** [https://mabyre.github.io/](https://mabyre.github.io/)

**Origin:** [https://github.com/mabyre/mabyre.github.io](https://github.com/mabyre/mabyre.github.io)

Try use [posts](https://mabyre.github.io/_post)

Fisrt of all you need to go to "Actions" tab to see if build/deploy process is **Ok**

- [Samples](#samples)
- [Tools](#tools)

## Menu

<ul>
  {% for item in site.menu %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
</ul>

## Index

[doc](https://mabyre.github.io/doc) > [page1](https://mabyre.github.io/doc/page1)

[error](https://mabyre.github.io/error)

[jump to docs](https://mabyre.github.io/docs/)

## Github Pages

Create a repository named **yourusername.github.io**. On setting tab set what is good for. Create a file **_config.yml** :

- [Quickstart for GitHub Pages](https://docs.github.com/en/pages/quickstart)

After that, help documentation is a little confused, two ways to continue :

- [Adding content to your GitHub Pages site using Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-content-to-your-github-pages-site-using-jekyll)

  - [Pages](https://jekyllrb.com/docs/pages/)
  - [Post](https://jekyllrb.com/docs/posts/)

- [About GitHub Pages and Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)

  - [Configuring Jekyll in your GitHub Pages site](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll#configuring-jekyll-in-your-github-pages-site)

    I'am so disapointed because **_post** will never works cause :

      By default, Jekyll doesn't build files or folders that:

      are located in a folder called /node_modules or /vendor

      start with _, ., or #

      end with ~

      are excluded by the exclude setting in your configuration file
  
  - [GitHub Metadata](https://jekyll.github.io/github-metadata/site.github/)

      Just not understandable

## Help on GitHub & Jekyll

- [Getting started with writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)

- [Help on GitHub Pages](https://docs.github.com/en/pages)

- [About GitHub Pages & Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)

- [About GitHub Pages & Jekyll fr](https://docs.github.com/fr/pages/setting-up-a-github-pages-site-with-jekyll)

## Samples usings of GitHub Pages & Jekyll

- [Github Pages examples](https://github.com/collections/github-pages-examples)

  - [artsy.github.io](https://github.com/artsy/artsy.github.io)

  > [artsy.github.io](https://artsy.github.io)

  - [square.github.io](https://github.com/square/square.github.io)

  > [square.github.io](https://square.github.io)

## Tools

Randomly in my wanderings

[YAML Validator](https://codebeautify.org/yaml-validator)

[Markdown syntaxe](https://www.markdownguide.org/basic-syntax/)
