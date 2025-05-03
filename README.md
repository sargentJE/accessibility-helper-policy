# Privacy Policy - MyVision Accessibility Helper Chrome Extension

This repository contains the source HTML file for the Privacy Policy page of the **MyVision Accessibility Helper** Chrome Extension.

## Purpose

This HTML page serves as the official Privacy Policy document for the extension. Its primary goals are:

1.  **Transparency:** To clearly inform users about what data the extension collects, how it's used, and how it's protected.
2.  **Compliance:** To meet the requirements set by the Chrome Web Store and relevant data protection regulations.
3.  **User Trust:** To build trust by being open about data handling practices.

## Structure of the HTML (`index.html`)

The `index.html` file is a single-page document with the following key components:

*   **Header:** Displays the title of the policy and the "Last updated" date.
    *   *Note:* The "Last updated" date needs to be manually updated whenever the policy changes.
*   **Main Content:** Contains the core sections of the Privacy Policy:
    *   Introduction
    *   What Information We Collect
    *   How We Use Your Information
    *   Data Storage & Security
    *   Third-Party Sharing
    *   Your Rights
    *   Data Minimisation Commitment
    *   Limited Use Statement (Compliance with Google API Services User Data Policy)
    *   Changes to This Policy
    *   Contact Us
*   **Footer:** Contains copyright information.
    *   *Suggestion:* Consider adding a link back to the main MyVision website here.

## Styling and Technical Details

*   **Inline CSS:** All styles are included within `<style>` tags in the `<head>` for simplicity and portability.
    *   *Consideration:* The CSS includes a comment questioning whether to link an external font stylesheet instead of using `@import`.
*   **Design Tokens:** Uses CSS custom properties (variables like `--color-primary`, `--font-size-base`, etc.) for theming and consistency, based on a "MyVision design tokens" system.
*   **Responsiveness:** Includes basic media queries to adapt the layout for smaller screens (phones) and larger desktops.
*   **Accessibility:**
    *   Includes a `prefers-reduced-motion` media query to disable transitions for users who prefer reduced motion.
    *   Contains comments reminding developers to ensure color contrast meets WCAG AA standards.
*   **Fonts:** Uses the 'Inter' font family, imported from Google Fonts.

## Key Policy Points & Notes from Code

*   **Data Collected:** Includes URLs, form responses, browser info, settings, email, and auth token (for sign-in).
    *   *Question:* A comment asks to double-check if the list of collected data is exhaustive.
*   **Data Usage:** Primarily for aggregating feedback, improving the extension, and research.
*   **Security:** Emphasizes HTTPS communication, encryption in transit, and secure storage.
    *   *TODO:* A comment suggests specifying the data retention period more concretely.
*   **Third-Party Sharing:** Explicitly states data is *not* shared except when required by law, with consent, or in anonymized/aggregated form.
*   **User Rights:** Users can access, export, delete their data, or opt-out by contacting `accessibility@myvision.org.uk`.

## Contact

For any questions regarding this privacy policy or the extension's data practices, please contact:

*   **Email:** `Info@MyVision.org.uk`
*   **Website:** `www.MyVision.org.uk`
*   **Address:** MyVision Oxfordshire, Bradbury Lodge, Gordon Woodward Way, Oxford, OX1 4XL, United Kingdom

---

&copy; 2025 MyVision Oxfordshire. All rights reserved.
