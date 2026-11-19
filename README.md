# Maison Soleil — Hotel Booking Confirmation Page

This project is an implementation of the **Hotel booking confirmation page** challenge from [Frontend Mentor Challenges](https://www.frontendmentor.io/challenges)

## Overview

The page presents a booking confirmation view for a stay at Maison Soleil in Cassis, featuring a sidebar with navigation items, a daily weather summary, and hotel details alongside a main content area with a booking receipt, a host welcome card from Margaux, and arrival, Wi-Fi, and breakfast cards.

## Approach & Customizations

- **HTML5 & Bootstrap 5:** Structured the page with semantic elements (`aside`, `main`, `nav`, `footer`) and used Bootstrap grid classes (`row`, `g-4`, `col-lg-6`, `col-lg-4`, `col-6`), components (`card`, `btn`, `badge`), and utilities (`d-flex`, `flex-column`, `flex-lg-row`, `justify-content-between`, `align-items-center`, `mt-auto`, `text-nowrap`, and spacing classes) for responsive layout behavior.
- **Typography & Color Palette:** Loaded `Fraunces`, `DM Sans`, and `DM Mono` from Google Fonts and paired them with custom CSS for warm cream backgrounds, a terracotta welcome card, a sunny Cassis weather card, and colored icon badges (`Arrival`, `Wifi`, and `Breakfast`).
- **Assets & Icons:** Linked SVG icons and artwork from `./assets/images/` for the brand emblem, navigation links, barcode, welcome card sun, weather indicator, and info card badges.


## Reflection 

Creating the hotel reservation confirmation page taught me how to transform a visual design into a responsive web page by combining Bootstrap layout tools with custom CSS. One of the biggest challenges I encountered was the accidental premature closing of `div` tags, which disrupted the nesting of cards and caused elements to shift out of their grid columns. Additionally, ensuring that light-colored SVG icons remained clearly visible, while also correctly positioning the weather widget in the sidebar and the footer, proved difficult. I resolved these issues by carefully verifying the boundaries of my HTML containers, grouping icons and text within flexible containers, and refining the CSS spacing and flex alignment. Furthermore, I tested the layout across both desktop and mobile screen sizes using browser Developer Tools to ensure the spacing and stacking behavior were correct. It felt a bit like assembling a custom-built computer, but it was incredibly rewarding to see the project take shape as I worked on it. If I had more time, I would have refined the side menu to make it interactive, added functional features such as a copy Wi-Fi password option and further improved the mobile spacing and overall accessibility.

## Links

- Frontend Mentor Challenge: [https://www.frontendmentor.io/challenges/hotel-booking-confirmation-page]
