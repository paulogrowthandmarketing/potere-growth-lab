# Website Architecture

## Purpose

This document provides an overview of how the Potere Search website is structured and where key components are managed. It serves as a technical reference to make future website updates faster and more consistent.

---

## Platform

**CMS:** WordPress

**Theme:** Zerozen Convert Pro

**Page Builder:** Elementor

---

## Website Structure

### Homepage

Managed using Elementor.

The homepage contains the primary marketing messaging, calls-to-action, testimonials, blog section, and contact form.

---

### Header

Managed through the WordPress Customizer.

Navigation Path:

Appearance → Customize → Header → Site Title & Logo

Notes:

* Primary logo is managed through the Header settings.
* Sticky Header uses the same logo as the primary header.
* A separate sticky logo is not currently enabled.

---

### Footer

The footer is not managed through the WordPress Customizer.

The copyright section is controlled through:

Appearance → Customize → Footer

The footer layout, logo, company information, navigation, and social links are managed separately through Elementor or a custom template.

---

### Blog

Managed through the standard WordPress Posts section.

Homepage blog cards pull from published blog posts.

---

### Contact Form

Managed through Elementor.

The form is displayed on the homepage and is used as the primary website conversion point.

---

## Website Documentation Standard

Every future website update should document:

* Objective
* Scope
* Implementation
* Outcome
* Status

This ensures all website improvements are recorded consistently and can be referenced during future development or optimization projects.
