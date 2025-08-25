---
title: About
layout: page
---

<img src="{{ site.url }}/{{ site.picture }}" alt="Profile Image" style="width:150px; border-radius:50%; margin-bottom:10px;">

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


---

<h2 class="contact-heading">Please do not hesitate to contact me:</h2>

<div class="about-social">
  {% if site.linkedin %}
    <a class="link" href="https://www.linkedin.com/in/{{ site.linkedin }}" target="_blank" rel="noopener" aria-label="LinkedIn">
      <i class="fa-brands fa-linkedin"></i>
    </a>
  {% endif %}
  {% if site.github %}
    <a class="link" href="https://github.com/{{ site.github }}" target="_blank" rel="noopener" aria-label="GitHub">
      <i class="fa-brands fa-github"></i>
    </a>
  {% endif %}
  {% if site.email %}
    <a class="link" href="mailto:{{ site.email }}" rel="noopener" aria-label="Email">
      <i class="fa-regular fa-envelope"></i>
    </a>
  {% endif %}
  {% if site.twitter %}
    <a class="link" href="https://twitter.com/{{ site.twitter }}" target="_blank" rel="noopener" aria-label="Twitter">
      <i class="fa-brands fa-x-twitter"></i>
    </a>
  {% endif %}
</div>


