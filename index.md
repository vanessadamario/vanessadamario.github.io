
---

<div class="hero" style="text-align:center">
  <img src="{{ site.author.avatar | relative_url }}" alt="Vanessa D’Amario" />
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
    Assistant Professor, Nova Southeastern University · Former Postdoctoral Researcher, MIT & Fujitsu
  </p>
</div>

<div class="section">
  <h2>Vision</h2>
  <p>
    Technology should reduce inequities, not widen them. My research focuses on:
  </p>
  <ul>
    <li>Generalization across populations and data distributions</li>
    <li>Digital health for <em>low-resource settings</em> (Jamaica, Galápagos)</li>
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
  <h2>Selected Publications</h2>
  {% for pub in site.data.publications limit:6 %}
    <div class="card">
      <h3>{{ pub.title }}</h3>
      <p class="small">{{ pub.authors }} ({{ pub.year }}). <em>{{ pub.venue }}</em></p>
      <p class="small">
        {% if pub.pdf %}<a href="{{ pub.pdf }}" target="_blank">PDF</a>{% endif %}
        {% if pub.arxiv %}{% if pub.pdf %} · {% endif %}<a href="{{ pub.arxiv }}" target="_blank">arXiv</a>{% endif %}
        {% if pub.doi %}{% if pub.pdf or pub.arxiv %} · {% endif %}<a href="{{ pub.doi }}" target="_blank">DOI</a>{% endif %}
      </p>
    </div>
  {% endfor %}
  <p class="small">Full list on <a href="{{ site.profile_links.scholar }}" target="_blank">Google Scholar</a>.</p>
</div>

<hr class="soft"/>

<div class="section">
  <h2>Talks & Teaching</h2>
  <div class="card">
    {% for t in site.data.talks %}
      <p><strong>{{ t.title }}</strong> — {{ t.event }} ({{ t.year }}){% if t.link %} · <a href="{{ t.link }}" target="_blank">link</a>{% endif %}</p>
    {% endfor %}
  </div>
  <div class="card">
    <h3>Courses</h3>
    <ul>
      {% for c in site.data.courses %}
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
