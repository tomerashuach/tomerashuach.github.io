---
layout: about
title: About
permalink: /
subtitle: Researcher at Technion – Israel Institute of Technology
profile:
  align: right
  image: me.png
  image_circular: true

social: true # includes social icons at the bottom of the page
selected_papers: false # Temporarily disabling selected_papers
announcements:
  enabled: false # Disable layout-level announcements
  scrollable: true
  limit: 10
latest_posts:
  enabled: false # Temporarily disabling latest_posts
---

I'm a PhD student at the Technion, advised by Prof [Yonatan Belinkov](https://belinkov.com/). My research focuses on the interpretability of language models, with particular emphasis on uncovering their internal mechanisms and understanding how knowledge is acquired and can be unlearned. Currently, I am also a research intern at Google Research, working with [Jonathan Herzig](https://jonathanherzig.github.io/).

### Research Interests

- Interpretability in LLMs
- Knowledge and Unlearning in LLMs
- AI Safety and Alignment

<br>

## <a href="{{ '/news/' | relative_url }}" style="color: inherit">News</a>

{% include news.liquid limit=true %}

## Selected Publications

<div class="publications">
  {% bibliography --query @* %}
</div>
