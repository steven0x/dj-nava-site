# DJ NAVA — Official Site

Single-file site for **DJ NAVA** — multi-cultural DJ, producer & instructor.
Telugu · Tamil · Bollywood · Punjabi · Hip-Hop / Top 40 · Originals.

## Deploy to Vercel

Zero config. Either:
- Drag this folder onto https://vercel.com/new (no git needed), or
- Push to GitHub and import the repo. Framework: Other. Build/output: empty.

## Contact email

All booking + review form submissions go to **Navaspinz@gmail.com**.
Change this by searching for `Navaspinz@gmail.com` in `index.html` (3 spots).

## Want a real backend instead of mailto?

When you're ready, swap mailto → Web3Forms:
1. https://web3forms.com → enter your email → copy access_key
2. In `index.html`, find each `<form>` tag and:
   - Change `action="mailto:..."` to `action="https://api.web3forms.com/submit"`
   - Delete the `data-mailto` attribute
   - Add `<input type="hidden" name="access_key" value="YOUR_KEY">` inside the form

## Features
- Visible SoundCloud music dock (Robo Baile, autoplay where allowed)
- Letter-by-letter logo reveal, hero parallax, scroll progress bar
- Animated stat count-up, 3D mouse-tilt cards, cursor glow
- Magnetic CTA buttons, marquee genre ticker
- Booking + star-rated review forms (mailto, working out of the box)
