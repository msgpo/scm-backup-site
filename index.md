---
layout: default
title: SCM Backup
permalink: /
---

![{{ site.title}}](/img/logo64x64.png)

{{ site.description }}

It's free and open source!

At the moment, the following hosters are supported:

- [Bitbucket](https://bitbucket.org)
- [GitHub](https://github.com)
- [GitLab](https://gitlab.com)


## News

{% for post in site.posts limit: 5 %}
- {{ post.date | date: "%b %d %Y" }} [{{ post.title | escape }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

[More news...](/news/)