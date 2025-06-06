SwiftThion Express Website
This repository contains the front-end code for the SwiftThion Express company website, a modern, responsive, and user-friendly platform designed to showcase logistics and shipping services.

Table of Contents
Project Overview

Features

Color System

Setup and Installation

Usage

File Structure

Dependencies

Responsive Design

Contributing

License

Contact

Project Overview
SwiftThion Express is a logistics and shipping company dedicated to providing smarter and faster delivery solutions. This website serves as the primary online presence, allowing users to explore services, track shipments, get quotes, and contact the company. The design emphasizes a professional and trustworthy brand image, utilizing a carefully selected color palette and a clean layout.

Features
Responsive Navigation Bar: A sticky navigation bar that adapts to different screen sizes, including a dynamic logo (text-based) and links for easy access to various sections.

Hero Section: A prominent hero area with a compelling image and overlay text, designed to immediately convey the company's value proposition.

How It Works Section: Explains the streamlined logistics process in simple steps, accompanied by an illustrative image.

Cargo Shipping Services: Details various freight options (Air, Road, Ocean, Rail) with clear service items and call-to-action.

Enterprise Logistics Services: Showcases advanced logistics solutions like warehousing, transport, and packaging for business clients.

Client Testimonials: A horizontal carousel section featuring positive feedback from clients, providing social proof and building trust. Includes navigation arrows for scrolling.

Partners Section: Highlights key partners, reinforcing credibility and showcasing collaborations.

FAQ Section: An interactive accordion-style section for frequently asked questions, improving user self-service.

Track Shipment Feature: A dedicated input field for users to track their packages in real-time.

Why Choose Us: Outlines the company's unique selling points and benefits for customers.

Call to Action (CTA) Sections: Strategically placed buttons to encourage user engagement (e.g., "Request a Quote", "Get Started").

Contact Us Section: Provides contact information and a functional message form for inquiries.

Footer: Contains copyright information and quick links to privacy policy, terms of service, and support.

Smooth Scrolling: Implemented for a seamless user experience when navigating between sections via the navbar.

Color System
The website utilizes a distinct color system designed for professionalism, trust, and clarity, adhering to WCAG AA contrast standards.

Primary Color: #ff6600 (SwiftThion Orange)

Reasoning: Chosen for its vibrancy and energy, ideal for calls-to-action and highlighting key elements, evoking warmth and innovation.

Primary Hover Color: #e65500 (Darker primary color for hover)

Secondary Color: #004080 (Deep Ocean Blue)

Reasoning: Represents trust, stability, and professionalism, forming the core brand identity.

Accent Color: #0066cc (Sky Blue)

Reasoning: A lighter, more dynamic blue, used for interactive elements, links, and secondary highlights to provide visual interest and contrast with the primary blue.

Light Background: #f9f9f9 (Soft Off-White)

Reasoning: Provides a clean, spacious backdrop, minimizing eye strain.

Dark Background: #e6e6e6 (Subtle Grey Background)

Reasoning: A slightly darker light background for alternating sections, adding visual separation.

White Color: #fff (Pure White)

Reasoning: For text on dark backgrounds and card elements, ensuring high readability.

Text Color: #333 (Charcoal Grey)

Reasoning: A soft, readable black for primary text, offering good contrast without being harsh.

Light Text Color: #666 (Medium Grey)

Reasoning: For section descriptions and less emphasized text, providing softer contrast.

Border Color: #ccc (Light Grey Border)

Testimonial Background Light: #ffe6d9 (Soft Peach)

Reasoning: A warm, inviting background for alternating testimonial cards, complementary to the orange.

Testimonial Background Dark: #0066cc (Reinforcing Sky Blue)

Reasoning: Used for alternating testimonial cards, providing a strong contrast and echoing the accent color.

Testimonial Text Dark: #004080 (Deep Ocean Blue for text on light testimonial backgrounds)

Setup and Installation
To set up this project locally for development or preview:

Clone the repository:

git clone [repository-url]
cd swiftthion-express-website

(Replace [repository-url] with the actual URL if this were a GitHub repo).

Ensure image assets are present:
The website relies on images located in an images/ directory relative to index.html. Make sure the following files are in your images/ folder:

logo.png (Your company logo)

card.png (Hero section background image)

truck2.jpg (How It Works section image)

ship.png (Cargo Shipping section image)

iyflogo.jpeg (Partner logo)

goodnewsmission.jpg (Partner logo)

gbstv.png (Partner logo)

Open index.html:
Simply open the index.html file in your preferred web browser.

Usage
Navigate through the website using the top navigation bar. Click on "Home", "Shipping", "Track", "Pricing", "Support", and "Contact" to smoothly scroll to the respective sections. The FAQ section allows expanding/collapsing answers, and the testimonials section can be scrolled using the left and right arrow buttons.

File Structure
.
├── index.html          # Main HTML structure of the website
├── styles.css          # All custom CSS styling
├── images/             # Directory for all image assets
│   ├── logo.png
│   ├── card.png
│   ├── truck2.jpg
│   ├── ship.png
│   ├── iyflogo.jpeg
│   ├── goodnewsmission.jpg
│   └── gbstv.png
└── README.md           # This file

Dependencies
This project uses:

Font Awesome 6 (Free): For various icons (fa-plane, fa-road, fa-ship, fa-train, fa-bars, fa-check-circle, fa-headset, fa-map-marked-alt, fa-leaf, fab fa-facebook, fab fa-twitter, fab fa-instagram). Loaded via CDN.

No other external JavaScript libraries or frameworks are used, keeping the project lightweight.

Responsive Design
The website is fully responsive, designed to provide an optimal viewing experience across a wide range of devices (desktops, tablets, and mobile phones). Media queries are extensively used in styles.css to adjust layouts, typography, and element visibility based on screen size:

Large (LG) Breakpoint: Base styles (993px and up).

Medium (MD) Breakpoint: Tablets (601px to 992px).

Small (SM) Breakpoint: Mobile devices (max-width: 600px).

Contributing
Contributions are welcome! If you have suggestions for improvements, feature requests, or bug fixes, please open an issue or submit a pull request.

License
(You can specify your chosen license here, e.g., MIT, Apache 2.0, etc.)

Contact
For any inquiries, please reach out to:
Kevin Mwangi
Email: sir.kevin.mwangi@gmail.com
Phone: 0710186408
Address: P.O BOX 39299-00623, Nairobi