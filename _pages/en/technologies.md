---
layout: archive
title: "Technologies"
permalink: /en/technologies/
lang: en
author_profile: true
---

{% include base_path %}

Current stack
------
* **Languages:** Java (primary), Python, Scala, JavaScript
* **Frameworks:** Spring Boot, Django, Play
* **Architecture:** hexagonal architecture (ports and adapters), microservices
* **Cloud and containers:** Kubernetes, Google Cloud Platform (GCP)
* **CI/CD:** GitLab CI/CD
* **Observability:** Grafana, Prometheus
* **Databases:** Oracle, SQL, MongoDB
* **Operating systems:** Linux, Windows

Courses and notes (in Spanish)
------

{% for post in site.technologies reversed %}{% unless post.permalink == "/technologies/stack" %}
* [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endunless %}{% endfor %}
