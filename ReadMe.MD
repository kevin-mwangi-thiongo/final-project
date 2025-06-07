SwiftThion Express Website
This repository contains the front-end code for the SwiftThion Express company website, a modern, responsive, and user-friendly platform designed to showcase logistics and shipping services.

Table of Contents
Project Overview
Features
Color System
Creative Divergence from Mockup
Setup and Installation
Usage
File Structure
Dependencies
Responsive Design & Breakpoint Logic
Contributing
License
Contact
Project Overview
SwiftThion Express is a logistics and shipping company dedicated to providing smarter and faster delivery solutions. This website serves as the primary online presence, allowing users to explore services, track shipments, get quotes, and contact the company. The design emphasizes a professional and trustworthy brand image, utilizing a carefully selected color palette and a clean, accessible layout.

Features
Responsive Navigation Bar: A sticky navigation bar that adapts to different screen sizes, including a dynamic logo (text-based) and links for easy access to various sections. Features a hamburger menu toggle for smaller screens.
Hero Section: A prominent hero area with a compelling background image and overlay text, designed to immediately convey the company's value proposition.
How It Works Section: Explains the streamlined logistics process in simple steps, accompanied by an illustrative image.
Cargo Shipping Services: Details various freight options (Air, Road, Ocean, Rail) with clear service items and a call-to-action button.
Enterprise Logistics Services: Showcases advanced logistics solutions like warehousing, transport, and packaging for business clients, presented in a clear grid format.
Client Testimonials: A horizontally scrollable section featuring positive feedback from clients, providing social proof and building trust. Includes intuitive navigation arrows for scrolling.
Partners Section: Highlights key partners with their logos and names, reinforcing credibility and showcasing collaborations.
FAQ Section: An interactive accordion-style section for frequently asked questions, improving user self-service.
Track Shipment Feature: A dedicated input field for users to track their packages in real-time.
Why Choose Us: Outlines the company's unique selling points and benefits for customers using a list with icons.
Call to Action (CTA) Sections: Strategically placed buttons to encourage user engagement (e.g., "Request a Quote", "Get Started").
Contact Us Section: Provides comprehensive contact information (email, phone, address) and a functional message form for inquiries. Includes social media links.
Footer: Contains copyright information and quick links to privacy policy, terms of service, and support.
Smooth Scrolling: Implemented for a seamless user experience when navigating between sections via the navbar.
Color System
The website utilizes a distinct color system designed for professionalism, trust, and clarity, adhering to WCAG AA contrast standards.

Primary Color: --primary-color: #ff6600; (SwiftThion Orange)
Reasoning: Chosen for its vibrancy and energy, ideal for calls-to-action and highlighting key interactive elements, evoking warmth, innovation, and urgency.
Primary Hover Color: --primary-hover-color: #e65500; (Darker primary color for hover states)
Secondary Color: --secondary-color: #004080; (Deep Ocean Blue)
Reasoning: Represents trust, stability, and professionalism, forming the core brand identity and providing a strong, reliable base.
Accent Color: --accent-color: #0066cc; (Sky Blue)
Reasoning: A lighter, more dynamic blue, used for interactive elements, links, and secondary highlights to provide visual interest and a sense of openness, complementing the primary blue.
Light Background: --bg-light: #f9f9f9; (Soft Off-White)
Reasoning: Provides a clean, spacious backdrop for main content sections, minimizing eye strain and enhancing readability.
Dark Background: --bg-dark: #e6e6e6; (Subtle Grey Background)
Reasoning: A slightly darker light background for alternating sections (e.g., cargo-shipping, services, partners, track-shipment), adding visual separation and design rhythm.
White Color: --white-color: #fff; (Pure White)
Reasoning: Used for text on dark backgrounds and bright card elements, ensuring high readability and a crisp appearance.
Text Color: --text-color: #333; (Charcoal Grey)
Reasoning: A soft, readable black for primary text, offering excellent contrast on light backgrounds without being overly harsh.
Light Text Color: --light-text-color: #666; (Medium Grey)
Reasoning: For section descriptions and less emphasized text, providing softer contrast and visual hierarchy.
Border Color: --border-color: #ccc; (Light Grey Border)
Testimonial Background Light: --testimonial-bg-light: #ffe6d9; (Soft Peach)
Reasoning: A warm, inviting background for alternating testimonial cards, chosen to be complementary to the primary orange, adding a friendly touch.
Testimonial Background Dark: --testimonial-bg-dark: #0066cc; (Reinforcing Sky Blue)
Reasoning: Used for alternating testimonial cards, providing a strong contrast and echoing the accent color, creating visual variety within the testimonials section.
Creative Divergence from Mockup
Beyond the custom color scheme detailed above, this project diverges creatively from a hypothetical generic mockup in several key areas:

