# This week in Vim

To subscribe this blog, join t.me/vimweek


<ul>
    {% for post in site.categories.blog %}
            <li>
               <h5><a href="{{ post.url }}">{{ post.title }}</a></h5>
               <span class="post-date">{{ post.date | date_to_string }}</span>
               <p>{{ post.excerpt | truncatewords: 100 }}</p>
            </li>
    {% endfor %}
</ul>
