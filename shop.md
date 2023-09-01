---
layout: default
title: shop
---


Current
- [Mae]({% link _projects/mae.md %})
- Emergency Medical Delivery Drone Service R&D
- Time Management
- [ConnectedNEO](https://connectedneo.com/)
- Chinese Fluency

2019
- Build Nights Organizing

2018
- Visualizing Messaging History 

2017
- Rollercoaster inside 北京顺义国际学校

2016
- Truck

2015
- Ride-able Ring Motor 

2014
- [First Permitted East Campus Rollercoaster](https://build-its-inprogress.blogspot.com/search/label/Wooden%20Roller%20Coaster)

2013
- [Electric Orbit Wheels](http://www.instructables.com/id/Electric-Orbit-Wheels-Laterally-Propelled-Hub-les/)

 









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
