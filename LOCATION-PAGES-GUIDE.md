# Location Pages — Setup & Scaling Guide

## Files in this batch
- `face-painter-horsham.html`
- `face-painter-guildford.html`
- `areas.html` — a hub page linking to both, and to any future town pages

## Step 1: Upload
Upload all 3 files to your repo root (same place as your other HTML files), same method as before — this time there's no need to touch or re-upload the 4 existing pages, so it should be a clean, low-risk addition.

## Step 2: Link to it from your main nav (optional but recommended)
To help Google discover these pages and pass authority to them, add an "Areas" link to your main nav. In each of your 4 existing pages, find this block:

```html
<a href="gallery.html">Gallery</a>
<a href="contact.html">Book</a>
```

Change it to:

```html
<a href="gallery.html">Gallery</a>
<a href="areas.html">Areas</a>
<a href="contact.html">Book</a>
```

This is a small, low-risk edit — just one line added per page, four times.

## Step 3: Submit to Google
Once live, go to **Google Search Console → URL Inspection**, paste in each new page's URL (e.g. `https://www.thepaintingpixie.co.uk/face-painter-horsham.html`), and click **Request Indexing**. This nudges Google to crawl the new pages faster rather than waiting for natural discovery.

## Adding more towns
To add a new town (say, Crawley), duplicate `face-painter-horsham.html`, rename it `face-painter-crawley.html`, and update:
1. `<title>` and meta description
2. Canonical URL and Open Graph URL
3. The JSON-LD schema `"name"` and `"url"` fields
4. `<h1>` and all visible "Horsham" mentions
5. The local landmark reference (e.g. "Denne Park and Hills Farm" → an actual Crawley landmark — a genuine local detail matters more for trust and SEO than just swapping the town name)
6. The testimonial name/location
7. Add a new card for it on `areas.html`

**Important**: don't just find-and-replace the town name and leave everything else identical across pages — Google can treat near-duplicate content across many location pages as low-value ("thin content"), which can hurt rather than help. Each page should have at least one or two genuinely distinct sentences (a real landmark, a specific venue you've worked at, a real local testimonial) so it reads as authentic rather than templated.

## Suggested next towns (based on Sussex/Surrey coverage)
Crawley, Lewes, Chichester, Worthing, Redhill — pick towns where you actually get bookings from, since Google can tell when a page doesn't match real business activity over time (e.g. no reviews or citations ever appearing from that area).
