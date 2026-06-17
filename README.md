# Peppercombe Cottages — Website

A complete, beautiful, self-contained single-file website for **Peppercombe Cottages**, the four holiday lets in Peppercombe Valley, North Devon (Coastguard Cottages 1–3 + Combe Cottage).

## Quick Start

1. Open `index.html` directly in any modern browser (double-click the file).
2. For production hosting:
   - Drag the whole folder (or just `index.html`) onto [Netlify Drop](https://app.netlify.com/drop)
   - Or upload to Vercel, GitHub Pages, Cloudflare Pages, etc.
   - No build step required.

## Name & Domain Recommendations

**Recommended name:** **Peppercombe Cottages**

This is clean, memorable, and exactly matches the historic name used by the National Trust listing. It feels premium and authentic.

**Strong domain options** (check availability):
- `peppercombecottages.co.uk` ← **Best choice**
- `peppercombe.co.uk`
- `peppercombevalley.co.uk`
- `peppercombeholidays.co.uk`
- `coastguardcottages.co.uk`

## Photos Used

This site now prioritizes the real photos from the Rightmove listing you shared (https://www.rightmove.co.uk/properties/89190456) and assigns them to the Coastguard Cottage cards and detail galleries:

- All three Coastguard Cottages (1, 2, and 3) now feature the authentic Rightmove photos in both their overview cards and the image galleries inside the detail modals (cycled for variety).
- Combe Cottage also includes them as additional views.

Higher-resolution versions were used where possible by updating the size parameter to `_max_1182x788.png`.

**To get all 12 professional photos:**
1. Open the Rightmove link you provided.
2. Click through the full media gallery (it says 12 photos).
3. Right-click → "Save image as..." for the high-quality versions, or use a browser extension to bulk-download.
4. Replace the `media.rightmove.co.uk` URLs in `index.html` (search for that domain) with your own hosted/optimized versions (strongly recommended for production and speed).

The remaining images are high-quality coastal placeholders that match the peaceful North Devon aesthetic until you swap in the full set.

## Customization Guide

### Easy changes (search & replace)
- Owner names → currently "Ash & Sammi"
- Phone number and email in the Contact section
- Prices (currently starting from £125–£155/night)
- Cottage descriptions and feature lists (fully accurate to the National Trust particulars)

## Built-in Editor (New!)

The site includes a simple in-browser editor:

1. Scroll to the very bottom of the footer and click **"Editor login"**.
2. Use the demo password: `pepper2026`
3. Once inside Editor Mode you can:
   - Click almost any heading or paragraph to edit the text live
   - Drag the four cottage cards to reorder them
   - Drag the testimonial cards to reorder them
   - Click **Save** to persist changes in your browser (localStorage)
   - Click **Export** to download a new `peppercombe-cottages-edited.html` with all your changes baked in (this is how you make edits permanent)
   - **Reset** to go back to the original content

This is a lightweight, no-backend solution perfect for quick updates before handing the file to a developer or deploying. For a real multi-user CMS you would later connect it to a proper backend.
- Instagram handle

### Adding real availability
The "Check availability" and booking forms are fully functional in demo mode (they show nice success messages). 

For real bookings you can:
- Embed a Calendly / TidyCal / Your own booking system
- Connect a form service (Formspree, Netlify Forms, Basin, etc.)
- Replace the fake availability checker with a real calendar once you have a booking engine

### Colors
The palette is warm coastal:
- Deep sea teal: `#1E5F74`
- Sage green: `#5C7457`
- Warm sand: `#C9B896`
- Cream: `#F7F3EB`
- Charcoal: `#0D3B45`

Easily tweak in the CSS variables at the top of the `<style>` tag.

## Key Content Included

- Accurate cottage specifications taken directly from the National Trust / Rightmove listing
- Personal, warm About story (based on your brief: local surfer, previous holiday let experience, life change to spend more time with family)
- Strong National Trust / coastal / peaceful positioning
- All required sections: Home/Hero, Cottages, Valley & Location, About, Bookings, Things To Do, Contact
- Mobile-first responsive design with excellent performance (single file, Tailwind CDN)
- SEO-ready meta tags and structure

## Deployment Tips for Best Results

- Host the images yourself (or use a CDN) for the fastest loading and full control.
- Add a real favicon and Apple touch icon.
- Consider adding a simple blog or "Journal" section later (stories from the valley).
- You can split this into a proper multi-page site later if you grow, but a single beautiful page converts extremely well for holiday lets.

## Support

This is a complete, production-ready starting point. You can edit everything in any text editor (VS Code recommended).

Let me know if you want:
- A version with a real calendar widget
- Separate pages instead of one long scroll
- Integration with a booking system
- More photography direction / image editing help

Enjoy the valley — it looks like a very special place.

— Grok
