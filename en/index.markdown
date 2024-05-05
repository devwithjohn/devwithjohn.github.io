---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: "DWJ's Products"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image:  /assets/img/home-splash.jpg
  actions:
    - label: "Training courses"
      url: "https://github.com/mmistakes/minimal-mistakes/"
    - label: "AWS Hand-Ons labs"
      url: "https://github.com/mmistakes/minimal-mistakes/"
    - label: "X-plat book reader"
      url: "https://github.com/mmistakes/minimal-mistakes/"

  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "I provide quality courses, practical lab systems, and learning resources to help make mastering cutting-edge technologies simple for everyone."
intro: 
  - excerpt: "You **ALREADY KNOWN** that learning cutting-edge technologies is crucial 🔑 <br> But it's **SLOW**, right? <br><br> 🖐🖐🖐🖐🖐 Don't worry!! 🖐🖐🖐🖐🖐 <br> I can **SPEED UP 🚀** your progress with **MY SOLID EXPERIENCE 🤝** <br>👇 See what I did 👇"
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}