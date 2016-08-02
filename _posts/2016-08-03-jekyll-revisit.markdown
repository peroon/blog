---
layout: post
title:  "久しぶりのJekyll"
date:   2016-08-03 02:33:00 +0900
categories: jekyll update
---

なかなか

```
jekyll serve
```

が通らない. Ruby2.3にしたからかな

```
bundle update
gem install bundler
bundle update
gem install nokogiri -- --use-system-libraries
xcode-select --install
gem cleanup
bundle exec jekyll serve
```

bundle updateが通るようにしてから、bundle execを前に付けてjekyll serveで動いた。_postsに記事を足せばいい。ファイル名に日付を入れているけど、それは使われていなくて、mdファイルに書いてるdateの値がソートに使われて表示されるようだ