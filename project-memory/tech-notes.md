# Technical notes

## Files

| File | What it is |
| --- | --- |
| `index.html` | The landing page. Images use `canva://` links with an automatic fallback to the local copies in `assets/`, so this single file still pastes into Canva and also opens correctly as a plain file outside it. |
| `specialties.html` | Specialty care page with eight specialties. |
| `primary-care.html` | Primary care page with four visit types: annual physicals, vaccinations, chronic conditions, and referrals and care coordination. |
| `imaging.html` | Diagnostic imaging page with four scan types: X-ray and fluoroscopy, ultrasound, CT scan, and MRI and mammography. |
| `doctors.html` | Find a doctor directory with nine sample doctors. |
| `patient-portal.html` | Sample patient portal preview: a sidebar with Dashboard, Appointments, Secure messages, Medications, Test results, Billing & insurance and Find care & support, previewable as three sample patients. |
| `donate.html` | Giving and donations page: six ways to give (one-time, monthly, memorial/tribute, corporate/matching, planned giving, volunteering) plus a "Where your gift goes" impact section. Every option routes to the landing page's contact form rather than a real payment flow. |
| `sources.html` | Sources and notes: brand rationale, name, course and all source credits. |
| `assets/` | Logo, hospital photo backups. |
| `screenshots/` | Full-page screenshots of every page at several sizes. |
| `DESIGN_REVIEW.md` | The formal design review and list of changes. |

## Running it

- Open `index.html` in a browser, or use VS Code's Live Server extension. Keep all the files and the `assets/` folder together.
- Photos, fonts, icons and Tailwind load from the internet, so an internet connection is needed.

## Things to know

- **Canva is one page.** The Specialty care, Primary care, Diagnostic imaging, Find a doctor and Patient portal pages only work as files, not inside Canva.
- **The request form** needs Canva's data connection. Outside Canva it shows an "unavailable" message, which is expected. Canva's data collection may need a `contact_detail` field and the reasons "Billing or insurance" and "Class or event sign-up".
- **Event dates** are set for October and November 2026. Update them if showing the site later.
- **Live hours** use Eastern time (America/New_York).
- **Form reasons from links:** pages can pre-fill the form with `index.html?reason=Requesting%20an%20appointment#contact`. Only reasons that exist in the form are accepted. The `gift` parameter (for example `index.html?reason=Giving%20and%20donations&gift=monthly%20giving#contact`) pre-fills the message field the same way `doctor` and `service` do.
- **Header search** on `doctors.html`, `primary-care.html`, `specialties.html`, `imaging.html`, `patient-portal.html`, `sources.html` and `donate.html` sends doctor-sounding queries to `doctors.html?q=...` and everything else to `index.html?search=...#find-care`, which auto-runs the landing page's own service filter on load.

## Ideas for the portfolio version

- Host it for free on GitHub Pages or Netlify so it has a real link.
- Replace the Tailwind CDN with a built stylesheet for faster loading.
