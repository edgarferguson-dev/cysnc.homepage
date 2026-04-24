CSync Solutions — Landing Page Deployment Package
====================================================

CONTENTS OF THIS FOLDER:
- index.html (the landing page, ready to deploy)
- img/ (create this subfolder — needs 4 PNGs, see below)

WHAT YOU NEED TO DO BEFORE DEPLOYING:

1. Create an "img" subfolder inside this folder (csync.homepage\img\)

2. Copy these 4 PNG files into the img\ subfolder.
   They live in my outputs folder — open them from the
   "View image" links I provided in chat, or grab them from:

   C:\Users\ewf83\AppData\Roaming\Claude\local-agent-mode-sessions\27d84987-3ebc-4b27-9026-abc38358185d\df88bc83-ab0b-48ad-a4af-a4f904eb33ee\local_bd1df544-5772-45d0-a45c-fd5fb1ab5383\outputs\csync-site\img\

   Files you need (keep the exact filenames):
     - bg_hero_business.png
     - bg_barber_shop.png
     - bg_hair_salon.png
     - bg_fitness_trainer.png

3. (Optional) Replace those 4 PNGs with real photos of Black
   business owners in Harlem/Brooklyn barber shops, hair salons,
   and training studios. Keep the exact same filenames so the
   HTML finds them — no code changes needed. Recommended:
   Unsplash search "Black barber shop NYC", "Brooklyn salon",
   "Harlem personal trainer". Save as 1600x900 or 1920x1080.

4. Deploy to Vercel:
     - Go to vercel.com → New Project → "Upload"
     - Drag this entire csync.homepage folder in
     - Vercel gives you a free *.vercel.app URL

5. Attach your GoHighLevel domain:
     - In Vercel: Project → Settings → Domains → Add
     - In GoHighLevel DNS:
         A     @     76.76.21.21
         CNAME www   cname.vercel-dns.com
     - Wait 5–30 min for DNS. Vercel auto-issues SSL.

KEY DETAILS:
- Business phone (shown on site): (929) 295-5738
- Email (shown on site): hello@csyncsolutions.com
- Booking widget: LeadConnector / HighLevel
  (https://api.leadconnectorhq.com/widget/booking/ZJq0xljfc03H3FJlr4R2)
- Brand palette: Navy #0A0F1E · Cyan #00E5FF

Questions? Open a new chat with Sonnet 4.6 and paste the
handoff prompt I provided.
