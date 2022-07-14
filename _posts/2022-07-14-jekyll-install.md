---
layout: post
title: " Install Jekyll on MacOS"
date: 2022-07-14 16:44:57 +0800
---
This is a pipeline of install Jekll on MacOS.
1. ```brew install ruby```
2. ```echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc```
3. ```ruby -v```, to check the ruby version if it is 3.x.x
4. ```gem install --user-install bundler jekyll```
5. ```echo 'export PATH="$HOME/.gem/ruby/X.X.0/bin:$PATH"' >> ~/.zshrc```
6. ```jekyll new my-site```
7. ```cd my-site/```
8. ```bundle add webrick```
9. ```bundle exec jekyll serve```
