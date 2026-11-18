# Everly — Thrissur Wedding Marketplace Prototype

A responsive, front-end-only wedding marketplace demo focused on Thrissur, Kerala. Couples can discover local venues and wedding professionals, filter by service, locality, and guest count, save profiles, and send date-specific availability inquiries. Providers can manage demo listings and respond to inquiries. Admins can review and approve new listings.

## Run locally

Open `index.html` in a browser. No install, build step, backend, or database is required.

For best compatibility with browser storage and local navigation, you can optionally run a local static server from this folder:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Demo accounts

| Role | Email | Password |
|---|---|---|
| Couple | `couple@everly.demo` | `Wedding2026!` |
| Venue / professional | `hello@willowstone.demo` | `Venue2026!` |
| Administrator | `admin@everly.demo` | `Admin2026!` |

The sign-in screen also has one-click demo account selection. Demo credentials and inquiry records are fictional. The provider account manages the fictional “Everly Demo Venue” profile; it is not connected to any business in the public sample directory. The pending admin-review listing is also fictional.

## Local sample profiles and sources

The default directory is a small Thrissur-area sample, not a complete venue or provider inventory:

- [Sree Parvathy Auditorium](https://sreeparvathy.com/) — Ollur; the venue website describes an auditorium with 500+ seats and a dining hall for 200+.
- [Linus Auditorium](https://www.wedmegood.com/wedding-venues/linus-auditorium-4132443) — Kottekkad/Kuttoor; a public WedMeGood listing reports 600 seated / 700 floating guests and ₹35,000 per function.
- [Zip By Spree Hotels Mangala Towers](https://www.google.com/search?q=Zip+By+Spree+Hotels+Mangala+Towers+Thrissur+wedding+banquet) — Patturaikkal; public directory search results show indicative vegetarian menu pricing of ₹300–₹600 per person and banquet capacity estimates.
- [Dreams Wedding Creation](https://dreamsweddingcreation.com/) — Thrissur wedding photography and videography business.
- [Nuptials by Nostalgia](https://www.google.com/search?q=Nuptials+by+Nostalgia+Thrissur+wedding+photography+packages) — a local photography/film sample; the displayed rate range is a third-party directory estimate, not a provider-confirmed quote.
- [Melodia Event Management](https://eventsmanagementkerala.com/) — public website describes wedding planning and venue selection across Kerala.

Public information can change. Directory rates and capacity figures are indicative and may be outdated, incomplete, or subject to package conditions. Confirm current details, taxes, inclusions, availability, and final prices directly with providers. Everly is not affiliated with or endorsed by the listed businesses. Profile photos are illustrative Unsplash images, not provider portfolio photographs. The app does not claim that public listing content has been verified by the businesses.

## What works in the prototype

- Search wedding providers by category, location, date, and guest count.
- Browse local venue, photography, catering, and wedding-planning sample profiles.
- Open profiles and public source links, save favorites, and send availability inquiries.
- Review inquiries in a couple dashboard.
- Add provider listings, preview them, and respond to inquiries.
- Submit new listings for admin review and approve or decline them.
- Sample listings and inquiries are stored in browser `localStorage` only.

## Prototype limits

There is no real account system, database, geocoding, live map, email delivery, live calendar, payment processing, or real booking confirmation. Demo passwords and user roles are client-side examples and must not be used as real authentication. The map area is explicitly a placeholder. Availability must be confirmed by each provider; sending an inquiry is not a booking.

The page uses remote Unsplash photos and Google Fonts; a network connection is needed to load these assets.
