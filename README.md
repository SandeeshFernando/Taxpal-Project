# TaxPal Landing Page

TaxPal is a responsive landing page for an accounting software product. The page is built with HTML and Tailwind CSS using a dark navy, indigo, and pink visual theme.

This project includes a complete single-page website with a navigation bar, hero section, company logos, features, task highlights, call-to-action section, testimonials, pricing cards, FAQ section, and footer.

## Project Overview

The website is designed for a fictional accounting platform called **TaxPal**. Its main message is:

> Accounting made for small businesses and for everyone.

The page uses a modern SaaS-style layout with strong typography, rounded cards, gradients, hover effects, and responsive sections.

## Technologies Used

- HTML5
- Tailwind CSS
- Inline custom Tailwind theme variables
- External images and SVG assets
- Responsive layout utilities

Tailwind CSS is loaded through the CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

## Main Sections

### 1. Navigation Bar

The navigation bar includes:

- TaxPal logo
- Feature, testimonial, and pricing links
- Sign-in link
- Get started button

The header is sticky, so it remains visible at the top of the page while scrolling.

### 2. Hero Section

The hero section contains:

- Main headline
- Highlighted text with SVG underline effects
- Short product description
- Primary call-to-action button
- Watch video button

### 3. Trusted Companies Section

This section displays six company logos to create brand trust and credibility.

### 4. Features Section

The features section introduces the main product features:

- Payroll
- Claim expenses
- VAT handling
- Reporting

It also includes a large product screenshot.

### 5. Business Tasks Section

This section highlights simplified business tasks such as:

- Reporting
- Inventory
- Contacts

Each feature card includes an icon, title, and short description.

### 6. Call-to-Action Section

A gradient CTA section encourages users to get the business package and try the product.

### 7. Testimonials Section

This section displays customer testimonials in card format with user avatars and job titles.

### 8. Pricing Section

The pricing section includes three plans:

| Plan | Price | Description |
|---|---:|---|
| Starter | $9/month | For self-employed users getting started |
| Small Business | $15/month | For small and medium-sized businesses |
| Enterprise | $39/month | For larger companies |

The Small Business plan is visually highlighted.

### 9. FAQ Section

The FAQ section contains common questions and answers about TaxPal.

## File Structure

A simple project structure could look like this:

```text
taxpal-landing-page/
├── index.html
└── README.md
```

If you add local images, CSS, or JavaScript later, you can expand it like this:

```text
taxpal-landing-page/
├── index.html
├── README.md
├── assets/
│   └── images/
├── css/
│   └── style.css
└── js/
    └── script.js
```

## How to Run the Project

### Option 1: Open Directly in a Browser

1. Download or clone the project.
2. Open `index.html` in your browser.

### Option 2: Use VS Code Live Server

1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

### 10. Footer

The footer includes:

- TaxPal logo
- Navigation links
- Copyright text
