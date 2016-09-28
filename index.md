---
layout: default
---
# New Site Home Page

See my new pages!

* [About](/about/)
* [FAQ](/faq/)
* [Procedure](/procedure/)

## Posts

<ul>
{% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title | escape }}</a>
        </h2>
      </li>
{% endfor %}
</ul>

# More 
For more info see these pages:

- page 1
- page 2
