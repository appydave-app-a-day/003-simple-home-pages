# 📄 Support Signal Landing Page – Requirements Document

## 🎯 Project Scope

Develop a single, static landing page using **pure HTML** and **Tailwind CSS**. No JavaScript frameworks or backend integrations are permitted. The page must serve as a marketing front for the Support Signal SaaS platform, driving awareness and conversions among NDIS service providers and stakeholders.

---

## 🧱 Tech Stack

* **HTML5** (semantic structure required)
* **Tailwind CSS v3+** (utility-first styling)
* No JavaScript frameworks (e.g., no React, Vue, Alpine)
* Optional: minimal vanilla JS for form validation if required

---

## 🖼️ Page Structure & Sections

1. **Hero Section**

   * Headline, tagline, short description
   * Primary call-to-action button
   * Optional background image or abstract visual element

2. **Key Features**

   * 3–4 feature blocks with icon/image, title, and short text

3. **Who It's For**

   * Grid or column layout describing 3–4 target personas

4. **Compliance & Intelligence Section**

   * Explains how the platform supports NDIS compliance and operational insight

5. **Testimonials**

   * Quotes or short excerpts from early adopters or pilot partners

6. **FAQs**

   * List format with questions and collapsible/expandable answers (static HTML allowed)

7. **Call to Action (CTA)**

   * Re-emphasized sign-up / get started message with clear CTA

8. **Footer**

   * Navigation links, contact info, copyright

---

## 🗺️ Layout Guidance

* **Responsive Design**: Mobile-first, fluid grid layout
* **Typography**: Clear hierarchy using Tailwind’s font and spacing utilities
* **Color Scheme**: Defined in brand-details document (access assumed)
* **Visual Balance**: Alternate light/dark sections for clarity and flow
* **Buttons**: Primary and secondary CTA button variants

---

## 📤 Forms & Functionality

* **Lead Capture Form** (in CTA or Hero section)

  * Fields: Name, Email, Organisation (text inputs)
  * Submit action: mailto: link or webhook placeholder
  * No backend logic—submit action handled outside the static page

---

## 🌐 Hosting & Deployment

* Designed for deployment on **static hosting** platforms such as:

  * Vercel, Netlify, GitHub Pages, Firebase Hosting
* No CMS integration required
* Export as self-contained HTML/CSS asset folder

---

## 🔍 SEO Metadata

* **Page Title**: Support Signal – Smarter Supports for NDIS Providers
* **Meta Description**: Discover Support Signal, the AI-powered incident intelligence platform for NDIS providers. Turn compliance into insight.
* **Keywords**: NDIS platform, incident reporting, support provider software, compliance intelligence, AI SaaS NDIS

---

## 🖼️ Media & Assets

* Images, logos, icons, and colors referenced from **brand-details document**
* Developer will receive image files in optimized formats (`.svg`, `.png`, `.webp` as needed)
* Placeholder copy/text may be used if not provided

---

## ✅ Final Deliverables

* `index.html` – Main landing page file
* `tailwind.css` – Compiled stylesheet
* `/assets` – Folder with images and media
* `README.md` – Short notes on deployment and file structure

---

> 📎 NOTE: Branding, tone, and persona details should be guided by the **brand-details** and **persona** documents accessible to the developer at time of build.
