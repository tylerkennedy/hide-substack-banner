# Chrome Extension Template

This is a base template for building Chrome extensions. 

## Getting Started

* Fork or copy this repo to get a clean base template to start with

* Update `name`, `description`, `default_title`, `permissions`, and `host_permissions` in `manifest.json`

* Replace `icon.png` with a new icon for the extension

* `popup.js` is already embedded in `popup.html` and `content_script.js` is included on all urls.

* [Help setting up TailwindCSS](https://nachoiacovino.com/blog/how-to-setup-tailwind-css-in-a-vanilla-html-project) in the extension

* Run `npm run watch` to watch for new changes and recompile TailwindCSS as updates are made in `popup.html`