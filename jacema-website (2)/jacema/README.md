# Jacema Global Services — Website

## Files Included
- `index.html` — Main HTML file
- `style.css` — All styles & responsive design
- `script.js` — Interactions, animations, particles

## How to Use
1. Open `index.html` in any browser to preview
2. Replace placeholder content:
   - Update phone number: search for `+234 800 000 0000`
   - Update email: search for `info@jacemaglobal.com`
   - Update address as needed
   - Replace social media links (Instagram, Twitter, Facebook, etc.)
3. To add real images, replace the `.hero-img-placeholder`, `.about-placeholder` etc. divs with `<img>` tags

## Adding Real Photos
The site uses styled placeholder boxes for images. To add your real photos:
1. Put your images in the same folder
2. In `index.html`, replace placeholder divs like:
   ```html
   <div class="about-placeholder"><i class="fa-solid fa-building"></i></div>
   ```
   with:
   ```html
   <img src="your-image.jpg" alt="Description" style="width:100%;height:100%;object-fit:cover;">
   ```

## Sections
1. **Hero** — Full-screen landing with animated text and floating cards
2. **Ticker** — Scrolling services marquee
3. **About** — Company story and pillars
4. **Services** — All 7 service cards with hover effects
5. **Why Choose Us** — Dark section with 4 key differentiators
6. **Portfolio/Clients** — Client categories + 4-step process
7. **Testimonials** — 3 client review cards
8. **CTA Banner** — Call/WhatsApp prompt
9. **Contact** — Form + contact details + social links
10. **Footer** — Links, socials, copyright

## Features
- Custom cursor (desktop only)
- Page loader animation
- Smooth scroll
- Mobile hamburger menu
- Header changes on scroll
- Scroll reveal animations
- Counter animations (500+, 200+, 7+)
- Floating particle canvas (hero section)
- 3D tilt effect on service cards
- Active social media links (Instagram, Twitter/X, WhatsApp, Facebook, LinkedIn)
- Form submit feedback
- Back to top button
- Fully responsive (mobile, tablet, desktop)

## Customization Colors
In `style.css`, edit the `:root` variables:
```css
--green: #1B6B3A;       /* Main brand green */
--green-light: #2D9B5A; /* Lighter green */
--gold: #C9A84C;         /* Gold accent */
--dark: #0D1B14;         /* Dark background */
```
