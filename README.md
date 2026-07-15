# PracticePlan — Homepage & Search Redesign

A modernized UI/UX prototype for PracticePlan covering three connected experiences:
homepage, search results, and the booking modal.

## Pages
- `index.html` — Homepage (search-first hero, activity browse, how-it-works, facility-owner section)
- `search.html` — Search results + booking modal (week/calendar date picker, live price, skeleton & empty states)
- `facility.html` — Facility detail page (gallery, sticky booking card, spaces list with add-on pricing)

## Design system
- **Fonts:** Barlow + Barlow Condensed (Google Fonts)
- **Palette:** Blue `#0076bb` · Green `#00a84f` · Navy `#0e2233`
- **Radius scale:** 10px (small controls) · 14px (cards/banners) · 20px (large surfaces) · 999px (pills)
- **Color rule:** green = commitment actions only (Search, Book); blue = brand + wayfinding
- Logos & facility photos load from PracticePlan's Cloudinary

## Notes
- Pure static HTML/CSS/JS — no build step
- Testimonials and some pricing are placeholder sample data
- Fully responsive; respects prefers-reduced-motion
