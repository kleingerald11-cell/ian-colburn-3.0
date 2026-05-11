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

The text below includes both explanations and filler content to show how these components work in practice.


## Building on Seedling Basics
{% include images/figure.html
class="right"
width="48%"
caption="Right-aligned images still work exactly like Seedling. You already know this pattern. [Source](https://rmoa.unm.edu/docviewer.php?docId=nmu1unma028.xml)"
image-path="images/mvh-history-stays.jpg"
%}

FILL TEXT [^note1] FILL TEXT

[^note1]: FOOTNOTE 1

## Your First Scrollybox
FILL TEXT

{% include scrollybox/bg.html
  image-path="images/mvh-women-supervision.jpg"
  above-box-space = "100vh"
  below-box-space = "80vh"
  box-content=' FILL TEXT'
%}


## What Just Happened?
FILL TEXT


## Pull Quotes Still Work
{% include typography/aside.html class="left" text="
This left-aligned pull quote is the same component you learned in Seedling. Sapling essays can mix scrollyboxes with traditional pull quotes depending on what fits your narrative." %}

## Image Carousels for Comparisons

{% assign images =
"images/mvh-menu.jpg,
images/mvh-history-stays.jpg,
images/mvh-room-cost.jpg" | split: ','
%}

{% include images/carousel.html
id="first"
images=images
%}

## Larger Images
{% include images/figure.html class="right" width="60%" caption="This image is 60% width instead of 48%, giving it more visual weight. Adjust widths based on what the image needs. [Source](https://rmoa.unm.edu/docviewer.php?docId=nmu1unma028.xml)" image-path="images/mvh-floorplan.jpg" %}

FILL TEXT

## Block Quotes for Primary Sources

> As of 1967 this was the design for the first floor of La Posada, reflecting the original design of Ernest J. Kump, lead design architect, and the alteration made by Sherman Smith. [Source](https://rmoa.unm.edu/docviewer.php?docId=nmu1unma028.xml)

## What You've Learned in Sapling

## Bibliography

## Ready to Create Your Own?

**New to Xanthan?** Start with the [Getting Started guide](../../../docs/getting-started/) to create your own site first. Once you have a working site, come back here to build your ScrollStory.

**Already have a Xanthan site?** To make your own Sapling essay:

1. **Duplicate this folder** (`scrollstories/sapling/`) and rename it for your topic
2. **Replace the text** with your own content, keeping the structure
3. **Add your own images** to the `images/` folder
4. **Update the front matter** at the top (title, author, date, header image, etc.)
5. **Customize components** - Add or remove scrollyboxes, carousels, and asides as needed

**What makes Sapling different from Seedling?**
- Background scrollyboxes for immersive text overlays
- Image carousels for comparing multiple images
- More sophisticated visual storytelling
- All Seedling components still work

Ready for even more? Check out the [Forest template](../forest/) for advanced features like background switching and side-scrolling.

{% include scrollybox/auto-scroll.html speed=1.5 %}
