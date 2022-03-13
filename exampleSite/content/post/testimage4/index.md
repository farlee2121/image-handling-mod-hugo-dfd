---
title: "Test Image #4"
date: 2022-03-12T12:52:01Z
publishDate: 2022-03-12T12:52:01Z
categories:
    - Markdown Images
tags:
    - Example Post
author: "Daniel F. Dickinson"
imageAltAsCaption: true
imageAddClass: markdown-image-wrapper
weight: 40
---

## Via Markdown

no wrapper, alt as caption:

![Tired and exhausted stick figure (illustration)](exhausted-151822.svg#width=1027&height=2048)

## Via figure shortcode (but \<div> as wrapper)

{{< figure class="responsive-div" imagewrapper="div" title="Figure 1: Differences between markdown figures and figure shortcode" src="exhausted-151822.svg" alt="Tired and exhausted stick figure (illustration)" caption="For a figure caption can be different than alt text" width="1027" height="2048" >}}

## Via figure shortcode (originalheight)

{{< figure class="responsive-figure-originalheight" singlesize=true title="Figure 1: Differences between markdown figures and figure shortcode (original height)" src="exhausted-151822.svg" alt="Tired and exhausted stick figure (illustration) (no caption specified so alt as caption)" width="1027" height="2048" >}}

## Via figure shortcode (fullwidth)

{{< figure class="responsive-figure fullwidth" title="Figure 1: Differences between markdown figures and figure shortcode (full width)" src="exhausted-151822.svg" alt="Tired and exhausted stick figure (illustration) (no caption specified so alt as caption)" width="1027" height="2048" >}}
