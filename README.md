## Introduction

This repository contains the source for the [Code for Nashville website](http://www.codefornashville.org). The site is hosted on [Github Pages](https://pages.github.com). Changes merged to the master branch of this repository are automatically deployed to the live site.

## Prerequisites
- [Ruby] (programming language)
- [Gem] (ruby's built-in package manager)
- [Bundler] (a dependency tracker for gems)
- [Homebrew] (optional, see below)
- [rbenv] (optional, see below)

Make sure you have ruby installed.
If ruby comes with your system, you may want to do a clean install.
For example, if you use MacOs, you should probably install [brew][Homebrew] and run
```
brew install rbenv
rbenv install 2.5.3 # or latest version of ruby
```
[Homebrew] is a MacOS package manager that gives you [rbenv], which lets you do a clean install of [Ruby] (and [Gem]).

## Contributing

The website is generated with Jekyll, so to contribute you'll need to have that [installed](http://jekyllrb.com/docs/installation/).


This is how to set it up:

1. Clone this repo
1. Run 'bundle install' to install required dependencies. If you don't have bundler, you can install it with 'gem install bundler' or check out [bundler's site](http://bundler.io/) for help. You may also need xcode installed by running 'xcode-select --install' in the command line.
1. Run locally with `bundle exec jekyll serve`


Changes to our website follow the [Github Flow](https://guides.github.com/introduction/flow/index.html). You need [git installed](https://help.github.com/articles/set-up-git) and some experience with Github. If you are not experienced with git, check out [Github's documentation](https://help.github.com) or ask another brigade member for help.


The process is

1. Create a branch
1. Make your changes
1. Test them locally with `bundle exec jekyll serve`
1. Commit your changes
1. Push your changes
1. Open a pull request
1. Wait for someone else to review your code
1. Once it gets a thumbs-up, merge your branch
1. Check the [site](http://www.codefornashville.org) and see your changes

[Ruby]: https://www.ruby-lang.org/en/
[Gem]: https://rubygems.org/
[Bundler]: https://bundler.io/
[Homebrew]: https://brew.sh/
[rbenv]: https://github.com/rbenv/rbenv
