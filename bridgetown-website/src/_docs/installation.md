---
order: 2
title: Installation
description: Official guide to install Bridgetown on macOS, GNU/Linux or Windows.
top_section: Setup
category: installation
---

Bridgetown is software written in Ruby, a friendly programming language that maximizes programmer happiness and makes it easy to build and customize open source projects. You will need to install Bridgetown as a Gem after you set up your Ruby language environment. You will also need to install Node and Yarn to manage your website's frontend assets.

## Requirements

* [Ruby](https://www.ruby-lang.org/en/downloads/) version **{{ site.data.requirements.min_ruby }}** or above, including all development headers (ruby version can be checked by running `ruby -v`)
* [RubyGems](https://rubygems.org/pages/download) (which you can check by running `gem -v`)
* [Bundler](https://bundler.io) (which you can check by running `bundle -v`)
* [Node](https://nodejs.org) version **{{ site.data.requirements.min_node }}** or above (which you can check by running `node -v`)
* [Yarn](https://yarnpkg.com) (which you can check by running `yarn -v`)

## Other System Tools

* [GCC](https://gcc.gnu.org/install/) and [Make](https://www.gnu.org/software/make/) (in case your system doesn't have them installed, which you can check by running `gcc -v`,`g++ -v`  and `make -v` in your system's command line interface)

## Guides

For detailed install instructions have a look at the guide for your operating system.

* [macOS]({{ '/docs/installation/macos/' | relative_url }})
* [Ubuntu Linux]({{ '/docs/installation/ubuntu/' | relative_url }})
* [Other Linux distros]({{ '/docs/installation/other-linux/' | relative_url }})
* [Windows]({{ '/docs/installation/windows/' | relative_url }})