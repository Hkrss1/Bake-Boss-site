🍰 Bake Boss - The Ultimate Bakery

Bake Boss is a modern, elegant, and fully responsive bakery website built using HTML, Tailwind CSS, and JavaScript.
It showcases the bakery’s menu, locations, and customer engagement features in a clean, minimal, and mobile-friendly design.

🚀 Features
🧁 Hero Section

Visually appealing header with logo and navigation links.

Tagline and action buttons to view catalog or find store locations.

Smooth color scheme with a modern bakery aesthetic.

🍰 Product Catalog

Four major product categories:

Cakes & Treat Slices

Desserts & Sweets

Savory Meals & Wraps

Quick Bites & Drinks

Each product card includes:

High-quality image

Short description with price range

Call-to-action button

📍 Multi-Location Section

Dynamically displays multiple store locations using JavaScript.

Each location card includes:

Bakery name and address

Buttons to get directions (Google Maps link)

Leave a Review (Google Place ID link)

📞 Contact & Footer

Contact details with clickable phone and email links.

Auto-updated copyright.

Quick links for Catalog, Privacy Policy, and Terms of Service.

🧩 Tech Stack
Technology	Purpose
HTML5	Structure and layout
Tailwind CSS	Styling and responsiveness
JavaScript (Vanilla)	Dynamic content rendering
Lucide Icons	Lightweight SVG icon library
Google Fonts (Inter)	Modern typography
Favicon Support	Custom bakery logo as page icon
⚙️ Setup Instructions

Follow these simple steps to run the project locally:

1️⃣ Clone the Repository
git clone https://github.com/yourusername/bake-boss.git
cd bake-boss

2️⃣ Open in Browser

Simply open the file:

index.html


You can double-click or drag it into your browser.

3️⃣ (Optional) Serve Locally

To test on localhost, use a simple live server:

# Using VS Code extension or Node
npx live-server


Then visit: http://localhost:8080

🗺️ Add or Edit Store Locations

You can update the bakery locations in the JavaScript section inside index.html:

const locations = [
  {
    name: "Bento Cakery",
    address: "NH22 Mall, Pinjore, Panchkula",
    mapUrl: "https://maps.app.goo.gl/68nXYV1pwvvWtpnn6",
    reviewPlaceId: "ChIJcwMzn9aTDzkRadpOfO6ha0U"
  },
  // Add more locations here
];


💡 To get your reviewPlaceId, search your business on Google Maps and extract it from the “Write a Review” link.

🎨 Customization

You can easily customize:

Colors – via CSS variables in the <style> section:

:root {
  --color-primary: #793D2A;
  --color-secondary: #F8F4E5;
  --color-accent: #E55039;
}


Images – replace with your own .png or .jpg files.

Text content – edit headings, descriptions, or pricing inside the catalog section.

📷 Assets

Please ensure these image files are available in your project folder:

Bake boss logo.png
Cakes & Treat Slices.png
Desserts & Sweets.png
Savory Meals & Wraps.png
Quick Bites & Drinks.png
Extracted pages from Bake Boss Logo_page-0001 (1).jpg

👨‍💻 Developer Info

Author: Ankit Raj
Brand: Bake Boss
Email: bake.boss@bentocakery.com

Phone: +91 86999-61616

📜 License

This project is for educational and demonstration purposes.
All branding, images, and logos are © Bake Boss and cannot be reused without permission.