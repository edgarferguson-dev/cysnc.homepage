# Sonnet 4.6 Handoff Prompt

Copy everything below the line into a fresh Sonnet 4.6 chat.
Attach `index.html` from this folder so the new chat has the
current state of the site.

---

I'm Edgar Ferguson, founder of **CSync Solutions** — I install AI
voicebots + appointment automation for service businesses. I already
have a landing page built (attaching `index.html`) and I want your
help taking it the rest of the way to a live, polished site on my
custom domain.

## Business context
- Service: 24/7 AI voice bot that answers calls, qualifies leads,
  books appointments, and sends follow-ups so operators stop losing
  revenue to voicemail.
- Three target niches: **barbers, hair stylists, and personal
  trainers** — specifically Black business owners in **Harlem and
  Brooklyn, NYC**. Representation in imagery matters.
- Booking widget: LeadConnector / HighLevel
  `https://api.leadconnectorhq.com/widget/booking/ZJq0xljfc03H3FJlr4R2`
- Business phone (AI virtual assistant picks up this line — this is
  the one clients should see): **(929) 295-5738**
- Email: **hello@csyncsolutions.com**
- Location tagline: Brooklyn, NY
- Brand palette: Navy `#0A0F1E`, Cyan `#00E5FF`, dark card
  `#111827`, border `#1E2A3A`. Font: Inter.

## Current state of the page (attached)
- Single-file `index.html` — nav, hero, niches bar, problem,
  how-it-works, who-it's-for, results/case study, CTA, footer.
- References 4 images from a local `img/` folder:
    - `img/bg_hero_business.png` (1920×1080) — hero background
    - `img/bg_barber_shop.png` (1600×900) — niche card + case study
    - `img/bg_hair_salon.png` (1600×900) — niche card
    - `img/bg_fitness_trainer.png` (1600×900) — niche card
- Those 4 PNGs are currently procedurally generated placeholders
  (brick texture + warm street-lamp glow + industry silhouettes like
  a barber pole/chair, scissors, dumbbell). They carry the brand
  colors but they are NOT photos of real people.

## What I want your help with (in priority order)

1. **Replace the 4 placeholder PNGs with real, licensed photos**
   that represent Black barbers, hair stylists, and personal
   trainers in NYC shops. Unsplash and Pexels are fine (free +
   commercial-use). Keep the exact same filenames so no HTML
   changes are needed.
2. **Deploy to Vercel** and attach my GoHighLevel-purchased domain:
   - DNS at GHL: `A @ 76.76.21.21` and `CNAME www cname.vercel-dns.com`
   - Walk me through the Vercel upload + domain-add flow.
3. **Polish pass on the HTML itself** — catch anything clunky:
     - Hero copy could be sharper.
     - Any responsive-layout issues on iPhone widths.
     - Make sure the LeadConnector booking link works as both a
       redirect AND (ideally) an embedded widget modal.
4. **Add a thin "Contact" or "Services" page** if it improves
   conversion — optional.
5. **SEO / meta**: add Open Graph tags, favicon, structured data
   for LocalBusiness schema. Title/description already present.

## What I do NOT want
- No CMS, no React, no build step. Keep it static, drag-and-drop
  deployable.
- Don't change my brand colors or remove the cyan accent.
- Don't change the booking URL or phone number.

## Your first move
Ask me anything unclear, then propose a plan. If you're ready to
start, begin with task #1 — source 4 real representative photos
(drop in the links + confirm licensing), and give me a `.zip` I
can unpack into the `img/` folder.
