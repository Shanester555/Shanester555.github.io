---
title: "Page Title"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/placeholder.png
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1ePqrAcar-abcMBgLCd7uo0HUbZDd929t/preview"
      target: "_blank"


excerpt: "You can add text here."
intro: 
  - excerpt: 'You can also add text like this....'
feature_row:
  - image_path: assets/images/Headshot.png
    alt: "Profesional headshot"
    title: "More about me"
    excerpt: "General informaion about me and my skills"
    btn_label: "Read More"
    btn_class: "btn--primary"
    url: "/about-me/"
  - image_path: assets/images/Screenshot 2026-03-19 141820.png
    alt: "Scrapyard Scramble"
    title: "Scrapyard Scramble"
    excerpt: "Look through various projects I made in my own time and university"
    btn_label: "View Projects"
    btn_class: "btn--primary"
    url: "/projects/"
  - image_path: assets/images/Headshot.png
    title: "Profesional Headshot"
    excerpt: "Contact me through the website"
    btn_label: "Contact Me"
    btn_class: "btn--primary"
    url: "/contact-me/"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

