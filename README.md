# Single Page Project

A growing collection of practical, standalone HTML tools. The homepage brings the tools together in one place; open any tool in your browser and use it directly, with no app installation or project-wide build step.

## What you’ll find here

Each tool is intended to be its own focused page: lightweight, easy to access, and built with familiar web technologies. The collection can grow over time as new single-page tools are added.

## Getting started

1. Visit the published GitHub Pages site, or clone or download this repository.
2. Choose a tool from the homepage.
3. Follow the instructions on that page.

To use the pages locally, open `index.html` in a modern web browser. There is no project-wide package installation or build command. Some tools may load optional fonts or libraries from a CDN, so an internet connection may be needed for those features.

## Project structure

```text
Single-Page-Project/
├── index.html             # Collection homepage and tool directory
├── resume-builder.html    # Resume Builder tool
├── qr-code-generator.html # QR Code Generator tool
└── README.md
```

Add new tools as standalone HTML pages in the repository root, then add a descriptive link to the homepage so they are easy to find. Keep each page focused and include any tool-specific usage instructions with it.

## Built with

- HTML
- CSS
- JavaScript

The QR Code Generator supports plain text and links, Wi-Fi network details, vCard contacts, email, phone calls, SMS, map locations, and calendar events. Customize square, rounded, or circular modules and export as PNG, JPEG, SVG, or WebP. It uses QRCode.js from cdnjs, so an internet connection is required to generate codes. Scanner behavior depends on the phone and QR reader.

## Publishing with GitHub Pages

In the repository settings, open **Pages**, select the branch you want to publish and the repository root (`/`) as the source, then save. GitHub Pages will serve `index.html` as the site homepage. Tool links are relative, so they work both on a GitHub Pages project site and when the pages are opened locally.
