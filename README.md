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

### 10. Footer

The footer includes:

- TaxPal logo
- Navigation links
- Copyright text

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

## Customisation

You can customise the website by editing the HTML file.

### Change Brand Colours

The custom theme colours are defined in the `<style>` block:

```css
@theme {
  --color-brand-by-abhishek: #4f46e5;
  --color-brand-by-abishek: #0a0f1e;
}
```

Main colours used across the page include:

- Dark navy: `#0a0f1e`
- Indigo: `#4f46e5`
- Pink: `#f472b6`
- Slate text colours from Tailwind CSS

### Change Pricing

Pricing cards are located in the **Pricing** section. Update the plan names, prices, and feature lists directly in the HTML.

### Change Testimonials

Testimonials are located in the **Testimonials** section. You can update:

- Quote text
- Customer name
- Job title
- Avatar image URL

### Change Navigation Links

The navigation links currently point to internal sections and example paths. For smoother single-page navigation, update links like this:

```html
<a href="#features">Features</a>
<a href="#testimonials">Testimonials</a>
<a href="#pricing">Pricing</a>
```

## Recommended Improvements

The current page is fully usable as a static landing page, but these improvements can make it more polished:

- Move inline styles into a separate CSS file.
- Fix spelling mistakes such as `Bussiness` to `Business`.
- Remove spaces from file paths such as `index .html`.
- Replace placeholder or joke text with real product copy.
- Add a mobile menu for smaller screens.
- Add form functionality for sign-in or get-started buttons.
- Optimise external images for faster loading.
- Add accessibility labels where needed.
- Add SEO meta tags such as description, keywords, and Open Graph tags.

## Browser Support

This page should work in modern browsers such as:

- Google Chrome
- Microsoft Edge
- Firefox
- Safari

Because Tailwind is loaded from a CDN, an internet connection is required for the styling to load correctly.

## License

This project is for learning and portfolio purposes. You can modify and use it for practice, assignments, or personal projects.

## Author

Created as a TaxPal landing page project.
