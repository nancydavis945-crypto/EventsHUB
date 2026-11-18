# Everly — Thrissur Marriage Discovery Prototype

A responsive, front-end-only matchmaking prototype for adults in Thrissur, Kerala who are looking for marriage. The main screen is a swipe feed of fictional member profiles, with a clearly labeled wedding-service promotion after every three people. Venues, photographers, catering, and wedding professionals are advertisements and directory listings—not member profiles. A separate events page shows illustrative local wedding events.

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
| Member | `couple@everly.demo` | `Wedding2026!` |
| Venue / professional | `hello@willowstone.demo` | `Venue2026!` |
| Administrator | `admin@everly.demo` | `Admin2026!` |

The sign-in screen has one-click demo account selection. All credentials, member profiles, and inquiry records are fictional. The profile photos are illustrative stock images, not photos of real members. The provider account manages the fictional “Everly Demo Venue”; the pending admin-review listing is fictional too.

## Local sample profiles and sources

The wedding-services directory and sponsored cards use a small Thrissur-area business sample, not a complete inventory:

- [Sree Parvathy Auditorium](https://sreeparvathy.com/) — Ollur; the venue website describes an auditorium with 500+ seats and a dining hall for 200+.
- [Linus Auditorium](https://www.wedmegood.com/wedding-venues/linus-auditorium-4132443) — Kottekkad/Kuttoor; a public WedMeGood listing reports 600 seated / 700 floating guests and ₹35,000 per function.
- [Zip By Spree Hotels Mangala Towers](https://www.google.com/search?q=Zip+By+Spree+Hotels+Mangala+Towers+Thrissur+wedding+banquet) — Patturaikkal; public directory search results show indicative vegetarian menu pricing of ₹300–₹600 per person and banquet capacity estimates.
- [Dreams Wedding Creation](https://dreamsweddingcreation.com/) — Thrissur wedding photography and videography business.
- [Nuptials by Nostalgia](https://www.google.com/search?q=Nuptials+by+Nostalgia+Thrissur+wedding+photography+packages) — a local photography/film sample; the displayed rate range is a third-party directory estimate, not a provider-confirmed quote.
- [Melodia Event Management](https://eventsmanagementkerala.com/) — public website describes wedding planning and venue selection across Kerala.

Public information can change. Directory rates and capacity figures are indicative and may be outdated, incomplete, or subject to package conditions. Confirm current details, taxes, inclusions, availability, and final prices directly with providers. Everly is not affiliated with or endorsed by the listed businesses. Profile photos are illustrative Unsplash images, not provider portfolio photographs. The app does not claim that public listing content has been verified by the businesses.

## What works in the prototype

- Open to a full-screen swipe feed of six fictional adult member profiles from Thrissur, with one service promotion after every three profiles. The feed loops after the second promotion.
- See clearly labeled sample promotions for wedding venues, photography, catering, and other services. These mock placements are not paid ads.
- Save member profiles to a shortlist and view them in the member dashboard.
- Browse the separate wedding-services directory and explore the separate sample events page.
- Save events and wedding services, and send demo availability inquiries to service providers.
- Add provider listings, preview them, and respond to inquiries; admins can approve or decline listings.
- Member profiles, events, provider listings, and inquiries are sample data stored in browser `localStorage` only.

## Prototype limits

There is no real account or matching system, database, geocoding, live map, email delivery, live calendar, ad payment system, or real booking confirmation. Demo passwords and user roles are client-side examples and must not be used as real authentication. Member profiles and events are fictional; service providers have not paid to appear. The map area is a placeholder. Availability must be confirmed by each provider; sending an inquiry is not a booking.

The page uses remote Unsplash photos and Google Fonts; a network connection is needed to load these assets.
