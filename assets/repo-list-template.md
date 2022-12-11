# Repositories


{% for repo in repositories %} - **[{{ repo.name }}]({{ repo.url }})** ({{ repo.stargazerCount }} ⭐) - _{{ repo.description }}_

{% endfor %}
