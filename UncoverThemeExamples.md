---
theme: uncover
paginate: true
_paginate: false
title: UNCOVER THEME
header: UNCOVER THEME
footer: A brand-new theme of Marp core
marp: true
---

<!--
_backgroundColor: "#235"
_color: "#fff"
_header: ""
_footer: ""
-->

# UNCOVER THEME <!--fit-->

A brand-new theme of [@marp-team/marp-core](https://github.com/marp-team/marp-core)

---

## Features

- **Simple, minimal, and modern** design
- Always centering by default
  - Inspired from *[reveal.js](https://revealjs.com/)*

---

## How to use

```markdown
<!-- theme: uncover -->

# Hello, uncover theme!
```

---

## Quotes

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed diam justo, vulputate vel vulputate ac, vulputate vitae nulla.

---

<!-- _footer: "Refer to: https://www.youtube.com/watch?v=0E00Zuayv9Q" -->

## Table

|Word|Emoji|Description|
|---:|:---:|:---|
|Pen|:pencil:|I have a pen.|
|Pineapple|:pineapple:|I have pineapple.|
|Apple|:apple:|I have an apple.|
|Pen|:pencil2:|I have a pen.|

---

<!-- _class: invert -->

## `invert` class

The all marp-core themes are supported `invert` class by default.

---

<!--
_backgroundImage: "linear-gradient(to bottom, #000, #222333, #667)"
_color: "#fff"
_class: invert
-->

## Custom background

This page has a gradient background like Keynote.

```yaml
backgroundImage: "linear-gradient(to bottom, #000, #222333, #667)"
color: "#fff"
```

---

## Background image

with filters

![bg 25% blur opacity](https://raw.githubusercontent.com/yhatt/marp/master/images/marp.png)

---

<!-- _footer: "*Photo by [Mathias Appel](https://flic.kr/p/CYCmp5).*" -->

#### :arrow_left: Split backgrounds

![bg left](https://c2.staticflickr.com/2/1688/24269660074_b675f702d7_h.jpg)

---

<!-- _class: left -->

#### Tweak style

You can tweak style by `<style>` tag if you want. The text on this page is aligned to left!

```html
<!-- _class: left -->

<style>
section.left h4, section.left p {
  text-align: left;
}
</style>
```

<style>
section.left h4, section.left p {
  text-align: left;
}
</style>

---


<!--
_header: ""
_footer: "Created by Yuki Hattori ([@yhatt](https://github.com/yhatt))"
-->

### Create a beautiful slide deck! <!--fit-->

with `uncover` theme