---
layout: default
title: Content Strips
parent: UI Components
nav_order: 1
---

# Content Strips
{: .no_toc }
## Table of contents
{: .no_toc .text-delta }
1. TOC
{:toc}

---

## What are they?
Content strips are used to organize and group information. Every element used on the website must be placed on a content strip so it can be properly styled and displayed to users. Organize elements into content strips so that only similar content shares a strip.

---

## Basic usage

### HTML structure

``` html
<div class="content-strip">
  <div class="flex-item">
    <!-- ... content ... -->
  </div>
</div>
```

### Guidelines
When content strips of the same background color are used adjacent to each other, apply the class `.content-strip--no-bottom-padding` to all but the last content strip of that color.  

Content Strips that are centered should not contain elements other than a title and a paragraph. Do not use buttons, images, graphs, or multiple paragraphs.  

The first content strip at the top of the page should contain the page title and, if applicable, a small description or introduction to the page. Additionally, the background should be the website's primary color and the contents of the content strip should be centered. This style of content strip should only be used in this fashion.

---

## Variants

### Standard

<script async src="//jsfiddle.net/Jack_Buehner/p8s3uyzx/5/embed/html,result/dark/"></script>

### Primary background

<script async src="//jsfiddle.net/Jack_Buehner/p8s3uyzx/6/embed/html,result/dark/"></script>

### Secondary background

<script async src="//jsfiddle.net/Jack_Buehner/p8s3uyzx/8/embed/html,result/dark/"></script>

### Extra padding

<script async src="//jsfiddle.net/Jack_Buehner/p8s3uyzx/10/embed/html,result/dark/"></script>

### Reduced padding

<script async src="//jsfiddle.net/Jack_Buehner/p8s3uyzx/17/embed/html,result/dark/"></script>

### Centered
<script async src="//jsfiddle.net/Jack_Buehner/p8s3uyzx/15/embed/html,result/dark/"></script>

### Title
<script async src="//jsfiddle.net/Jack_Buehner/p8s3uyzx/13/embed/html,result/dark/"></script>

---

## Style customization

### CSS classes

| CSS class | Description |
|---|---|
| content-strip--primary | Sets the background of the content strip to the primary color. Text color also adjusts to white to be legible on a dark background. |
| content-strip--secondary | Sets the background of the content strip to the secondary color. Text color also adjusts to white to be legible on a dark background. |
| content-strip--center | Horizontally centers the contents of the content strip. |
| content-strip--extra-padding | Adds extra vertical padding to the content strip |
| content-strip--reduced-padding | Removes excess vertical padding from the content strip.  |
| content-strip--no-bottom-padding | Removes bottom padding from the content strip. Should only be used when followed by another content strip of the same color background. |
