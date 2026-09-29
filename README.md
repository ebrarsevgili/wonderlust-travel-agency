# Wonderlust Travel Agency

Wonderlust is a **multi-page static website** built for a travel agency. It serves as a showcase site presenting tours, hotels, campaigns, and contact information.

> ⚠️ **Project status: Work in Progress**
> This is a frontend showcase project; it is not yet connected to a backend. Booking, purchasing, and form submission do **not** perform any real action. See the [Known Limitations](#known-limitations) section below for details.

---

## Table of Contents

- [Features](#features)
- [Known Limitations](#known-limitations)
- [Tech Stack](#tech-stack)
- [Quick Start](#quick-start)
- [Repository Structure](#repository-structure)
- [Pages](#pages)
- [Roadmap](#roadmap)
- [License](#license)

---

## Features

- Multi-page static site architecture (each page has its own `.html` + `.css` file)
- Responsive mobile menu
- Tour categories: Domestic, International, and Themed Tours
- A dedicated tour detail page (East Express to Kars Tour) with tabbed content and an expandable day-by-day itinerary
- Hotel listing page
- Campaigns page
- About and Contact pages
- Embedded Google Maps location on the Contact page
- Written entirely in vanilla HTML/CSS/JS — no framework or build tool required

## Known Limitations

This project is currently **frontend/static only**. The following points are not yet functional and are intentionally documented here:

| Area | Status |
|---|---|
| Contact form (`Iletisim.html`) | The form UI exists, but no `action` is defined — submitting it sends data nowhere |
| Hotel "VIEW HOTEL" button | `href="#"` — clickable but doesn't link anywhere |
| East Express "Select Tour" button | Visually present, but not connected to any booking/purchase logic |
| Booking / purchase flow | None — this is a showcase site, no real booking or payment system exists |
| Backend / database | None — all content is hardcoded into static HTML |
| Form validation | None |

These limitations are listed here intentionally, for transparency, since this project is shared as a CV/portfolio piece.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (used only on the tour detail page: tab switching, expandable day itinerary, mobile menu)
- Google Fonts (Poppins)
- Google Maps embed (Contact page)

## Quick Start

No installation or dependencies required. Clone the repo and open it directly in a browser:

```bash
git clone https://github.com/ebrarsevgili/wonderlust-travel-agency.git
cd wonderlust-travel-agency
```

Then open `index.html` in your browser, or if you're using VS Code, run it with the **Live Server** extension:

```bash
# Using VS Code's Live Server extension
# Right-click index.html > "Open with Live Server"
```

## Repository Structure

```text
wonderlust-travel-agency/
├── index.html                    # Home page
├── index.css
├── Turlar.html                   # Tour categories page
├── Turlar.css
├── Yurt-Ici-Turlar.html          # Domestic tours
├── Yurt-Ici-Turlar.css
├── Yurt-Disi-Turlar.html         # International tours
├── Yurt-Disi-Turlar.css
├── Temalara-Gore-Turlar.html     # Themed tours
├── Temalara-Gore-Turlar.css
├── Dogu_Ekspresi_Kars.html       # East Express / Kars tour detail page
├── Dogu_Ekspresi_Kars.css
├── Otel.html                     # Hotel listing
├── Otel.css
├── Kampanyalar.html              # Campaigns
├── Kampanyalar.css
├── Hakkimizda.html               # About Us
├── Hakkimizda.css
├── Iletisim.html                 # Contact (form + Google Maps)
├── Iletisim.css
├── images/                       # Site images
└── README.md
```

## Pages

| Page | Description |
|---|---|
| Home | Landing page, featured content |
| Tours | Overview of all tour categories |
| Domestic Tours | Tour options within Turkey |
| International Tours | Tour options abroad |
| Themed Tours | Tours filtered by theme (culture, nature, etc.) |
| East Express to Kars Tour | Detailed tour program, tabbed content, day-by-day itinerary |
| Hotels | Hotel list |
| Campaigns | Current campaign announcements |
| About Us | Company information |
| Contact | Contact form + map |

## Roadmap

- Connect the contact form to a real backend/email service
- Add a real booking flow to the hotel and tour pages
- Add dynamic pricing based on date selection
- Add tour search and filtering
- Improve responsive behavior across all pages
- Optimize images for performance
- Publish a live demo via GitHub Pages

## License

This project was built for educational and portfolio purposes.
