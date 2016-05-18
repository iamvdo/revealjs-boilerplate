## iamvdo's RevealJS Boilerplate

Changes from RevealJS:

- Add custom CSS theme in `css/theme/source/iamvdo.scss`
  - Specific fonts in `css/fonts`
  - Add link CSS in index.html
- Add `iamvdo language-css` classes on `.reveal` element
- Add bottom bar (`.info-overlay`)

```html
<div class="info-overlay" id="info-twitter">
  <a href="https://twitter.com/iamvdo">@iamvdo</a>
</div>
<div class="info-overlay" id="info-slides">
  <a href="http://slides.iamvdo.me/kiwiparty16">slides.iamvdo.me/kiwiparty16</a>
</div>
```

- Add dependencies (prismjs, nav)

```js
{ src: 'plugin/prismjs/prism.js', async: true, callback: function () { Prism.highlightAll(); } }
```

- Add favicon: `<link rel="icon" href="http://iamvdo.me/images/favicon.png"/>`
- Update title and description
- Remove zenburn.css


CSS Pseudo-Components:

- `.Showcase`
- `.Showcase-text`
- `.Jumbo`
- `.Jumbo-title`
- `.Jumbo-title--big`
- `.Part`
- `.Image--unstyled`
- `.Image--side`
- `.Image-legend--side`
- `.Image--fakealign`
- `.Image-legend`
- `.Subtitle--discreet`
- `.Point--plus`


Atomic CSS:

- `.u-aligncenter`
- `.u-alignmiddle`
- `.u-code`
- `.u-small`
- `.u-margin`
- `.u-no`
- `.u-margin-auto`
- `.u-svg`
- `.u-row`, `.u-row *`
