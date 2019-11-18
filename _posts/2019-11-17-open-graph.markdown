---
layout: post
title: Open Graph
date: 2019-11-17
---

**What is Open Graph and how do you make use of it?**

Open Graph is a very important tool because it allowes to post the link to the website on social media so that a link looks good: with a picture, name, url, etc.
All one has to do is to tell social media what info should be publiced in the preview.
Jekyll has a jekyll-seo-tag plugin which sets all the properties which are written on **template.html** page. Then the plugin reads the values from my config.yaml file.

~~~~
title: Maria Roze
type: Webblog
description: This website was created by Maria Roze for submissions of future tasks.
url: "https://mariiamira.github.io/"
image: images/myPhoto.jpg
~~~~

Apart from that I have used a template of sharing buttons from [Jekyllcodex.org](https://jekyllcodex.org/without-plugin/share-buttons/) and imported it to the footer
in order to check how OG works and to make it more user friendly.

![share_preview](../../../images/share.jpg)