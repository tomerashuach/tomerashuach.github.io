---
layout: about
title: About
permalink: /
subtitle: PhD student · Interpretability and AI Safety
profile:
  align: right
  image: me.png
  image_circular: true

social: false # includes social icons at the bottom of the page
selected_papers: false # Temporarily disabling selected_papers
announcements:
  enabled: false # Disable layout-level announcements
  scrollable: true
  limit: 10
latest_posts:
  enabled: false # Temporarily disabling latest_posts
---

I'm a PhD student at the Technion in the [Belinkov Lab](https://lab.belinkov.com/), advised by Prof [Yonatan Belinkov](https://belinkov.com/) and supported by the [VATAT Excellence Fellowship in AI](https://che.org.il/scholarships/%D7%9E%D7%9C%D7%92%D7%95%D7%AA-%D7%9C%D7%93%D7%95%D7%A7%D7%98%D7%95%D7%A8%D7%A0%D7%98%D7%99%D7%9D-%D7%9E%D7%A6%D7%98%D7%99%D7%99%D7%A0%D7%99%D7%9D-%D7%91%D7%9E%D7%93%D7%A2%D7%99-%D7%94%D7%A0%D7%AA/). My research is at the intersection of interpretability and AI safety. I study how language models store knowledge and how it can be unlearned, the mechanisms they learn to solve tasks, and latent reasoning, the hidden computations that never appear in their outputs.

<br>

## <a href="{{ '/news/' | relative_url }}" style="color: inherit">News</a>

{% include news.liquid limit=true %}

<div class="mt-4"></div>

## Selected Publications

<div class="publications compact">
  {% bibliography --query @*[selected=true] %}
</div>
