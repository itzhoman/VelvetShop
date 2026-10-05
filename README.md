# Velvet Shop — Fashion Landing Page

A fashion storefront landing page built with HTML, custom CSS, and Bootstrap. The page combines a dress showcase, an automatic hero carousel, product-card effects, and brand storytelling sections.

**Stack:** HTML5 · CSS3

## Highlights

- Bootstrap navigation with a collapsible mobile menu.
- Automatic hero carousel using Bootstrap data attributes.
- CSS-driven scrolling dress-image strip with hover pause.
- Product cards with animated information reveals.
- Craftsmanship section, promotional content, and multi-column footer.
- Media-query styling for different screen sizes.

## Run locally

Clone the repository and open `index.html` in a browser. There is no package installation or build step.

```sh
git clone https://github.com/itzhoman/VelvetShop.git
cd VelvetShop
```

Alternatively, serve the directory with your editor's static-server extension.

## Project structure

| Path | Responsibility |
| --- | --- |
| `index.html` | Page sections, Bootstrap markup, and CDN dependencies |
| `style.css` | Custom layouts, scrolling animation, card effects, and media queries |
| `assets/` | Local clothing images used throughout the page |

## Customize

- Update dress descriptions and calls to action in `index.html`.
- Replace images in `assets/` and preserve matching paths.
- Adjust the scrolling strip and card transitions in `style.css`.

## Current scope

This is a storefront UI showcase. Cart, checkout, account creation, and product APIs are not implemented. Bootstrap and Font Awesome are loaded from CDNs. `index.html` also references a local `script.js` that is not present in the repository; the existing carousel and navbar behavior come from the Bootstrap bundle.

## Try the interaction

1. Resize the page and inspect the navbar and section layouts.
2. Hover the scrolling image strip and product cards.

## Repository

[Source on GitHub](https://github.com/itzhoman/VelvetShop) · [Hooman Hajimohamadi](https://github.com/itzhoman)

Documentation reviewed against source commit [`130e82d`](https://github.com/itzhoman/VelvetShop/commit/130e82d5012b183bac1303db721dd145b98a615a).
