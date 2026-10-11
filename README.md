# Nexora | The Global Beauty Growth Network

Complete source export of https://nexora-beauty-network.templateapp67.chatgpt.site/.

## Run locally

Requires Node.js to regenerate pages, and Python 3 for the example server.

```sh
node prepare.mjs
python -m http.server 8080 --directory dist
```

Open http://localhost:8080/.

## Files

- `render-source.js`: page renderers and shared content.
- `prepare.mjs`: generates all 12 static pages.
- `dist/`: ready-to-serve HTML, JavaScript, CSS, original image assets and local fonts.
- `template-catalog.json`: catalog of 28 templates with preview and customization links.
- `reward-image-sources.json`: reward image sources.
- `.openai/hosting.json`: original Sites project and hosting configuration.

## Scope

This is the complete Nexora network website source, not an Android APK. SalonOS signup, login, template editing, jobs and booking destinations link to separately hosted applications; their backend code and databases are not part of this website. No API credentials or user records are included.

## Deployment

Serve `dist/` as the static web root. This GitHub upload is a source snapshot; automatic synchronization with Sites is not configured.

Source Sites commit: `a1a37dc80e6c2f7b947e1a584508ffaa90262354`.