Distinct Typography Choices: While using standard sans-serif fonts (Arial, Helvetica), deliberate choices were made in font-size (clamp function for fluid scaling), line-height, and letter-spacing to ensure optimal readability and a modern, professional aesthetic across all devices.
Enhanced Interactivity: The FAQ section is implemented as an interactive accordion, providing a cleaner initial view and allowing users to expand answers as needed. The Client Testimonials feature a custom horizontal scroll with clear navigation arrows, offering a more engaging way to browse feedback than a static grid.
Unique Button Styling: Buttons (primary-button, secondary-button) feature custom border-radius, padding, box-shadow, and hover effects, giving them a distinct brand feel that goes beyond typical default button styles.
Structured Section Layouts: The arrangement of content within sections like "How It Works" and "Cargo Shipping" (e.g., image alongside text block, services grid within content wrapper) prioritizes clear visual hierarchy and readability, optimized for content absorption.
Semantic HTML and Accessibility Focus: A strong emphasis was placed on semantic HTML5 elements and aria-label attributes for improved accessibility, ensuring the site is usable and navigable for a wider audience, including those using assistive technologies.
Setup and Installation
To set up this project locally for development or preview:

Clone the repository:
Bash

git clone [repository-url]
cd swiftthion-express-website
(Replace [repository-url] with the actual URL once the GitHub repo is created and public).
Ensure image assets are present: The website relies on images located in an images/ directory relative to index.html. Make sure the following files are in your images/ folder:
truck2.jpg (How It Works section image)
ship.png (Cargo Shipping section image)
kenyagov.jpg (Partner logo)
kenyaports.jpg (Partner logo)
iyflogo.jpeg (Partner logo)
gbstv.jpg (Partner logo)
Open index.html: Simply open the index.html file in your preferred web browser.
Usage
Navigate through the website using the top navigation bar. Click on "Home", "Shipping", "Track", "Pricing", "Support", and "Contact" to smoothly scroll to the respective sections. The FAQ section allows expanding/collapsing answers, and the testimonials section can be scrolled using the left and right arrow buttons.

File Structure
.
├── index.html          # Main HTML structure of the website
├── styles.css          # All custom CSS styling
├── images/             # Directory for all image assets
│   ├── truck2.jpg
│   ├── ship.png
│   ├── kenyagov.jpg
│   ├── kenyaports.jpg
│   ├── iyflogo.jpeg
│   └── gbstv.jpg
└── README.md           # This file
Dependencies
This project uses:

Font Awesome 6 (Free): For various icons (fa-plane, fa-road, fa-ship, fa-train, fa-bars, fa-check-circle, fa-headset, fa-map-marked-alt, fa-leaf, fab fa-facebook, fab fa-twitter, fab fa-instagram). Loaded via CDN.
No other external JavaScript libraries or frameworks are used, keeping the project lightweight.

Responsive Design & Breakpoint Logic
The website is fully responsive, designed to provide an optimal viewing experience across a wide range of devices (desktops, tablets, and mobile phones). Media queries are extensively used in styles.css to adjust layouts, typography, and element visibility based on screen size:

Large (LG) Breakpoint (@media (min-width: 1024px)): This is the primary desktop layout, utilizing multi-column flexbox and grid layouts for sections like how-it-works-container, cargo-container, services-grid-box, testimonials-grid, partners-grid, and contact-content. The navigation bar displays all links.
Medium (MD) Breakpoint (@media (max-width: 1023px) and (min-width: 768px)):
The navbar elements (nav-left, nav-right) might begin to stack or adjust, and the logo might be re-centered or resized.
Sections like how-it-works-container and cargo-container might transition to a more vertical flex-direction: column layout to optimize space.
Grids (e.g., shipping-services-grid, services-grid-box, partners-grid) will likely adjust their grid-template-columns to show fewer columns or adapt to minmax definitions, ensuring items don't become too small.
Font sizes (clamp functions) and padding/margins are adjusted for tablet readability.
Small (SM) Breakpoint (@media (max-width: 767px)):
The primary navbar will collapse, and the menu-toggle (hamburger icon) will become visible, allowing users to open/close the navigation.
All multi-column layouts will typically collapse into single-column (flex-direction: column or grid-template-columns: 1fr).
Images may be optimized for smaller screens, and font-size will be further scaled down for mobile readability.
Padding and margins are significantly reduced to maximize content area on very small screens.
Contributing
Contributions are welcome! If you have suggestions for improvements, feature requests, or bug fixes, please open an issue or submit a pull request.


Contact
For any inquiries, please reach out to:
Kevin Mwangi
Email: sir.kevin.mwangi@gmail.com
Phone: 0710186408
Address: P.O BOX 39299-00623, Nairobi