---
title: new update to the site
jurl: 
date: 2023-12-01
jkey: blog
---
# 12/01/23 - New Update to the site

added if loop to filter by key to use one template for different collections on same page - very powerful stuff

    {% for item in items %}
        {% if item.status == "published" %}
        <h2>{{ item.title }}</h2>
        <!-- Add other HTML elements related to the item -->
        {% endif %}
    {% endfor %}

