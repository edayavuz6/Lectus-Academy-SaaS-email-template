📧 Lectus Academy — SaaS Welcome Email Template
Production-ready responsive email engineering using MJML & VML.

This project features a high-conversion, cross-client compatible welcome email designed for Lectus Academy, a fictional EdTech platform. It demonstrates the ability to bridge modern web design aesthetics with the rigorous technical constraints of email rendering engines (e.g., Microsoft Outlook).

🛠️ Technical Stack & Tools
Source Format: MJML 4 (Mailjet Markup Language)

Output: Compiled Cross-client HTML (Table-based)

Compatibility: VML (Vector Markup Language) for Outlook fallbacks

Typography: Google Fonts (Playfair Display & DM Sans)

Testing: Verified across Gmail, Apple Mail, Outlook (2016-365), and Yahoo Mail

🚀 Key Features & Engineering
Why MJML?
Email development is notoriously fragile due to lack of support for CSS Grid or Flexbox in major clients. MJML was chosen to:

Component-based Workflow: Manage complex nested <table> structures using semantic tags.

Outlook Hybrid Coding: Automatically generate VML for buttons and gradients.

Responsive by Default: Ensure a mobile-first grid system with reliable @media query support.

Design Decisions
Editorial Aesthetic: Utilized a warm, pastel-toned palette (#d4a478, #f5ede3) to create a human-centric, editorial feel rather than a generic SaaS look.

Typography Pairing: Combined Playfair Display (Serif) for headlines to add character and DM Sans (Sans-serif) for high legibility in body copy.

Visual Hierarchy: Features a 3-column card grid that gracefully stacks on mobile devices for optimal readability.

🔧 Optimizations & Compatibility
Advanced technical implementations included to ensure a professional user experience:

Outlook Compatibility Layer:

Implemented v:roundrect for pill-shaped buttons in Outlook 2010+.

Applied mso-table-lspace: 0pt; to eliminate phantom spacing issues in Windows-based Outlook clients.

Accessibility (A11y):

Used role="presentation" on all layout tables.

Included descriptive alt text for images and lang="en" attributes for screen readers.

🎨 Preview
Note: The design reflects the vibrant and creative identity of Lectus Academy, utilizing modern card layouts and a sophisticated color palette.

Maintained WCAG AA color contrast ratios throughout the design.

Inbox Preview: Injected a hidden 200-character preheader to control the "first impression" text in the user's inbox.
