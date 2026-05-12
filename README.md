# DJ NAVA — Official Site

Single-file site for **DJ NAVA**. Telugu · Tamil · Bollywood · Punjabi · Hip-Hop / Top 40 · Originals.

## Deploy
- Drag this folder onto https://vercel.com/new, OR
- Push to GitHub and import the repo (Framework: Other, build/output empty)

## Contact email
All booking + review form submissions go to **Navaspinz@gmail.com**.
Search `Navaspinz@gmail.com` in `index.html` to change it (3 spots).

## Want a real backend instead of mailto?
1. https://web3forms.com → enter your email → copy access_key
2. In each `<form>`: change `action="mailto:..."` to `action="https://api.web3forms.com/submit"`,
   delete `data-mailto`, add `<input type="hidden" name="access_key" value="YOUR_KEY">`

## Features
- Visible SoundCloud music dock (Robo Baile) — auto-collapses on phones
- Letter-by-letter logo reveal, hero parallax, scroll progress bar
- Stat count-up, 3D mouse-tilt cards, cursor glow (desktop), magnetic buttons
- Marquee genre ticker (resized on mobile)
- Animated hamburger ↔ X menu with outside-click close
- 44×44 touch targets, iOS no-zoom inputs, full-bleed mobile sections
- Booking + star-rated review forms (mailto-based)
