# Testify Project Blog Site
[![Build Status](https://travis-ci.org/testify-project/blog.svg?branch=develop)](https://travis-ci.org/testify-project/blog)
[![Join the chat at https://gitter.im/blog/Lobby](https://badges.gitter.im/blog/Lobby.svg)](https://gitter.im/blog/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![License](https://img.shields.io/badge/Creative%20Commons-BY--SA-lightgrey.svg)](https://github.com/testify-project/blog/blob/master/LICENSE.md)

## Local Site Development
You can set up a local version of your Jekyll GitHub Pages site to test changes to your site locally.

### Install Prerequisites
1. [Install Ruby 2.1.0 or higher](https://www.ruby-lang.org/en/documentation/installation/)
1. [Install NodeJS 4.2.6 or higher](https://nodejs.org/en/download/package-manager/)
1. Install Bundler
```bash
gem install bundler
```
1. Install Bundles
```bash
sudo bundle install
```
1. Install Gulp
```bash
sudo npm install --global gulp-cli
```
1. Install Dependencies
```bash
npm install
```

### Generate and Run Site Locally
#### Clean, Build, and Run Site
```bash
gulp
```
#### Clean Site
```bash
gulp clean
```
#### Build Site
```bash
gulp  build
```
#### Run Site
```bash
gulp run
```

### Use GUI Admin Tool Site
1. Enable jekyll-admin gem in the Gemfile
```ruby
gem 'jekyll-admin', group: :jekyll_plugins
```
1. Run Admin
```bash
gulp admin
```
1. Go to [http://127.0.0.1:4098/admin](http://127.0.0.1:4098/admin)


## Color Platter
- Orange - #DC5D1E
- Navy   - #3C4E5C
- Brown  - #765E51
- Black  - #000000
- White  - #FFFFFF
