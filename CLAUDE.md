# Inzozi Events — project notes for Claude

## About the owner
- Hirwa, based in Kigali, Rwanda. Beginner at coding: explain every step simply, one step at a time, with exact clicks and copy-paste values.

## What this is
- Inzozi Events ("inzozi" = dreams): a wedding marketplace website for Rwanda.
- Couples browse curated wedding venues and vendors and contact them on WhatsApp for pricing.
- Categories: venues, photographers, decorators, DJs, MCs, caterers, serving staff, cakes, hair & makeup, florists, wedding cars, mushanana & attire, intore dancers, sound & lighting.
- Venue listing fields: name, district, area, map location, guest capacity, price range (RWF), parking (yes/no and number of cars), indoor/outdoor/both, catering included or bring your own, ceremonies (gusaba, civil/church, reception), photos (5–15), WhatsApp contact.
- Vendor listing fields: name, category, areas covered, starting price, portfolio photos, WhatsApp, short description.

## Business model
- Field agents visit venues and vendors, show them the site, and sign a contract. Listings are free at first.
- Later: monetize (commission or paid featured listings).
- Later: venues and vendors log in with email and manage their own profiles.

## Current status
- Live prototype: https://inzozi-events.vercel.app
- Hosting: GitHub repo `inzozi-events` connected to Vercel (auto-deploys when index.html changes).
- Site is a single file: `index.html` (plain HTML, CSS, JavaScript; no framework). Listings are sample data hard-coded in the script.
- Design: clean white style inspired by Hitched and Zola, deep rose accent, Cormorant Garamond + Figtree fonts, imigongo pattern. White by default, with a light/dark switch button.
- Domain plan: register `inzozievents.rw` through a RICTA-accredited registrar, then connect it in Vercel.

## Next steps
1. Connect a real database (Supabase) so listings come from the database instead of sample data.
2. Agent tool: a simple form for field agents to add listings and photos from their phones.
3. Admin page for Hirwa: approve, edit, publish listings; see which agent signed whom.
4. Later: venue/vendor self-service login, then a mobile app linked to the same database.
