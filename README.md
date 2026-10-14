# WebPy — Python Console by CGL+

WebPy is a browser-based Python console for `webpy.crazygamelabs.co.uk`.

## Features
- Runs Python in the browser with Pyodide/WebAssembly; no local Python installation is required.
- Persistent Python globals between runs, output and error display, and example snippets.
- Responsive dark interface with CGL+ yellow branding.
- Code stays in the browser session; the page does not send submitted code to a CGL+ backend.

## Deploy
Deploy this repository as a static site using GitHub Pages or Cloudflare Pages. The entry point is `index.html`. Configure `webpy.crazygamelabs.co.uk` as the custom domain in your hosting provider and configure its DNS as instructed by that provider.

The Pyodide runtime is loaded from jsDelivr, so an internet connection is required to start the console. This is a browser sandbox, not a server-side Python environment; filesystem and operating-system access are not available like they are in a normal Python installation.
