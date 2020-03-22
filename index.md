<ul>
{% for state in site.states %}
<li><a href="{{state.permalink}}">{{state.title | escape }}</a></li>
{% endfor %}
</ul>
