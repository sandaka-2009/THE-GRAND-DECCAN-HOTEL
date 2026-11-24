# THE-GRAND-DECCAN-HOTEL
# The Grand Deccan Residency — Hotel Booking Website

A responsive, single-page hotel booking web application built for a college web development project. It features interactive room category filtering, dynamic GST-inclusive fare calculation, live customer review submission, and an instant printable booking receipt modal.

---

## Key Features

- **Hero & Quick Availability Bar:** Syncs check-in, check-out, and guest count selections directly with the main reservation section.
- **Filterable Room Categories (₹ INR):** Filter rooms by category (*All*, *Deluxe & Executive*, *Family Garden*, *Royal Heritage Villa*) with one-click **Book This Room** auto-selection.
- **Hotel Facilities Showcase:** Clean grid highlighting Wi-Fi, Rooftop Infinity Pool, Multi-Cuisine Dining, Ayurvedic Spa, Airport Shuttle, and 24/7 Concierge.
- **Interactive Guest Reviews:** Star-rating filter and a working **Write a Review** form that updates the average rating and adds new reviews to the page in real time.
- **Live Fare Calculator & Booking Receipt:** Automatically computes `Nights × Room Rate + 12% GST`, validates dates, and generates a reservation confirmation modal with a unique Booking ID (`GDR-XXXXXX`).

---

## Tech Stack

- **HTML5:** Semantic structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- **CSS3 / Tailwind CSS:** Responsive grid/flexbox layouts, custom styling, and mobile-first design
- **Vanilla JavaScript (ES6+):** DOM manipulation, dynamic pricing logic, form validation, review state updates, and modal controls

---

## Project Structure

```text
hotel-booking-website/
├── index.html      # Complete application (HTML structure, styles, and JavaScript logic)
└── README.md       # Project documentation
