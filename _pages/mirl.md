---
layout: archive
title: "Machine Intelligence and Robot Learning (MIRL)"
permalink: /mirl/
author_profile: true

author:
  avatar: /assets/images/mirlImage.png
  name: "MIRL Lab"
  bio: "Machine Intelligence and Robot Learning Lab"
---


The **Machine Intelligence and Robot Learning (MIRL)** Lab at the University of Ottawa develops **data-efficient, safe, and adaptive machine learning systems**, with a focus on reinforcement learning and deep learning for real-world applications.

Our research lies at the intersection of **machine learning, robotics, and decision-making under uncertainty**, with the goal of enabling intelligent agents to operate reliably in complex and dynamic environments.

---

## Research Focus

### Reinforcement Learning
- Goal-conditioned and model-based RL
- Continual RL
- Safe and reliable learning  
- Sample-efficient exploration  
- Sim-to-real transfer  

### Applications
- Robotics and autonomous systems  
- Healthcare and biomedical systems  
- Industrial automation  
- AI for science, environment, and climate  

---

## People

### Current Members

#### PhD Students

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

{% for person in site.data.people.phd %}
  {% unless person.alumni %}
  <div style="width: 200px; text-align: center;">
    <img src="{{ person.image | default: '/assets/images/mirlImage.png' }}" 
         style="width:150px; height:150px; object-fit:cover; border-radius:50%;"><br>
    <strong>{{ person.name }}</strong><br>
    <small>{{ person.description }}</small>
  </div>
  {% endunless %}
{% endfor %}

</div>

---

#### MSc Students

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

{% for person in site.data.people.msc %}
  {% unless person.alumni %}
  <div style="width: 200px; text-align: center;">
    <img src="{{ person.image | default: '/assets/images/mirlImage.png' }}" 
         style="width:150px; height:150px; object-fit:cover; border-radius:50%;"><br>
    <strong>{{ person.name }}</strong><br>
    <small>{{ person.description }}</small>
  </div>
  {% endunless %}
{% endfor %}

</div>

---

#### Undergraduate Researchers

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

{% for person in site.data.people.undergrad %}
  {% unless person.alumni %}
  <div style="width: 200px; text-align: center;">
    <img src="{{ person.image | default: '/assets/images/mirlImage.png' }}" 
         style="width:150px; height:150px; object-fit:cover; border-radius:50%;"><br>
    <strong>{{ person.name }}</strong><br>
    <small>{{ person.description }}</small>
  </div>
  {% endunless %}
{% endfor %}

</div>
---

### Alumni

#### PhD Alumni

- **Payam Parvizi** (PhD, 2026)  
  *Wavefront Sensorless Adaptive Optics for Free-space Satellite-to-Ground Communication using Online Reinforcement Learning*  
  Co-supervised with Prof. Davide Spinello (uOttawa) and Prof. Ross Cheriton (NRC)

---

#### MSc Alumni

- **Fahim Shahriar** (MSc, 2026)  
  *Simplifying Goal Representations with Masks in Vision-based Reinforcement Learning*  
  Co-supervised with Prof. Rupam Mahmood (University of Alberta / Amii)

- **Alireza Azimi** (MSc, 2026)  
  *Reinforcement Learning for Robotics*  
  Co-supervised with Prof. Rupam Mahmood (University of Alberta / Amii)

- **Runnan Zou** (MASc, 2024)  
  *Reinforcement Learning in Wavefront Sensorless Adaptive Optics Systems*  
  Co-supervised with Prof. Davide Spinello (uOttawa) and Prof. Ross Cheriton (NRC)

---

#### Undergraduate Alumni

- **Zahra Suleymanova** (Research Assistant, 2026)  
  *Beyond Information Sufficiency: Observation-Action Space Alignment in Robotic Reinforcement Learning*

- **Vishal Bhrat** (Research Assistant, 2026)  
  *Beyond Information Sufficiency: Observation-Action Space Alignment in Robotic Reinforcement Learning*

---

## Selected Projects

*(Coming soon — highlight key research projects, open-source work, and systems)*

---

## Join the Lab

We are always looking for motivated students interested in reinforcement learning, deep learning, and robotics.

Apply [here](https://forms.cloud.microsoft/r/Hij4NX6dzu)

Prospective MSc and PhD students should indicate **Colin Bellinger** as their preferred supervisor when applying to uOttawa EECS.

---

## Affiliations

- University of Ottawa — School of EECS  
- IARA Lab  
- Vector Institute (Faculty Affiliate)
``
