DHARMIKA WEBSITE — SETUP & EDITING GUIDE
==========================================

FILES
-----
1. dharmika-website-prototype.html — main responsive website, including embedded logo artwork and styling.
2. dharmika-customer-dashboard-demo.html — sample customer-area dashboard concept. It is NOT a secure login or live customer account.

HOW TO PREVIEW
--------------
1. Download both HTML files to your computer.
2. Double-click dharmika-website-prototype.html. It opens in Chrome, Edge or Firefox.
3. Internet is required for Google Fonts and the remote Unsplash demo photographs.
4. The official Dharmika logo from page 2 of your presentation is embedded in the main HTML.

BRAND DIRECTION USED
--------------------
Foundation Charcoal #111A22
Signal Gold #FFC72C
Pure White #FFFFFF
Concrete #E9EAEC
Steel #5B6670

The supplied presentation describes the D + building + road/land symbol and the “DHARMIKA / NAME OF TRUST” lock-up. Gold is used as a restrained accent. The site uses Manrope / DM Sans for interface text and Playfair Display for selected editorial emphasis.

WHAT IS WORKING IN THIS PROTOTYPE
---------------------------------
- Responsive desktop and mobile layout
- Navigation and mobile menu
- Property category filters
- Property type / region quick filter
- Scroll reveal motion and subtle image zoom
- FAQ accordion
- Enquiry form validation and mailto handoff
- WhatsApp placeholder button
- Customer dashboard visual concept
- Social links placeholders

IMPORTANT: WHAT IS NOT LIVE YET
-------------------------------
This is a front-end prototype, not a complete production property platform.
- The property cards are illustrative and use stock photographs, not confirmed Dharmika projects.
- No real inventory, prices, maps, availability or legal approvals are connected.
- The enquiry form opens the visitor's email application. It does not save leads to a database or CRM.
- WhatsApp, social links, company email and phone are placeholders.
- The customer dashboard is a visual demo only. It has no authentication, private customer data, document storage or live project tracking.
- Testimonials are placeholder copy and must be replaced by genuine, consented customer reviews.
- No claims such as RERA registration, years of experience, completed project counts, guarantees or awards should be published unless Dharmika verifies them.

HOW TO EDIT MANUALLY
--------------------
1. Right-click the HTML file and choose Open with > Notepad (or use Visual Studio Code).
2. Use Ctrl+F to find the text you want to change.
3. Edit visible text between HTML tags. Example: search for “Build your future on” to change the hero headline.
4. Replace image URLs inside src="https://images.unsplash.com/..." with approved Dharmika project image URLs.
5. Replace COMPANY_EMAIL and WHATSAPP_NUMBER near the bottom of the main HTML:
   COMPANY_EMAIL="official-email@yourdomain.com"
   WHATSAPP_NUMBER="91XXXXXXXXXX" (country code + 10-digit number, digits only)
6. Replace the Instagram / Facebook / LinkedIn / YouTube placeholder links with official profile URLs.
7. Save the file and refresh the browser.
8. Keep a backup before making major edits. Do not delete closing </div>, </section>, </script> or </body> tags.

CHANGE COLOURS
-------------
At the top of the <style> section, find :root.
Edit these CSS variables:
--ink:#111A22;
--gold:#FFC72C;
--white:#fff;
--concrete:#E9EAEC;
--steel:#5B6670;

HOSTING OPTIONS
---------------
EASIEST: NETLIFY (static hosting)
1. Create a Netlify account.
2. Put the main HTML file in a folder on your computer and rename it to index.html.
3. Open Netlify and use its manual deploy / drag-and-drop deployment area.
4. Drag the folder containing index.html into the deploy area.
5. Netlify gives you a temporary public website address.
6. Add your own domain in Site settings > Domain management and follow the DNS instructions from your domain registrar.
7. Re-upload the folder whenever you update the static HTML.

ALTERNATIVE: GITHUB PAGES
1. Create a GitHub account and a new repository.
2. Upload the website file renamed to index.html.
3. Open repository Settings > Pages.
4. Select deployment from the main branch / root folder and save.
5. GitHub Pages publishes a public URL. A custom domain can be connected later.

CUSTOM DOMAIN
-------------
Buy a domain from a reputable registrar (for example, a .com or .in domain). Choose a short domain that Dharmika owns and can renew. Connect it through the hosting provider's domain instructions. Use HTTPS/SSL and enable automatic renewal.

BEFORE PUBLIC LAUNCH — REQUIRED COMPANY INPUT
---------------------------------------------
- Official registered company name and legal address
- Official phone, WhatsApp, email and social media links
- Approved logo files (SVG / transparent PNG) and favicon
- Real project names, exact addresses, maps and project status
- Actual photographs and permission to publish them
- Property types, plot sizes, unit plans, specifications and verified prices
- Ownership/title and approval information to display, plus applicable RERA registration details
- Genuine testimonials with written customer consent
- Privacy policy, terms, cookie notice if applicable, and lead-consent wording
- A person/team responsible for responding to enquiries

CUSTOMER LOGIN / LEAD MANAGEMENT — NEXT DEVELOPMENT PHASE
---------------------------------------------------------
For a real customer portal, use a backend (for example Supabase or Firebase) with secure authentication, role-based permissions, database records and private file storage. Each customer must only see their own enquiries, receipts, agreements and project updates. Add admin access for authorised Dharmika staff, audit logs, backups and a privacy policy. Never store passwords, identity documents or customer financial information in a plain HTML file.

RECOMMENDED LAUNCH PATH
-----------------------
Phase 1: Approve content, projects, photos, contact details and legal text.
Phase 2: Publish the static marketing website on Netlify with a custom domain.
Phase 3: Connect a real enquiry form to a CRM or secure backend and test every lead.
Phase 4: Build secure customer login, admin dashboard, project progress and document access.
Phase 5: Test mobile usability, accessibility, page speed, SEO, analytics, backups and security.

DESIGN REFERENCES STUDIED
-------------------------
- SOBHA Showcase — structured property discovery and trust / brand storytelling:
  https://www.sobha.com/showcase/
- Aura Estates case study — property filters, rich project pages and enquiry flows:
  https://www.novilance.com/portfolio/aura-estates
- ERA case study — immersive motion and location storytelling:
  https://videinfra.com/work/era
- Award-winning real estate site patterns:
  https://uidiscovery.com/websites/award-winning-real-estate

The Dharmika prototype borrows general UX principles (clear property discovery, strong image-led storytelling, restrained motion and clear enquiry paths), not their brand assets or exact layouts.
