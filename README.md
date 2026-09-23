# PRJKU Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Static Site](https://img.shields.io/badge/Type-Static%20Website-00C853?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Design-Responsive-FF6F61?style=for-the-badge)

A static web portal developed for RISDA (Rubber Industry Smallholders Development Authority) to promote entrepreneurship and agromakanan programmes, provide business information, and share success stories with the public.

## What this project does

This website acts as a central information hub for:

- entrepreneur and agromakanan assistance programmes
- product and service categories for local entrepreneurs
- success stories and inspiring business journeys
- public information about RISDA offices and station details
- frequently asked questions (FAQ)
- documents and useful forms
- awards and achievements
- contact information and public links to official resources

The site is designed to be simple, responsive, and easy to navigate for visitors looking for information related to local entrepreneurship development and agro-based business support.

## Tech Stack

- HTML5 for page structure
- CSS3 for styling and layout
- Bootstrap 5 for responsive UI and components
- JavaScript for interactivity and Bootstrap-based behavior
- External image assets and icons for branding and content

## Project structure

```text
.
├── index.html
├── css/
│   ├── card.css
│   ├── nav.css
│   ├── program-list.css
│   └── style.css
├── document/
├── image/
├── views/
│   ├── anugerah.html
│   ├── dokumen.html
│   ├── prjku.html
│   ├── programagromakanan.html
│   ├── soalan-lazim.html
│   ├── stesen-list.html
│   ├── kisahkejayaan/
│   ├── produksusahawan/
│   └── programusahawan/
└── README.md
```

## Features

- landing page with promotional banner carousel
- navigation bar with quick links to key sections
- information cards for programmes and services
- dedicated pages for entrepreneurship products and stories
- FAQ, document, award, and contact sections
- mobile-friendly layout using Bootstrap
- static hosting-friendly structure, no backend required

## How to run locally

Because this is a static website, you can run it by opening the project in a browser:

1. Clone or download the project.
2. Open the root folder.
3. Launch `index.html` directly in your browser, or serve it with a simple local web server if preferred.

Example using Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

This project is suitable for static hosting platforms such as:

- GitHub Pages
- Netlify
- Vercel
- any basic static web hosting service

## Notes

This website is primarily a public-facing informational portal rather than a transactional application. It is focused on content delivery, awareness, and accessibility for entrepreneurship and agromakanan support programmes.

## License

This project is intended for internal/public use for the associated organisation and may be updated or adapted as needed.
