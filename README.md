# Right-Hardware
# Right Hardware

Right Hardware is a static storefront and service website for a local hardware business. The project presents product categories, service offerings, and company information for customers browsing on desktop or mobile.

## Project overview

This website includes:
- A home page with hero content and featured highlights
- Product listings and category navigation
- Service information for repair and project support
- An About Us page describing the business values
- A responsive layout with shared styling and JavaScript behavior

## Project structure

```text
.
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── pages/
│   ├── about-us.html
│   ├── home.html
│   ├── products.html
│   └── services.html
├── index.html
├── README.md
└── .gitignore
```

## Run locally

Because this is a static website, you can view it by opening `index.html` directly in a browser, or serve it locally:

```bash
cd "D:\My Projects\RIGHT HARDWARE"
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Notes

- The site uses plain HTML, CSS, and JavaScript.
- No package installation or build step is required.
- Styling and scripts are located in the `assets/` directory and reused across pages.
