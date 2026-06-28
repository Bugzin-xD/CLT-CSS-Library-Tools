# CLT (CSS Library Tools)

A lightweight CSS and JavaScript library focused on productivity, simplicity and customization.

---

# About

CLT (CSS Library Tools) was created to speed up front-end development using native HTML, CSS and JavaScript.

Instead of replacing the way you build websites, CLT automates repetitive tasks while keeping your code clean, readable and easy to customize.

The library combines modern CSS, lightweight JavaScript and native browser features to create responsive interfaces with minimal code.

---

# Features

* CSS Variables theme system
* Ready-to-use components
* Intelligent JavaScript helpers
* Automatic Floating Labels
* Password Reveal
* Button states
* Loading buttons
* Automatic Alerts
* Copy to Clipboard helper
* Download helper
* Responsive layouts
* Custom Scrollbar
* Scroll Reveal Animation
* Zero dependencies

---

# Installation

Include the required files in your project.

```html
<link rel="stylesheet" href="clt-dark-minimalist.css">
<link rel="stylesheet" href="clt.min.css">

<script src="clt-functions.js"></script>
```

---

# Components

## Card

```html
<div class="clt-card">
    <h2 class="clt-card-title">
        Card Title
    </h2>

    <p class="clt-card-text">
        Card text.
    </p>

    <button class="clt-card-button">
        Button
    </button>
</div>
```

---

## Title

```html
<h1 class="clt-title">
    Hello World
</h1>
```

---

## Paragraph

```html
<p class="clt-p">
    Paragraph.
</p>
```

---

## Link

```html
<a class="clt-link">
    Link
</a>
```

---

## Input

Simply use the `clt` attribute.

```html
<input clt="Name">
```

Automatically creates:

* Floating Label
* Input Group
* Placeholder
* Responsive layout

---

## Password Reveal

```html
<input
type="password"
clt="Password"
reveal>
```

Automatically creates a show/hide password control.

---

## Buttons

Default

```html
<button class="clt-card-button">
    Button
</button>
```

Active

```html
<button
class="clt-card-button"
clt="on">
    Button
</button>
```

Disabled

```html
<button
class="clt-card-button"
clt="off">
    Button
</button>
```

Loading

```html
<button
class="clt-card-button"
clt="loading">
    Loading...
</button>
```

---

## Alerts

Default

```html
<clt-alert>
Message
</clt-alert>
```

Warning

```html
<clt-alert type="warn">
Message
</clt-alert>
```

Danger

```html
<clt-alert type="alert">
Message
</clt-alert>
```

---

## Loader

```html
<div class="clt-loader"></div>
```

---

## Copy Helper

Copy the contents of any element.

```html
<pre id="example-code">
Hello World
</pre>

<button
class="clt-card-button"
clt-copy="example-code">
Copy
</button>
```

---

## Download Helper

Downloads a local file.

```html
<button
class="clt-card-button"
clt-download="clt-v1.0.zip">
Download
</button>
```

Optional custom download name:

```html
<button
class="clt-card-button"
clt-download="downloads/library.zip"
download-name="CLT.zip">
Download
</button>
```

---

## Footer

```html
<footer class="clt-footer">
    <p class="clt-footer-text">
        Footer
    </p>

    <p class="clt-footer-right">
        Loaden TI
    </p>
</footer>
```

---

## Header

```html
<header class="clt-header"></header>
```

---

## Navbar

```html
<nav class="clt-navbar"></nav>
```

---

## Main

```html
<main class="clt-main"></main>
```

---

## Section

```html
<section class="clt-section"></section>
```

---

## Container

```html
<div class="clt-container"></div>
```

---

## Center

```html
<div class="clt-center"></div>
```

or

```html
<div class="clt-flex-center"></div>
```

---

## Scroll Animation

```html
<body class="clt-animation-scroll">
```

Every direct child element will animate when entering the viewport.

---

# Customization

CLT is fully based on CSS Variables.

Override any variable inside your own `:root`.

Example:

```css
:root {
    --clt-surface: #202020;
    --clt-text: white;
    --clt-border-color: #00aaff;
}
```

No library files need to be modified.

---

# Philosophy

CLT follows four principles:

* Simplicity
* Performance
* Native HTML
* Customization

The library automates repetitive tasks while keeping developers in control of their HTML, CSS and JavaScript.

---

# Browser Support

Recommended browsers:

* Chrome
* Edge
* Firefox
* Opera
* Brave

---

# License

Copyright © Loaden TI

All rights reserved.
