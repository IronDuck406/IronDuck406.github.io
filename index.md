# My website
# My Projects
List of Projects

# My Interests
List of Interests

# My Blog
Blog about my github stuff
<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

# Get in Touch
Contact info/links to be added later
