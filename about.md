---
title: About
layout: page
---

<img class="title-image" src="{{ page.image }}" alt="{{ page.title }}">


<h1 class="title">{{ page.title }}</h1>

<span class="date">
    <time datetime="{{ page.date | date:"%d-%m-%Y" }}">{{ page.date | date: "%A. %B %d, %Y" }}</time>
    {% if site.read-time %} - {% include read-time.html %}{% endif %}
</span>

{% if site.show-tags %}
    <div class="post-tags">
        {% for tag in page.tags %}
            <a class="item" href="{{ site.url }}/tags/#{{ tag | slugify }}">{{ tag }}</a>
        {% endfor %}
    </div>
{% endif %}

{{content}}

{% if site.post-advance-links contains page.category %}
    <div class="blog-navigation">
        {% if page.previous.hidden == false and page.previous.url %}
            <a class="prev" href="{{ site.url }}{{ page.previous.url }}">&laquo; {{ page.previous.title }}</a>
        {% else %}
            <a class="prev"></a>
        {% endif %}
        {% if page.next.hidden == false and page.next.url %}
            <a class="next" href="{{ site.url }}{{ page.next.url }}">{{ page.next.title }} &raquo;</a>
        {% endif %}
    </div>
{% endif %}


---

## About Me

<p>Lorem Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<h2>Skills</h2>

<ul class="skill-list">
	<li>HTML - Jade - Haml - Erb</li>
	<li>Responsive (Mobile First)</li>
	<li>CSS (Stylus, Sass, Less)</li>
	<li>Css Frameworks (Bootstrap, Foundation)</li>
	<li>Javascript (Design Patterns, Tests)</li>
	<li>AngularJS - ReactJS</li>
	<li>Grunt - Gulp - Yeoman</li>
	<li>Git</li>
	<li>PHP</li>
	<li>Python</li>
	<li>MySQL - MongoDB</li>
	<li>Scrum and Kanban</li>
	<li>TDD e Continuous Integration</li>
</ul>

<h2>Projects</h2>

<ul>
	<li><a href="https://github.com/">Lorem Lorem</a></li>
	<li><a href="https://github.com/">Ipsum Dolor</a></li>
	<li><a href="https://github.com/">Dolor Lorem</a></li>
</ul>
