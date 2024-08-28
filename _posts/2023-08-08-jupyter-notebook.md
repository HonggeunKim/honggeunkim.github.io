---
layout: post
title: Segmenting cosmological images using the deep learning technique U-Net
date: 2024-08-04 08:57:00-0400
description: an example of a blog post with jupyter notebook
tags: formatting jupyter
categories: sample-posts
giscus_comments: true
related_posts: false
---

{% assign jupyter_path = "assets/jupyter/bubble_Unet_training_hera_resolution_mask_v3_batch512_epoch5_n64_XYslice.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
