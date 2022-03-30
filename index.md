---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Stardew Valley Speedrun Tips.
{: .fs-9 }

Just the Docs gives your documentation a jumpstart with a responsive Jekyll theme that is easily customizable and hosted on GitHub Pages.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/just-the-docs/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Introduction

Welcome! This document will guide you on how to use Adobe Photoshop for creating and editing images. The aim of this guide is to provide users with the Photoshop skills that can help in the development of video games and websites.

Adobe Photoshop is a photo editing software made by Adobe. It provides users with many tools to create and edit images easily. This software is widely used by artists, designers, and developers making it the standard software to use for any graphic design.

### Intended Users

The documentation is targeted toward the following users:
* Novice digital artists, graphic designers, or photo editors.
* Software developers who want to make custom design elements.

### Prerequisites

To successfully complete the steps provided, you will need the following:
* A general understanding of basic computer tasks.
* An internet connection to access required software.

### Software Requirement(s):

Before proceeding with the guide, ensure you have installed the following:
* [**Windows 10 Operating System**][https://www.microsoft.com/en-ca/windows/get-windows-10]
* [**Adobe Photoshop Pro 2021 _(Version 23.2.2 or later)_**][https://www.adobe.com/ca/products/photoshop.html]

















<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>

### Local installation: Use the gem-based theme

1. Install the Ruby Gem
  ```
  bash
  $ gem install just-the-docs
  ```
  
  ```yaml
  # .. or add it to your your Jekyll site’s Gemfile
  gem "just-the-docs"
  ```

2. Add Just the Docs to your Jekyll site’s `_config.yml`
  ```yaml
  theme: "just-the-docs"
  ```

3. _Optional:_ Initialize search data (creates `search-data.json`)
  ```bash
  $ bundle exec just-the-docs rake search:init
  ```

3. Run you local Jekyll server
  ```bash
  $ jekyll serve
  ```
  ```bash
  # .. or if you're using a Gemfile (bundler)
  $ bundle exec jekyll serve
  ```

4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Just the Docs is &copy; 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](http://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/just-the-docs/just-the-docs/tree/main/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/just-the-docs/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/just-the-docs/just-the-docs/tree/main/CODE_OF_CONDUCT.md) on our GitHub repository.
