# Phase 1 Changes — What I Did & What You Still Need To Do

## Files included
- `index.html`, `about.html`, `gallery.html`, `contact.html` — replace your 4 existing pages with these
- `logo-nav.png` — your logo, cropped square, added to the nav bar on every page
- `favicon.ico`, `favicon-32x32.png`, `favicon-16x16.png`, `apple-touch-icon.png` — generated from your logo, added to every page's `<head>` so it shows as the browser tab icon and iOS home-screen icon

## Logo integration (updated)
I cropped your uploaded logo to a clean square and generated all the standard favicon sizes from it. I also now have your real `style.css`, so the nav logo is properly styled via CSS (a `.nav-logo-link` class) rather than inline styles — it sits as a clean 44px circle to the left of your nav links, excluded from the pink pill hover-background so it doesn't look odd on hover.

**Upload all of these to your repo root, replacing the existing files:**
- `index.html`, `about.html`, `gallery.html`, `contact.html`
- `style.css`
- `logo-nav.png`, `favicon.ico`, `favicon-32x32.png`, `favicon-16x16.png`, `apple-touch-icon.png`

## What I fixed automatically

**index.html**
- Added meta description, canonical URL, Open Graph tags (so shared links look good on WhatsApp/Facebook)
- Added LocalBusiness schema markup (helps Google understand your business for local search)
- ⚠️ Replaced the mismatched "CrossFit" testimonial with a **placeholder** — see below, this is NOT real and must not go live as-is
- Removed all 4 Star Wars images from the "Popular Designs" section, replaced with the 2 non-licensed images available (blue.jpg, other.jpg)

**gallery.html**
- Reordered so original/non-licensed images appear first
- Removed "Darth Maul.jpg" (the space in the filename can break links/SEO)
- Softened alt text on remaining licensed-character images so it doesn't name the specific IP (reduces some search-indexing association, though the visual content itself is still a licensing consideration)

## ⚠️ Action needed from you — testimonial

I wrote a placeholder line for "Liam, Horsham" so the page isn't broken, but **it is not a real quote**. Please do one of the following before this goes live:
1. Replace it with an actual quote from a real client (screenshot text, review, thank-you message), or
2. Delete that testimonial box entirely

Publishing an invented quote as if it's a genuine customer testimonial is a real legal risk in the UK (the CMA treats fake reviews/testimonials as a consumer protection breach) — not just an SEO nicety.

## ⚠️ Action needed from you — GitHub steps I can't do for you

1. **Rename or remove `Darth Maul.jpg`** in your repo (the space in the filename is bad practice). I've already removed the reference to it from gallery.html, so you can safely delete the file, or rename it to `darth-maul.jpg` and re-add it later if you want to keep it as an example.
2. **Upload the two corrected files** (`index.html`, `gallery.html`) to your repo, replacing the existing ones — either via GitHub's web "upload file" feature or `git add / commit / push` if you're using the command line.
3. **Test the Formspree form again** after any changes to confirm it's still working.

## Still to do (bigger Phase 1 item)

- **New photography**: right now, the only non-licensed-character images available are `blue.jpg`, `other.jpg`, `kat.jpg`, `kat2.jpg`. To properly move away from Star Wars/Marvel imagery (both for legal safety and premium positioning), you'll want a proper photography session of your actual original designs — florals, animals, fantasy, glitter/sparkle work — shot consistently (good lighting, similar background/style). This is the single highest-impact thing left in Phase 1.

Once you've got new photos, send them over and I'll help you slot them into the gallery and homepage properly.
