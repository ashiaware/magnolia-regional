# Case study: Magnolia Regional Medical Center

## Overview

Magnolia Regional Medical Center is a fictional regional hospital in Laurel Springs, Georgia. The assignment for Web Graphics II (CIST 2531) was to design a hospital landing page. The project grew into a five-page site: a landing page, a Specialty care page, a Find a doctor directory, a sample patient portal preview, and a project notes page that explains the brand and credits every source.

The real Wellstar Cobb Medical Center website (Wellstar Health System) was the source material for what a hospital site needs to include.

## The problem

Hospital websites are often cold and hard to scan. People usually visit them when they are stressed, sick, or caring for someone else. They need three things fast:

1. What to do in an emergency
2. How to find the right care or doctor
3. Practical details: where to go, when it is open, how to pay and how to get in touch

The goal was a site that answers those questions quickly while feeling warm and human instead of clinical.

## Goals

- Put emergency guidance first, on every page.
- Make finding care and finding a doctor the main paths.
- Give the hospital a distinctive brand that feels local and welcoming.
- Meet accessibility standards (WCAG AA contrast, keyboard use, screen readers, reduced motion).
- Work well on phones, tablets and desktops.
- Be honest: label sample content and credit every source.

## Key design decisions

### A magnolia brand
- The southern magnolia is an iconic tree of the American South, including Georgia, so the name and logo feel local.
- Magnolias are long-lived and bloom year after year, which supports the tagline "Care, nurtured to last."
- A flower is softer and more personal than the crosses and hearts most hospital logos use.

### A plant-inspired palette
- Every color comes from the magnolia: forest green leaves, ivory blooms, blush petals, mint new growth, plum buds.
- Natural tones feel calm and set the site apart from the usual hospital blue.
- Deep rose is reserved for emergencies, so urgent information stands out.
- Every text color was checked to meet WCAG AA contrast.

### A hospital photo with plants built in
- The building's terraced, planted balconies echo the palette and the "care that grows with you" idea.
- Bright daylight makes the hospital feel hopeful, and the covered walkway suggests an easy-to-navigate campus.
- The first image had the logo baked into it, so it was replaced with a clean photo that lets the site's own logo lead.

### Emergency care first
- A dark emergency bar sits at the top of every page.
- Emergency care is the largest card in the Find care section, with an ambulance photo, an "Open 24 hours" badge and a tap-to-call 911 link.
- The emergency entrance and ambulance bay are marked on the campus map.

### Clear paths instead of long lists
- The landing page shows four main care options. Specialties moved to their own page so the landing page stays focused.
- Every service and doctor card has one clear next step, and appointment buttons fill in the request form's reason automatically.

## Features

- **Live hours.** Each service shows "Open now" or "Closed now" based on the current time in Georgia.
- **Search.** Service search on the landing page, and doctor search by name, specialty or language.
- **Doctor directory.** Nine sample doctors with photos, languages, availability and an "Accepting new patients" filter.
- **Campus map.** An illustrated, embedded-style map with zoom, drag and keyboard controls, an ER marker and directions.
- **Request form.** Shows a phone or email field based on how the person wants a reply, validates each field with clear messages, and prevents double submissions.
- **Signature interaction.** Cards fill with forest green from the bottom on hover or keyboard focus.
- **Calm motion.** Sections fade in gently as you scroll, and the effect switches off when a device asks for reduced motion.
- **Insurance and billing, FAQ, classes and events**, plus a grouped footer with language assistance.
- **Trust badges.** A "Recognized for quality care" row (Joint Commission accredited, Magnet recognized nursing, an "A" safety grade from Leapfrog, Top 100 rural and community hospital), labeled as sample recognitions.
- **Patient portal preview.** A separate page with a sidebar nav across seven sections (Dashboard, Appointments, Secure messages, Medications, Test results, Billing & insurance, Find care & support), previewable as three sample patients: an adult managing their own care, a parent managing a child's care, and a teen with a guardian's oversight on some records. Appointments link to the matching doctor in the Find a doctor directory, and a sample MRI result links straight to the Diagnostic imaging page.

## Accessibility

- WCAG AA contrast on every text and background pair (one gray was darkened during the design review to pass).
- Skip link, landmarks, labeled form fields and visible focus rings.
- Tap targets of at least 44 by 44 pixels.
- Keyboard-operable map, menus and dialogs, with focus kept inside open dialogs.
- Alt text on every meaningful image, and status information that never relies on color alone.
- Reduced-motion support.

## Process and tools

- Design reviews used the ui-ux-pro-max, design-master and design-review guidelines (hierarchy, contrast, layout variety, interaction states).
- Built and refined with help from Claude, an AI assistant, which wrote and revised code and ran checks at Ashia's direction. The logo was generated with ChatGPT.
- Every change was checked in a browser at desktop, tablet and phone sizes, with full-page screenshots.
- See [design-iterations.md](design-iterations.md) for each round of feedback.

## Results

- A seven-page site that works across screen sizes, with no sideways scrolling down to 320px.
- A distinctive, consistent brand documented in a brand guide.
- Every photo, font, library and source credited with an APA citation.

## What I would do next

- Turn the Specialty care, Find a doctor and Patient portal pages into a multi-page Canva site, or host the whole site online.
- Add real appointment scheduling and sign-in to the patient portal, beyond the sample preview.
- Run usability tests with a few people to see how quickly they find emergency info, a doctor and the portal.
