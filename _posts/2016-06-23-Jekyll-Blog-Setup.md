---
layout:     post
title:      Quickly Setup Your Own Personal Blog Using Jekyll
date:       2016-06-20 12:31:19
summary:    Jekyll is a simple static site generator. It takes in a website from the raw material (Markdown), and runs it through Liquid
categories: jekyll pixyll
---
## Quickly Setup Your Own Personal Blog Using Jekyll

## Roll Your Blog with Github Pages and Jekyll

## Create Your Own Simple Fast Blog in Minutes

---
Find a great template to start off
Bend it to your will, add your own flavor
Setup Jekyll on Linux
Throw up some posts
Include images hosted by CDN, optimize images

## Intro
Jekyll is a simple static site generator. It takes in a website from the raw
material (Markdown), and runs it through Liquid a templating engine to spit
a full static website (HTML,CSS, Javascript) ready for deployment.

Jekyll has been seeing huge growth

## Installation
jekllrb.com has a great section on installation for Linux,Mac,and Windows. So
I'll only tell you what you need to know for Linux.
It's always a good practice to update your repositories before installing anything new

```
$ sudo apt-get update
```

## Ruby
```
$ sudo apt-add-repository ppa:brightbox/ruby-ng
$ sudo apt-get update
$ sudo apt-get install ruby2.3 ruby2.3-dev
$ sudo ruby -v
```

## Ruby Gems

  Download the latest version or upgrade to the latest version. I'm going to start fresh. Download the tgz and unpack in any directory. Unpack and run setup.rb

```
$ cd /path/to/dir/rubygems-x.x.x
$ sudo ruby setup.rb
```

### Node.js

```
$ curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
$ sudo apt-get install -y nodejs
$ node -v
$ npm -v
```

```
$ sudo apt-get install nodejs
$ sudo apt-get install npm
$ sudo ln -s /usr/bin/nodejs /usr/bin/node
```

Update to the latest nodejs

```
$ sudo npm cache clean -f
$ sudo npm install -g n
$ sudo n stable
$ sudo ln -sf /usr/local/n/versions/node/X.X.X/bin/node /usr/bin/node
$ node -v
$ npm -v
```

### Python

Make sure python 2.7+ is installed.

```
$ python -v
```

**Jekyll**

```
$ gem install Jekyll
```

jekyll.tips is a great place to get started.
