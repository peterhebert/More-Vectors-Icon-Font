More Vectors Icon Font
======================

A vector icon font providing up to date versions of some of the most popular services out there (or at least the ones I’m using or aware of). Inspired by the [Just Vector](http://alexpeattie.com/projects/justvector_icons/) set.

## Usage

Add the stylesheet to your page:
```html
<link rel="stylesheet" href="morevectors.css">
```

Then to use an icon:

```html
<i class="mv mv-apple"></i>
```

To use with CSS as a pseudo-selector, just copy the CSS from the stylesheet, and apply to a <code>:before</code> or <code>:after</code> pseudo-selector.

```css
.my-element {
  font-family: 'morevectors';
  speak: none;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
  /* Better Font Rendering =========== */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.my-element:before {
  content: "\e600";
}
```
replace the *content* value with the appropriate unicode value for the icon.

## Changelog

2024-05-04:
* Updated demo and README instructions.

2014-05-07:
* Added a LESS version of the stylesheet, as well as a minimized version of the CSS. The CSS is now compiled from the LESS version.

2013-11-26:
* Updated the glyphs to use the Unicode Protected Use Area instead of latin characters.
* Updated icons to latest available versions, dropped icons for decommissioned services, and added a few new ones.

Please see the demo.html file for an example of the web font in usage.

Thanks to [IcoMoon](http://icomoon.io/app/) for their app, which simplifies the font generation process.
