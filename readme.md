# Kobe's Kitchen — Official Web Application Documentation

Welcome to the comprehensive repository for **Kobe's Kitchen**, a vibrant, community-oriented food business specializing in fresh, high-quality, Kasi-style meals. This documentation serves as a complete technical guide, architectural outline, and maintenance manual for the five-page static web application.

---

## 📌 Executive Summary & Brand Identity

Kobe's Kitchen was founded on a simple yet ambitious premise: to craft delicious, generous, and affordable Kasi-inspired meals using fresh ingredients while treating every guest with pride and respect. 

The primary goal of this web application is to translate that physical storefront hospitality into an accessible, fast, and structured online experience. Through this application, customers can interact with the brand, explore menu items and prices, read the brand story, submit digital enquiry forms, and find physical directions to the establishment.

### Core Value Propositions
* **Generous Portions:** Satisfying meals made for people who appreciate great taste and value.
* **Fresh Ingredients:** Daily sourced ingredients prepared without shortcuts.
* **Community First:** A proudly local business built around serving families, friends, and workers.
* **Accessible Communication:** Direct connectivity via phone, WhatsApp, embedded Google Forms, and Google Maps.

---

## 📁 Complete Repository File Structure

Below is the directory map representing the project root and all linked assets referenced across the five HTML files:

```text
kobes-kitchen/
│
├── index.html                  # Landing page featuring hero banner & core product highlights
├── about.html                  # Brand narrative, core mission, values, & community impact
├── services.html               # Full menu, item descriptions, & pricing structure
├── enquiries.html              # Interactive online contact & customer enquiry form
├── contact.html                # Contact numbers, WhatsApp links, & Google Maps location
│
├── css_assets/
│   └── style.css               # Central stylesheet driving global layout, responsiveness, & typography
│
└── _images/                    # High-resolution media assets folder
    ├── Logo.jpeg               # Main Kobe's Kitchen official brand logo
    ├── burger (2).jpg          # Hero burger image & Regular Burger item photo
    ├── Burger 3.jpg            # Smash Burger item display photo
    ├── Burger 4.jpg            # Monster Burger item display photo
    ├── wings (1).jpg           # Sticky / Non-Sticky Wings item photo
    ├── wings and fries (1).jpg # Fire Burger & combo item photo
    ├── Fries 1.jpg             # Regular Crispy Fries photo
    ├── Fries 2.jpg             # Loaded Fries photo
    ├── drinks.jpg              # Cold Fanta drinks range photo
    ├── cheff.jpg               # Chef at work ("Our Story" section)
    ├── community.jpg           # Local community photo ("Our Mission" section)
    ├── staff.jpg               # Kitchen & service team photo ("Why Choose Us" section)
    └── happy_customer.jpg      # Satisfied diner photo ("Our Community" section)
    # Kobe's Kitchen — Complete Version History & Changelog

This document provides a detailed itemized breakdown of all features, structural markup additions, visual media integrations, content implementations, and layout improvements applied across the five primary HTML pages of the Kobe's Kitchen web application.

---

## 📌 Global Project Specifications & Updates

Across all five HTML documents, the following standardized architecture was established:

* **Document Structure & Standard:** Full HTML5 compliance featuring `<!DOCTYPE html>` declarations, standard `<head>` meta configurations, UTF-8 charset encoding, and mobile viewport optimization (`width=device-width, initial-scale=1.0`).
* **Unified Design Language:** Linked all pages to a central external stylesheet (`css_assets/style.css`).
* **Global Header Architecture:** Implemented a uniform header containing the brand logo (`_images/Logo.jpeg`), page title (`<h1>`), and introductory taglines.
* **Universal Navigation Bar:** Integrated an unordered list (`<ul>`) navigation block linking `index.html`, `about.html`, `services.html`, `enquiries.html`, and `contact.html` to guarantee consistent site-wide user traversal.
* **Standardized Footer:** Implemented a sticky-bottom footer across all documents displaying the copyright notice (`&copy; 2026 Kobe's Kitchen. All rights reserved.`).

---

# 📄 Page-by-Page Detailed Changelog

### 1. `index.html` (Home Page)

#### 🚀 Features Added & Structural Implementation
* **Hero Banner Section (`.home-hero`):**
  * Added primary welcome message: `"Welcome to Kobe's Kitchen"`.
  * Added brand tagline subtitle: `"Fresh Food With a Unique Twist"`.
  * Included descriptive brand messaging highlighting Kasi flavour, generous portions, and welcoming atmosphere.
  * Embedded a primary Call-To-Action (CTA) button linking directly to the menu (`services.html`).
  * Integrated a high-resolution hero product photograph (`_images/burger (2).jpg`).
* **Introductory Section (`.home-intro`):**
  * Structured content block explaining the core food philosophy (*"Good Food, Great Taste"*).
  * Outlined product range including burgers, wings, fries, and cold beverages.
* **Product Highlights Grid (`.home-highlights`):**
  * Created four modular card blocks (`.home-card`) to highlight primary menu categories:
    * **Burgers Card:** Highlighted taste profile and crispy fries pairing.
    * **Wings Card:** Outlined flavor options and meal satisfaction.
    * **Fries Card:** Detailed side dish offerings.
    * **Drinks Card:** Highlighted the refreshing cold Fanta beverage selection.
