---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---



  <nav class="blue">
    <div class="nav-wrapper">
      <a href="#" class="brand-logo">{{site.title}}</a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
      {% for page in site.pages%}
        <li><a href="{{page.url}}">{{page.title}}</a></li>
          {% endfor %}
      </ul>
    </div>
  </nav>
