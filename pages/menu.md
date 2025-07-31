---
layout: menu
title: Menu
permalink: /menu/
---

<style>
body {
  background-color: var(--ts-color-black);
  color: var(--ts-color-white);
  min-height: 100vh;
}

.menu-page {
  padding: var(--ts-space-8) var(--ts-space-4);
  max-width: 400px;
  margin: 0 auto;
  text-align: center;
}

.menu-page__links {
  display: flex;
  flex-direction: column;
  gap: var(--ts-space-3);
}

.menu-page__link {
  color: var(--ts-color-white);
  text-decoration: none;
  font-size: var(--ts-text-xl);
  font-weight: var(--ts-font-bold);
  padding: var(--ts-space-3);
}

.menu-page__link:hover {
  opacity: 0.8;
}

.menu-page__link--active {
  opacity: 0.6;
}

.menu-page__close {
  position: absolute;
  top: var(--ts-space-4);
  right: var(--ts-space-4);
  color: var(--ts-color-white);
  text-decoration: none;
  font-size: var(--ts-text-2xl);
  line-height: 1;
  padding: var(--ts-space-2);
}
</style>

<div class="menu-page">
  <a href="{{ site.baseurl }}/" class="menu-page__close">×</a>
  
  <nav class="menu-page__links">
    {% for item in site.data.navigation.main %}
    <a href="{{ site.baseurl }}{{ item.url }}" 
       class="menu-page__link{% if page.url == item.url %} menu-page__link--active{% endif %}">
      {{ item.text }}
    </a>
    {% endfor %}
  </nav>
</div>