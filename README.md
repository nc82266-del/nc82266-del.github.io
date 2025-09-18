Brotherhood — Static Website Kit
================================

What you have:
- A ready-to-deploy static website in this ZIP.
- Files: index.html, products.html, product.html, about.html, contact.html
  css/styles.css, js/main.js, products.json, images/*.svg
- The buy button uses a demo mailto flow so you can receive order details and manually fulfill via your POD provider.

How to deploy (easy options):
1) Netlify (recommended for students)
   - Create a free Netlify account.
   - Drag & drop the unzipped folder into Sites > New site from drag & drop.
   - Netlify will publish your site and give a URL. Replace the demo email in js/main.js ('your-email@example.com') with your store email.

2) GitHub Pages (free)
   - Create a GitHub repository and upload these files.
   - In repo settings -> Pages -> select branch 'main' and root folder -> Save.
   - Your site will be published at username.github.io/repo-name

3) Vercel (also easy — sign up and import the repository)

How to edit files on iPad (if you only have an iPad):
- Use the Files app to save the ZIP to iCloud Drive or "On My iPad".
- Use the Textastic app, Working Copy (for git), or the GitHub app to upload files.
- For Netlify, open Safari, go to Netlify app or Netlify web dashboard and use drag & drop from the Files app (Safari supports file selection).

Next steps to make it a full store:
- Create accounts: Shopify (+Printful), Printful (or Printify), and payment gateway (Razorpay/Stripe).
- Replace mailto order flow with a real cart:
  - Option A: Use Shopify + Printful (easiest, automated fulfillment).
  - Option B: Integrate Snipcart or Stripe Checkout on this static site (requires Stripe keys).
- Add real product photos (order physical samples), update products.json with real image URLs.
- Replace the Formspree placeholder with your form endpoint or Mailchimp for email capture.
- Add analytics: Google Analytics & Meta Pixel.

If you want, I can:
- Convert this static template into a Shopify theme (Liquid) ready to import.
- Integrate with Printful API for automatic order forwarding (requires your API keys).
- Create social graphics & 30-day content calendar.
- Help you with domain setup and small ad creatives.

Enjoy — launch fast, iterate often! — ChatGPT
