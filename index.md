# David R. Stevenson

# My Interests

I am interested in C# and the latest features.

# Get In Touch

<ul>
    <li><a href="https://twitter.com/{{ site.twitter_username }}">Twitter</a></li>
    <li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
</ul>
        
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }} </a>
        </li>
    {% endfor %}
</ul>