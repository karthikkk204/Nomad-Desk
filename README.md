# NomadDesk — React + JavaScript + Tailwind CSS

A responsive coworking-space discovery website recreated from the supplied NomadDesk project, using React, JavaScript (JSX), Vite, Tailwind CSS v4, and Lucide icons.

## Run locally

1. Install Node.js 20.19+ or 22.12+.
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL Vite prints.

## Functional features

- Responsive navigation and section links
- Explore cities; choosing a city filters the workspace list
- Search workspaces by name, city, neighbourhood, and description
- Filter by city, minimum Wi-Fi speed, maximum day-pass price, and amenities
- Sort by rating, price, or Wi-Fi speed
- Save/unsave workspaces; saved selections persist in localStorage
- Dedicated workspace detail URLs at `/space/:id`, including amenities, reviews, and a demo booking form
- Compare up to three spaces side by side
- Browser back/forward support for workspace detail pages
- Responsive mobile navigation

## Notes

This is a front-end demo. Booking submissions show a local confirmation only; no real reservation is made and no email is sent. Listings and reviews are sample data. There is no backend or authentication system connected.
