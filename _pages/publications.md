---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

{% include base_path %}

<head>
<style>
a:visited {
  color: grey;
  background-color: transparent;
  text-decoration: none;
}
a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}
</style>
</head>

<body>

<h2 style="color:green;">Journal</h2>

<ol>
  {% for post in site.publications reversed %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <a href="{{post.paperurl}}">[Download]</a>
    </li>
  {% endfor %}
</ol>

<h2 style="color:green;">Conference</h2>
<ol>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <a href="{{post.paperurl}}">[Download]</a>
    </li>
  {% endfor %}
</ol>

</body>
