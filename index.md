---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "Home"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "./assets/images/header.jpg"

intro: 
  - excerpt: "Welcome to my website! This website will try to serve as a space for me to record my thoughts on my travels, college career, and my projects in my career"
feature_row:
  - image_path: "./assets/images/Untitled.png"
    alt: "Travel Skyline"
    title: "Travel"
    excerpt: "I absolutely love traveling and experiencing different cultures. I also like to record my thoughts on the places  I've been and the places I want to go."
    url: "/travel/"
    btn_label: "Learn more"
    btn_class: "btn--primary"
  - image_path: "./assets/images/Untitled2.png"
    alt: "Mini500 Tradition"
    title: "College"
    excerpt: "My college experience made me who I am. I have so many lessons learned and adventures I love to share"
    url: "/college/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: "./assets/images/ComputerScience.jpg"
    title: "Career"
    excerpt: "I'm a passionate computer scientist and leader who loves technology. "
    url: "/career/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}