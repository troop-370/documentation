---
layout: default
title: Typography
parent: UI Components
nav_order: 2
---

# Typography
{: .no_toc }
## Table of contents
{: .no_toc .text-delta }
1. TOC
{:toc}

---

## General information
Troop 370 uses the material design components (MDC) typography system.

MDC Typography has thirteen styles:

* Headline 1
* Headline 2
* Headline 3
* Headline 4
* Headline 5
* Headline 6
* Subtitle 1
* Subtitle 2
* Body 1
* Body 2
* Caption
* Button
* Overline

---

## Basic usage

### HTML structure within content strips (always use this)
``` html
<div class="content-strip">
  <div class="flex-item">
    <h1>Heading</h1>
    <p>Paragraph Text</p>
  </div>
</div>
```

### HTML structure without content strip

Avoid using typography outside of content strips unless absolutely necessary. Typography outside of content strips will not be aligned and scaled to best fit the user's screen.

``` html
<body class="mdc-typography">
  <h1 class="mdc-typography--headline1">Big header</h1>
</body>
```

### Guidelines
In the type scale, headlines span from a range of 1 through 6. Headlines are the largest text on the screen, reserved for short, important text or numerals. Troop 370 typically uses headline scales 4 through 6, which are respectively assigned to `<h1>`, `<h2>`, and `<h3>` in content strips. Use the IBM Plex Sans font for headlines (applied by default in content strips).

Body text comes in ranges 1-2, and it’s typically used for long-form writing as it works well for small text sizes. Only use Body 1 on Troop 370 websites. Use the Roboto font for body text (applied by default in content strips).

Button text is a call to action used in different types of buttons (such as text, outlined and contained buttons). Button text on Troop 370 websites are automatically capitalized and uses the IBM Plex Sans font.

---

## Style customization

### CSS classes

Some components have a set typographic style. For example, an `<h1>` or `<p>` within content strips use Headline 4 and Body 1 styles, respectively.

If you want to set the typographic style of an element which is not a predefined component, you can apply the following CSS classes.

CSS Class | Description
--- | ---
`mdc-typography` | Sets the font to Roboto
`mdc-typography--headline1` | Sets font properties as Headline 1
`mdc-typography--headline2` | Sets font properties as Headline 2
`mdc-typography--headline3` | Sets font properties as Headline 3
`mdc-typography--headline4` | Sets font properties as Headline 4
`mdc-typography--headline5` | Sets font properties as Headline 5
`mdc-typography--headline6` | Sets font properties as Headline 6
`mdc-typography--subtitle1` | Sets font properties as Subtitle 1
`mdc-typography--subtitle2` | Sets font properties as Subtitle 2
`mdc-typography--body1` | Sets font properties as Body 1
`mdc-typography--body2` | Sets font properties as Body 2
`mdc-typography--caption` | Sets font properties as Caption
`mdc-typography--button` | Sets font properties as Button
`mdc-typography--overline` | Sets font properties as Overline
