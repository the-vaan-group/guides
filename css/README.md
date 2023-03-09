# CSS

- Use [viewport](https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag)
- Avoid absolute measurement units, e.g., `px`. [1](https://chiamakaikeanyi.dev/sizing-in-css-px-vs-em-vs-rem/) [2](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/)
- Use a "mobile-first" approach[^mobile_first_css] to organize style statements.
- Avoid increasing [CSS specificity](https://css-tricks.com/specifics-on-css-specificity/).
- Use [BEM-like methodology](https://css-tricks.com/bem-101/) to minimize rule cascade depth and interdependency.
- Use [CSS Modules](https://css-tricks.com/css-modules-part-1-need/).
- Use [SASS](https://sass-lang.com/)

[^mobile_first_css]:
    [How To Write Mobile-first CSS](https://zellwk.com/blog/how-to-write-mobile-first-css/) by Zell.

    MQPacker PostCSS Plugin works best with [min-width only media queries](https://github.com/hail2u/node-css-mqpacker#notes)
