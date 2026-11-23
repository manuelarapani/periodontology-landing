# Periodontology ONE — Landing page

Landing page for **Periodontology ONE** (Active Recall Dentistry), by Dr. Manuela Rapani: an evidence-based flashcard study system in three volumes of 60 cards, with a waitlist for the web app.

- `index.html` — main page, in Italian.
- `en/index.html` — English page, at `/en/`.
- `og-image.png`, `en/og-image.png` — preview images used when the link is shared.
- `cards.html` — old sample-cards link, now redirects to the sample cards on the main page.
- `fonts/` — Lato, Poppins and Roboto Mono, served from this site instead of Google Fonts (SIL Open Font License, see `fonts/OFL.txt`).

Each page is a single file apart from the shared fonts. Waitlist sign-ups go to Brevo with double opt-in: the Italian page feeds the list "Waitlist Periodontology ONE - IT", the English page the list "Waitlist Periodontology ONE - EN". After the confirmation link Brevo sends people back to `#thanks`; right after submitting, the page shows `#check`. Visits are counted with GoatCounter (no cookies). The privacy notice is inside each page.

Published with GitHub Pages.
