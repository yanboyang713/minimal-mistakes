---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: homePage.jpg
  caption:
excerpt: 'A flexible two-column Jekyll theme. Perfect for personal sites, blogs, and portfolios hosted on GitHub or your own server.'
feature_row:
  - image_path: avatar/cycle/cycle1023x540.png
    alt: "aboutMe"
    title: "About Me"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/about/"
    btn_label: "Learn More"
  - image_path: blog.png
    alt: "fully responsive"
    title: "Blog"
    excerpt: "Built on HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/docs/layouts/"
    btn_label: "researchProject"
  - image_path: researchProject.jpg
    alt: "researchProject"
    title: "researchProject"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it, whatever!"
    url: "/docs/license/"
    btn_label: "Learn More"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
