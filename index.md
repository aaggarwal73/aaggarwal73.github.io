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
  - excerpt: 'Welcome to my website! This website will try to serve the function of my blog space for georgia tech'
feature_row:
  - image_path: "./assets/images/untitled.png"
    alt: "Travel Skyline"
    title: "Travel"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/travel/"
    btn_label: "Learn more"
    btn_class: "btn--primary"
  - image_path: "./assets/images/Untitled2.png"
    alt: "Mini500 Tradition"
    title: "College"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/college/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: "./assets/images/ComputerScience.jpg"
    title: "Career"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/career/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}