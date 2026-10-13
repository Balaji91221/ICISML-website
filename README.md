# ICISML 2024 · Conference Website

**Conference information in a lightweight, static website.**

HTML · CSS · JavaScript

## About

This repository contains a website for the **4th International Conference on Intelligent Systems and Machine Learning (ICISML 2024)**. It organizes information for prospective authors and attendees, including research tracks, paper submission, committee information, keynotes, important dates, registration, and contact details.

The content refers to the 2024 event and should be treated as an archived conference website.

## Browse the project

- [`index.html`](index.html): main conference page and navigation.
- [`keynote.html`](keynote.html): keynote information.
- [`icisml.pdf`](icisml.pdf): program resource linked by the site.
- [`poster.jpg`](poster.jpg): conference poster.
- [`style-guide.md`](style-guide.md): design reference.

## Preview locally

No package installation or build step is required. Download the repository files and serve the root directory with a static server. For example, with Python 3:

```bash
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000).

## How it is organized

```text
Browser
  ├── index.html / keynote.html
  ├── assets/css/style.css
  ├── assets/js/script.js
  └── images, poster, PDF, and video assets
```

The HTML contains the event content, CSS controls presentation, and JavaScript handles interactive page behavior. There is no application server, database, or submission-processing backend in the repository.

## Maintaining the site

Update event copy and links in the HTML, visual rules in [`assets/css/style.css`](assets/css/style.css), and interactions in [`assets/js/script.js`](assets/js/script.js). Keep relative asset paths consistent when moving files.

The navigation currently refers to `gallery.html`, which is absent from this repository. External conference links and historical dates also require review before adapting the site for a new event.
