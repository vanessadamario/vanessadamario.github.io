<div class="hero" style="text-align:center">
  <img src="{{ site.author.avatar | relative_url }}" width="180">
  <h1>{{ site.title }}</h1>
  <div class="links">
    <a href="{{ site.profile_links.cv | relative_url }}" class="button">CV</a>
    <a href="{{ site.profile_links.scholar }}" target="_blank">Google Scholar</a>
    <a href="{{ site.profile_links.github }}" target="_blank">GitHub</a>
    <a href="{{ site.profile_links.linkedin }}" target="_blank">LinkedIn</a>
    <a href="{{ site.profile_links.email }}">Email</a>
  </div>
</div>

<div class="section">
  <h2>About</h2>
  <p>
    I work at the intersection of <strong>AI, healthcare, and global health</strong>, building
    <strong>trustworthy & accessible ML tools</strong> for medicine. My background spans
    machine learning, signal processing, and computational neuroscience, with applications
    from epilepsy to pediatric endocrinology.
  </p>
  <p class="small">
    Assistant Professor in Decision Sciences, H. Wayne Huizenga College of Business and Entrepreneurship, Nova Southeastern University · Former Postdoctoral Researcher, MIT & Fujitsu
  </p>
</div>

<div class="section">
  <h2>Vision</h2>
  <p>
    Technology should reduce inequities, not widen them. My research focuses on:
  </p>
  <ul>
    <li>Generalization across populations and data distributions</li>
    <li>Digital health for <em>low-resource settings</em> (Galápagos Islands, Jamaica)</li>
    <li>Bias-aware, transparent tools that support clinical decision-making</li>
  </ul>
</div>

<hr class="soft"/>

<div class="section">
  <h2>Current Projects</h2>
  {% for p in site.data.projects %}
    <div class="card">
      <h3>{{ p.title }}</h3>
      <p>{{ p.summary }}</p>
      {% if p.links %}
      <p class="small">
        {% for l in p.links %}<a href="{{ l.url }}" target="_blank">{{ l.label }}</a>{% if forloop.last == false %} · {% endif %}{% endfor %}
      </p>
      {% endif %}
    </div>
  {% endfor %}
</div>

<hr class="soft"/>

<div class="section">
  <h2>Publications</h2>
  <p class="small">Check here for updated list <a href="{{ site.profile_links.scholar }}" target="_blank">Google Scholar</a>.</p>
</div>

<hr class="soft"/>

<div class="section">
  <h2>Teaching</h2>
  <div class="card">
    <h3>Current</h3>
    <ul>
      {% for c in site.data.new_courses %}
        <li><strong>{{ c.name }}</strong> — {{ c.note }}</li>
      {% endfor %}
    </ul>
  </div>
  <div class="card">
    <h3>Previously Taught</h3>
    <ul>
      {% for c in site.data.new_courses %}
        <li><strong>{{ c.name }}</strong> — {{ c.note }}</li>
      {% endfor %}
    </ul>
  </div>
</div>

<hr class="soft"/>

<div class="section footer-links">
  <a href="{{ site.profile_links.github }}" target="_blank">GitHub</a>
  ·
  <a href="{{ site.profile_links.linkedin }}" target="_blank">LinkedIn</a>
  ·
  <a href="{{ site.profile_links.scholar }}" target="_blank">Google Scholar</a>
</div>
