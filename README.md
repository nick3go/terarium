# Terarium

A quiet, interactive glass garden made with plain HTML, CSS, JavaScript and SVG. No build step, libraries, tracking or API keys.

## Play

Feed and pet Moss, make it rain, switch between day and night, rename your creature, and plant ferns, flowers, mushrooms and pebbles. The garden and care levels persist in localStorage in the current browser. Care levels gently decline between visits but never fall below 15. This is a personal garden, not a shared multiplayer world.

## Run

From this folder run `python3 -m http.server 8000`, then open `http://localhost:8000`.

## Publish with GitHub Pages

In repository Settings → Pages, choose **Deploy from a branch**, **main**, **/(root)**, then Save. The site is ready at the repository's Pages URL after deployment. To attach your domain, configure a custom domain in Pages and the corresponding DNS record with your DNS provider. No domain is hardcoded into the site.

All assets use relative paths, so project URLs and custom domains both work. Supports mobile layouts, keyboard controls and reduced motion. Resetting the garden asks for confirmation. Storage is browser-local and may be removed by clearing site data.
