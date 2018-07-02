---
layout: default
title: News | Leiden CBC
tag: news
permalink: /news/
---
<article class="post-content-main">
  <!--h1>News <span class="left-icon"><a href="{{ site.baseurl }}/feed.xml"><i class="fa fa-rss"></i></a></span></h1-->
  <h1>News <span class="left-icon"><i class="fa fa-rss"></i></span></h1>
  <ul class="post-list">
    {% for post in site.posts %}
      <li class="post-list-item">
        <div class="row" style="margin-top:1rem;">
          <div class="post-list-title col-sm-9">{{ post.title }}</div>
          <div class="post-list-date col-sm-3">{{ post.date | date: "%-d %b %Y" }}</div>
        </div>
        <div class="row">
          <div class="post-list-excerpt">{{ post.excerpt }}</div>
          <a class="post-list-link" href="{{ site.baseurl }}{{ post.url }}">More...</a>
        </div>
      </li>
    {% endfor %}
  </ul>
</article>