* **Call-to-Action Bottom Banner (`.home-bottom`):**
  * Added closing invitation: `"Come Taste the Difference"`.
  * Embedded a secondary conversion button directing users to the contact page (`contact.html`).

---

### 2. `about.html` (About Us Page)

#### 🚀 Features Added & Structural Implementation
* **Brand Story Section (`.about-section` - Block 1):**
  * Integrated chef media asset (`_images/cheff.jpg`).
  * Written narrative detailing the humble origins of Kobe's Kitchen, starting from a small passion-driven project to a popular local culinary spot.
* **Mission Statement Section (`.about-section` - Block 2):**
  * Integrated community media asset (`_images/community.jpg`).
  * Outlined customer satisfaction goals, affordable pricing strategy, and non-negotiable commitments to fresh daily ingredients and consistent portions.
* **Value Proposition Section (`.about-section` - Block 3):**
  * Integrated team/kitchen staff media asset (`_images/staff.jpg`).
  * Detailed why customers choose Kobe's Kitchen: welcoming store atmosphere, careful order presentation, and high daily kitchen standards.
* **Community Connection Section (`.about-section` - Block 4):**
  * Integrated customer photograph (`_images/happy_customer.jpg`).
  * Documented local roots, highlighting independence from corporate chains/franchises and commitment to supporting the local neighborhood.

---

### 3. `services.html` (Menu & Pricing Page)

#### 🚀 Features Added & Structural Implementation
* **Menu Introductory Section (`.services-intro`):**
  * Added section heading `"Our Menu"` and overview text introducing the dish lineup.
* **Interactive Menu Grid Layout (`.services-grid`):**
  * Constructed eight individual dish cards (`.service-card`), complete with dish titles, pricing badges (`<h3>`), ingredients (`<p>`), and specific product photography:
    1. **Regular Burger with Fries:** Priced at **R50**. Ingredients: Beef or Chicken patty, Lettuce, Tomato, Onion rings, Sauce. Linked `_images/burger (2).jpg`.
    2. **Smash Burger with Fries:** Priced at **R70**. Ingredients: Double Beef or Chicken patty, Lettuce, Tomato, Onion rings, Sauce. Linked `_images/Burger 3.jpg`.
    3. **Monster Burger with Loaded Fries:** Priced at **R90**. Ingredients: Triple Beef or Chicken patty, Lettuce, Tomato, Onion rings, Bacon, Sauce. Linked `_images/Burger 4.jpg`.
    4. **Fire Burger with Loaded Fries:** Priced at **R120**. Ingredients: Rib patty, Lettuce, Tomato, Onion rings, Bacon, Sauce. Linked `_images/wings and fries (1).jpg`.
    5. **Sticky or Non-Sticky Wings:** Priced at **R55**. Description: Choice of flavorings. Linked `_images/wings (1).jpg`.
    6. **Crispy Fries:** Tagged as `"Included With Meals"`. Linked `_images/Fries 1.jpg`.
    7. **Loaded Fries:** Tagged as `"Available With Selected Meals"`. Linked `_images/Fries 2.jpg`.
    8. **Fanta Soft Drinks:** Priced at **R20**. Description: Cold selection. Linked `_images/drinks.jpg`.

---

### 4. `enquiries.html` (Enquiry Page)

#### 🚀 Features Added & Structural Implementation
* **Enquiry Header & Guidance (`.enquiries-heading`):**
  * Formulated clear user instructions inviting visitors to submit feedback or catering questions.
* **Google Form Integration (`.form-container`):**
  * Embedded a fully functional Google Form iframe (`https://docs.google.com/forms/...`).
  * Configured responsive dimensions (`width="640"`, `height="689"`).
  * Removed default iframe borders (`frameborder="0"`) and padded margins (`marginheight="0"`, `marginwidth="0"`).
  * Included fallback loading state text (`"Loading…"`).

---

### 5. `contact.html` (Contact Page)

#### 🚀 Features Added & Structural Implementation
* **Contact Information Section (`.contact-intro` & `.contact-details`):**
  * Structured two high-visibility contact cards (`.contact-card`):
    * **Call Card:** Displays direct store telephone line (`+27 66 399 3257`).
    * **WhatsApp Card:** Displays instant messaging business line (`+27 82 464 4856`).
* **Google Maps Location Integration (`.contact-map`):**
  * Integrated an interactive embedded Google Maps iframe pinpointing the physical address at **45 Krypton St, Clayville, Olifantsfontein, 1668**.
  * Configured security and performance attributes (`loading="lazy"`, `allowfullscreen=""`, `referrerpolicy="no-referrer-when-downgrade"`).

---

## 🛠️ Summary of Applied Technical Enhancements

| Feature / Technique | Implementation Location | Developer Benefit |
| :--- | :--- | :--- |
| **Semantic HTML5** | All 5 Files | Improved SEO indexing, screen-reader accessibility, and clean markup hierarchy. |
| **Modular CSS Linkage** | `<head>` across all files | Keeps styling decoupled from content; allows global updates via `style.css`. |
| **Image Asset Mapping** | `_images/` directory | Organizes all menu items, logos, and team photographs in a clean folder tree. |
| **Iframe Embedding** | `enquiries.html` & `contact.html` | Offloads data collection and map rendering to reliable external services (Google). |
| **Relative Pathing** | All hyperlinked elements | Ensures site links work flawlessly on any local device or web server. |