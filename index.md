---
layout: page
title: 数据水墨
tagline: Supporting tagline
---
{% include JB/setup %}

参阅 [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

或完整的使用说明及文档: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## 更新作者信息

记得在 `_config.yml` 文件中给出你自己的信息:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


