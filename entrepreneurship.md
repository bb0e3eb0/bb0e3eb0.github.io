---
layout: page
title: 
permalink: /entrepreneurship/
---

<div class="posts">



<div class="cat-nav">
  <ul>
    <li>
      <a  href="/articles">Show All</a>
    </li>
    <li>
    <a class="is-active" href="/entrepreneurship" >Entrepreneurship</a>
          </li>
    <li>
      <a href="/inner-game" class="btn-nav">Inner Game</a>
    </li>
    <li>
      <a href="/personal-brand-building" class="btn-nav">Personal Brand Building</a>
    </li>
        <li>
    <a href="/lists" class="btn-nav">Lists</a>
          </li>
    <li>
      <a href="/profiles" class="btn-nav">Permissionless Mentors</a>
    </li>
  </ul>
</div>

  

  {% for post in site.categories.entrepreneurship %}
  <!-- {% unless post.categories contains "notes" or post.categories contains "lists"%} -->
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  <!-- {% endunless %} -->
  {% endfor %}

  <article class="post">
  <h1>Legend</h1>
    <p>⭐️ Essays I put serious effort into</p>
    <p>🧠 Raw brain dumps</p>
  </article>
</div>