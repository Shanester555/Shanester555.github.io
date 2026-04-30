---
title: "Page Title"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/Headshot.png
  actions:
    - label: "Download CV"
      url: "assets/downloads/CV_Shane_Collum.pdf"
      target: "_blank"
intro:
  - excerpt: "Contact me through the website"
    btn_label: "Contact Me"
    btn_class: "btn--primary"
    url: "/contact-me/"
feature_row:
  - image_path: assets/images/Screenshot 2026-04-16 090427.png
    title: "Guns n' Growth"
    excerpt: "A game made for the Global Game Jam 2026 using the Godot game engine"
    btn_label: "View Project"
    btn_class: "btn--primary"
    url: "/projects-global-game-jam/"
  - image_path: assets/images/Screenshot 2026-03-19 141820.png
    alt: "Scrapyard Scramble"
    title: "Scrapyard Scramble"
    excerpt: "A 2D game made for my first semester in university"
    btn_label: "View Project"
    btn_class: "btn--primary"
    url: "/projects-2D-game-semester-1/"
  - image_path: assets/images/Screenshot 2026-04-16 115815.png
    title: "Kackle Kastle"
    excerpt: "A game made with a group of peers for university"
    btn_label: "View Project"
    btn_class: "btn--primary"
    url: "/projects-2D-group-game-semester-2/"
---

{% include feature_row id="intro" type="center" %}
## About Me
I'm Shane Collum. I'm currently a university student studying game design and development. I'm passionate about making games as well as video editing.
{% include button
  url="/about-me/"
  label="Read More"
  class="btn--primary"
%}

## Projects
{% include feature_row %}

