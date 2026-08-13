---
title: "The Translational Chronopsychiatry Lab"
layout: splash
permalink: /
---

<div class="clab-band clab-band--blue">
<div class="clab-inner">
<div class="clab-hero">
<div markdown="1">

# The Translational Chronopsychiatry Lab

Wir erforschen, wie Schlaf, Licht und zirkadiane Rhythmen affektive
Erkrankungen beeinflussen — von der Grundlagenforschung bis zur klinischen
Anwendung.

[Mehr erfahren](/about/){: .btn .btn--inverse}

</div>
<div>
  <img src="/assets/images/hero-clock-brain.png" alt="Circadian clock and brain illustration">
</div>
</div>
</div>
</div>

<div class="clab-band clab-band--grey">
<div class="clab-inner">

## Why sleep, sunlight and circadian rhythms are relevant to affective disorders

<div class="clab-grid clab-grid--4">
{% for topic in site.data.topics %}
  <div class="clab-topic">
    <img src="{{ topic.icon }}" alt="{{ topic.title }}">
    <h3>{{ topic.title }}</h3>
    <p>{{ topic.text }}</p>
  </div>
{% endfor %}
</div>

</div>
</div>

<div class="clab-band">
<div class="clab-inner">

## Meet the Chrono-Warriors

<div class="clab-grid clab-grid--team">
{% for person in site.data.team %}
  <div class="clab-person">
    <img src="{{ person.photo }}" alt="{{ person.name }}">
    <div class="name">{{ person.name }}</div>
    <div class="role">{{ person.role }}</div>
    <div class="focus">{{ person.focus }}</div>
    {% if person.url %}<a href="{{ person.url }}" class="btn btn--primary btn--small">Read bio</a>{% endif %}
  </div>
{% endfor %}
</div>

</div>
</div>

<div class="clab-band clab-band--blue">
<div class="clab-inner">

## Chronobiological Research Methods

<div class="clab-grid clab-grid--methods">
{% for method in site.data.methods %}
  <div class="clab-method">
    <img src="{{ method.image }}" alt="{{ method.title }}">
    <div class="title">{{ method.title }}</div>
    <div class="tag">{{ method.tag }}</div>
  </div>
{% endfor %}
</div>

</div>
</div>

<div class="clab-band clab-band--grey">
<div class="clab-inner" markdown="1">

## Get in touch

Interested in collaborating? [Write to us](/contact/).

</div>
</div>
