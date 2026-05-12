---
title: Sapling
author: Fred Gibbs
layout: scrollstory
date: 2025-07-21
header-image: images/sapling-card.png
thumbnail: images/sapling-card.png
summary: Our Sapling essay uses a few more features than our Seed essay, including the simplest scrolly box.
header-title:
header-position: 0px
toc-section: second
geo: [41.240000, -81.550000]
placename: Cuyahoga Valley National Park
tags:
    - history
    - nature
---

# A Sapling Essay

**What makes this a "Sapling" essay?** It includes everything from Seedling (headings, images, footnotes, pull quotes) plus immersive components: text overlaying background images, image carousels for c

## Building on Seedling Basics
{% include images/figure.html
class="right"
width="48%"
caption="Right-aligned images still work exactly like Seedling. You already know this pattern. [Source](https://rmoa.unm.edu/docviewer.php?docId=nmu1unma028.xml)"
image-path="images/mvh-history-stays.jpg"
%}

[^note1]
[^note1]:

## Your First Scrollybox

{% include scrollybox/bg.html
  image-path="images/mvh-women-supervision.jpg"
  above-box-space = "100vh"
  below-box-space = "80vh"
  box-content=' One stated reason for building a men-only dorm is that Hokona Hall could be freed up to be used as a women-only dorm, where they would have supervision "of the best sort".'
%}

{% include typography/aside.html class="left" text="
This left-aligned pull quote is the same component you learned in Seedling. Sapling essays can mix scrollyboxes with traditional pull quotes depending on what fits your narrative." %}

{% assign images =
"images/mvh-menu.jpg,
images/mvh-history-stays.jpg,
images/mvh-room-cost.jpg" | split: ','
%}

{% include images/carousel.html
id="first"
images=images
%}



{% include images/figure.html class="right" width="60%" caption="This image is 60% width instead of 48%, giving it more visual weight. Adjust widths based on what the image needs. [Source](https://rmoa.unm.edu/docviewer.php?docId=nmu1unma028.xml)" image-path="images/mvh-floorplan.jpg" %}

> As of 1967 this was the design for the first floor of La Posada, reflecting the original design of Ernest J. Kump, lead design architect, and the alteration made by Sherman Smith. [Source](https://rmoa.unm.edu/docviewer.php?docId=nmu1unma028.xml)

{% include scrollybox/auto-scroll.html speed=1.5 %}
