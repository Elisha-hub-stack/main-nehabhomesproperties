NEHAB HOMES & PROPERTIES LTD. — WEBSITE STARTER
================================================

This is a complete static, multi-page website built with HTML, CSS and vanilla JavaScript.
It does not require React, Django, a database, npm or a build process.

1. EXTRACT
----------
Extract the ZIP file. Open the extracted "nehab-homes-properties" folder in VS Code.

2. RUN LOCALLY
--------------
Recommended: install the "Live Server" extension in VS Code.
Right-click index.html and choose "Open with Live Server".
You can also double-click index.html, but Live Server gives a better development experience.

3. IMPORTANT COMPANY DETAILS TO CHECK
-------------------------------------
The website currently uses:
- Company: Nehab Homes & Properties Ltd.
- Address: 1 Close, Opp. NNPC Megastation, Ogwashi-Uku, Delta State.
- Phone / WhatsApp: +2348038621411
- Email: nehabhomes@gmail.com

Please confirm the email address with the company before publishing.

4. REPLACE PLACEHOLDER PHOTOS
-----------------------------
The sample listing photos use remote Unsplash image URLs for demonstration only.
They are not Nehab's actual properties and must not be presented as confirmed company listings.
Before launch:
- Replace the sample listings in js/properties.js with verified company property/land details.
- Add the company's real photos to assets/images/properties/ and assets/images/lands/.
- Change each listing's image paths in js/properties.js to the local image paths.
- Replace the hero image in index.html with a company-approved photo.
- Add the real company logo as assets/images/logo.png (or .jpg), then update the logo markup
  in js/main.js. The current header uses a text logo placeholder.

5. EDIT PROPERTY / LAND LISTINGS
--------------------------------
Open js/properties.js.
- Add or edit objects in the properties array for houses/buildings.
- Add or edit objects in the lands array for land listings.
- Keep each listing slug unique and descriptive.
- Use status values such as "Available", "Under Offer", or "Sold".
- Set verified: true only after the company confirms the listing details.
The cards and detail pages are generated automatically from this data.

6. WHATSAPP ENQUIRIES
---------------------
The website uses +2348038621411. Update WHATSAPP_NUMBER in js/main.js if needed.
The number must be digits only, including country code, without + or spaces.
All enquiry links open WhatsApp with a prefilled message.

7. CONTACT FORM LIMITATION
--------------------------
This is a front-end-only website. The contact form opens WhatsApp with the visitor's message.
It does not store submissions in a database or send email automatically.
For a stored enquiry system or email delivery, a backend or a trusted form service is required.

8. PUBLISHING
-------------
Upload the contents of this folder (not the ZIP itself) to your hosting account's public_html
folder or the hosting provider's website root. Keep the folder structure unchanged.
Connect the domain to the hosting account and enable SSL/HTTPS in the hosting dashboard.

9. BEFORE GO-LIVE CHECKLIST
---------------------------
[ ] Confirm company email, phone and address.
[ ] Replace every sample listing with real, authorised listing information.
[ ] Replace sample photos with company-approved photos.
[ ] Add the real logo.
[ ] Check every WhatsApp link on a phone.
[ ] Test all pages on mobile and desktop.
[ ] Check domain, SSL and hosting.
[ ] Add privacy/legal wording if the company collects personal information.

UPDATED BRAND AND INVESTMENT PAGE
---------------------------------
The supplied logo is integrated at assets/images/nehab-logo.png.
The supplied Buy2Sell flyer is integrated at assets/images/buy2sell-investment-plan.jpg.
A dedicated investment.html page and navigation link have been added.
The figures are transcribed from the flyer and should be confirmed against the signed contract.

VIDEO NOTE
----------
A land-listing video was mentioned, but no video file was attached with the two images in this update. It can be added to assets/videos/ when supplied.

YOUTUBE PROPERTY/LAND VIDEOS
----------------------------
The eight client-supplied videos are connected to the land listings in the supplied order:
1. Aihuobabekun, Benin City (landscape video)
2. Evboneka, Edo State (landscape video)
3-8. Iyowa, Benin City (YouTube Shorts)
The homepage hero uses video 1. Shorts are shown in their native portrait ratio and
landscape videos in 16:9. The embeds use youtube-nocookie.com and load lazily on listing pages.
Confirm each listing's exact plot size, price, availability and title documents before launch.

Recent design updates:
- The supplied official logo is preserved as assets/images/nehab-logo-original.jpg, with a transparent gold version at assets/images/nehab-logo.png for site placement.
- The site-wide service coverage is South-South, South-West and South-East Nigeria. The listed office address remains a physical contact address.
- The home page Land Opportunities feature includes the supplied Evboneka YouTube video.
- The navigation shell remains fixed at the top while scrolling.
