🌆 Seattle, WA  
🔭 Physics/Astronomy BSc. (in progress)  
💻 Building [a game](https://nimows.github.io/) in my spare time.  

🌐 Check out my [personal homepage](https://nimo.ws/).

## Posts

{% for post in site.posts %}
{{ post.date | date: "%b %d, %Y" }} - [{{ post.title }}]({{ post.url }})  
{% endfor %}
