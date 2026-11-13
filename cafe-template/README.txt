CAFE WEBSITE TEMPLATE - HOW TO USE
==================================

1. PREVIEW
   Double-click index.html. It opens in your browser (needs internet for fonts and map).

2. CUSTOMIZE FOR A CAFE
   Open index.html in any text editor (VS Code, Notepad++, Notepad).
   Scroll to the bottom and find the block marked:
       EDIT ONLY THIS BLOCK for each new cafe
   Change: name, tagline, menu and prices, specials, reviews, opening hours,
   address, phone, WhatsApp number, email, social links.

   WhatsApp number format: country code + number, no plus or spaces.
   Example: 919876543210

3. COLOURS
   At the top of the file, change the colours inside ":root { ... }"
   (--bg, --surface, --ink, --muted, --accent, --warm).

4. PHOTOS
   Put photos inside the "images" folder and set paths in the config,
   for example:  image: "images/hero.jpg"
   Leave "" to show a placeholder. Compress photos first (squoosh.app),
   ideally under 300 KB each.

5. PUBLISH (free)
   Drag the whole folder onto app.netlify.com/drop, or use Cloudflare Pages.
   Then connect the cafe's own domain.

6. BEFORE GOING LIVE - CHECK
   - Every sample name, phone number and WhatsApp number is replaced.
   - Every menu item, price and review is the cafe's real information.
   - Only use photos the cafe gave you or you took yourself.
   - Test the reservation form and the WhatsApp button on your phone.

Tip: keep this original folder untouched and work in a copy for each client.
