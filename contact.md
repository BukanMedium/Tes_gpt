---
layout: post
title: "My First Blog Post"
date: 2020-01-01
categories: [category1, category2]
---

<h1>{{ page.title }}</h1>
<p>{{ page.date | date: "%B %d, %Y" }}</p>
<p>{{ Kamu tau bagaimana cara menghubungi saya }}</p>
<p>Categories: {% for category in page.categories %} {{ category }} {% endfor %}</p>
