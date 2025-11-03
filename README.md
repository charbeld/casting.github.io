# Spotlight Casting Agency

A polished, responsive landing page for Spotlight Casting Agency that highlights the brand, showcases talent, and collects new registrations via a no-backend form workflow.

## Features
- Modern hero with art-directed photography and proof points
- Responsive layout with mobile navigation, hamburger menu, and sticky header
- Dark/light theme toggle with system preference detection and local storage
- Talent showcase and client strip for credibility
- Registration form wired to an n8n webhook so it works on static hosting (e.g., GitHub Pages)
- Accessible focus states, semantic markup, and progressive enhancement

## Tech Stack
- HTML5
- CSS3 (custom properties, grid, flexbox, clamp)
- Vanilla JavaScript for interactivity and theme persistence

## Local Development
1. Clone or download the repository.
2. Open `index.html` in your browser (double-click or serve with any static server).
3. Edit `index.html` and `styles.css` as needed; the site is framework-free.
4. Update the `N8N_WEBHOOK_URL` in `index.html` if you need to point to a different form endpoint.

## Customization Tips
- Swap Unsplash image URLs in the hero and talent sections for your own assets.
- Adjust accent colors by editing the CSS variables in `styles.css`.
- Add or remove form fields by modifying the form markup and ensuring your webhook expects the same names.

## Deployment
- Push the project to any static host (GitHub Pages, Netlify, Vercel, etc.).
- Ensure the webhook endpoint is accessible over HTTPS; otherwise, the form submission will fail.

## License
Feel free to adapt this landing page for your own casting or agency projects.




