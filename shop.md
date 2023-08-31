---
layout: default
title: shop
---


Current
- [Truckv2]({% link _projects/truckv2.md %})
- Emergency Medical Delivery Drone Service R&D
- Time Management
- ConnectedNEO
- Chinese Fluency

2019
- Build Nights Organizing

2018
- Visualizing Messaging History 

2017
- Rollercoaster inside 北京顺义国际学校

2016
- Truck v1

2015
- Ride-able Ring Motor 

2014
- First Legal East Campus Rollercoaster

2013
- Electric Orbit Wheels

 









---
# Testing Jekyll Features
<ul>
  {% for project in site.projects %}
    <li>
      <h2><a href="{{ project.url }}">{{ project.name }}</a></h2>
      <h3>{{ project.position }}</h3>
      <p>{{ project.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
---
