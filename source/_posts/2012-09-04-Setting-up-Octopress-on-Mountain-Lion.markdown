---
layout: post
title: "Setting up Octopress on Mountain Lion"
date: 2012-09-04 22:11
comments: true
categories:
---

I decided to start blogging again and picked
[Octopress](http://octopress.org/). While setting up I found some hickups I
want to document.

* You have to build the latest ruby from source via rvm. For strange reasons ruby 1.9.3 didn't work for me.

```
rvm install ruby-1.9.3-p194
```

* Don't prefix your Twitter name with an "@" in _config.yml. It results in an ugly stacktrace stating nonsense.

That's it. The rest is pretty straight forward.
