---
title: Loans
permalink: "/loans/guides/"
layout: page
---

{% assign guides = site.guides | where_exp: "guide", "guide.categories contains 'loans'" %}
{% for guide in guides %}
  <li>{{ guide.title }}</li>
{% endfor %}
