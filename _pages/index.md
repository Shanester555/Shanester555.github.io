---
title: "Home Page"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/Headshot.png
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1ePqrAcar-abcMBgLCd7uo0HUbZDd929t/preview"
      target: "_blank"


excerpt: ""
intro: 
  - excerpt: 'I'm Shane Collum. I'm currently a university student studying game design and development. I'm passionate about making games as well as video editing.'
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
    url: "#test-link"
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

