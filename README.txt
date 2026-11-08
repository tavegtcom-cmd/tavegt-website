TAVEGT LTD WEBSITE + PWA STARTER

FILES:
- index.html: complete responsive website
- manifest.webmanifest: installable PWA settings
- sw.js: basic offline cache
- icon.svg: app icon

BEFORE PUBLISHING:
1. Open index.html in a text editor.
2. Find: const TAVEGT_WHATSAPP = '91XXXXXXXXXX';
3. Replace 91XXXXXXXXXX with your WhatsApp Business number (country code 91 + 10 digits, no + or spaces).
4. Update the location/contact text in the footer if needed.
5. Add real products, photos, confirmed service prices, and official contact details before advertising.

GITHUB PAGES:
1. Open your tavegt-website repository on GitHub.
2. Upload all four files into the repository root (same folder as index.html).
3. Replace the old index.html when asked.
4. Commit changes to main.
5. In Settings > Pages, confirm deployment from main branch / root.

PWA INSTALL:
After GitHub Pages is live on HTTPS, open the website in Chrome on Android. Use browser menu > Install app or Add to Home screen (wording may vary).

IMPORTANT LIMITATIONS:
This is a front-end starter. Booking form stores requests only in the same browser's local storage and opens WhatsApp after the business number is configured. It does not sync to Google Sheets or between devices. Admin panel is a local demo, not a secure login. Live payments, real product orders, staff/partner accounts, secure admin, and cross-device database require a backend and payment integration. Do not publish customer private data in the demo Admin section.
