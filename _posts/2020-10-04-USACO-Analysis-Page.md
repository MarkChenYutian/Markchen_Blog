---
layout: page
---
<head>
<link rel="stylesheet" type="text/css" href="https://markchenyutian.github.io/Markchen_Blog/Asset/css/Unified_Style.css">
</head>

# USACO Gold Division Analysis
<center><img src="https://markchenyutian.github.io/Markchen_Blog/Asset/USACO_Banner.png"></center>

<a herf="window.open('https://markchenyutian.github.io/Markchen_Blog/2020/10/04/USACO-2016-Jan-Gold-Analysis.html">
<div class="card">
  <div class="title_container">
    <h3>2016 January Contest Gold Division Analysis</h3>
  </div>
</div>
</a>

<br>
test Liquid

<div id="home">
  <h2>All Posts</h2>
    {% for post in site.posts %}
      <div class="card">
      <div class="title_container">
      <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}
      </a>
      </h3>
      </div>
      </div>
      <div style="width: 100%; height: 1em"></div>
    {% endfor %}
    ---
    {{site.tags}}
</div>