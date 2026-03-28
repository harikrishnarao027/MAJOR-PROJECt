Amazon Demo UI Clone

A simple front-end Amazon-style shopping UI built using HTML and CSS. This project showcases a product browsing interface with multiple sections, product pages, and basic navigation.

📌 Project Overview

This is a static e-commerce UI inspired by Amazon.
It demonstrates:

Product listing pages
Individual product views
Navigation between sections
Image carousel (banner)
Basic UI styling

⚠️ Note: This is a frontend-only demo (no backend, no real payments).

🚀 Features

✅ Clean UI layout inspired by Amazon
✅ Product showcase with images and pricing
✅ Multiple product sections
✅ Navigation using buttons
✅ Carousel banner for promotions
✅ Responsive layout using Flexbox & Bootstrap classes

🗂️ Project Structure
📁 project-folder
│── amazone demo.html   # Main HTML file
│── amazone demo.css    # Styling file
🖥️ Pages / Sections

The project includes multiple sections:

🏠 Home section
👕 Clothing products (hoodies, t-shirts)
📱 Electronics (placeholder)
📦 Individual product detail pages

Each product page includes:

Product image
Title
Description
Price
"Buy Now" button
"Go Back" navigation
🎯 Key Components Explained
1. 🔄 Carousel Banner
Uses Bootstrap carousel
Displays promotional images
Auto sliding banners
2. 🛍️ Product Display

Each product section contains:

Product image (<img>)
Title (<h1>)
Description (<p>)
Price button

Example:

<h1>LEOTUDE Men's</h1>
<p>Cottonblend Oversized T-shirt</p>
<button class="btn btn-primary">Buy now ₹268</button>
3. 🔁 Navigation System

Navigation is handled using:

onclick="display('sectionHome')"

This uses an external UI script:

ccbp-ui-kit.js

It dynamically switches between sections.

4. 🎨 Styling
Custom CSS file (amazone demo.css)
Bootstrap utility classes:
d-flex
justify-content-center
btn
Layout built using Flexbox
5. 📢 Footer Section

Includes:

Address (placeholder)
Contact info (placeholder)
Timings
Scrolling message using <marquee>
⚙️ Technologies Used
HTML5
CSS3
Bootstrap (via classes)
JavaScript (UI Kit for navigation)
▶️ How to Run
Download or clone the repository
Open the HTML file:
amazone demo.html
Run in any browser 🌐
📸 Screenshots (Suggested)

You can add screenshots like:

Home page
Product page
Carousel banner
🔧 Improvements You Can Add

🚀 Add real JavaScript for cart functionality
🚀 Connect backend (Node.js / Firebase)
🚀 Add login/signup system
🚀 Make fully responsive (mobile-first)
🚀 Replace <marquee> (deprecated) with modern animation

⚠️ Limitations
No backend integration
Static product data
No real checkout system
Uses deprecated <marquee> tag
🙌 Credits
Product images from Amazon CDN
UI inspiration: Amazon
📬 Contact
Address: updating soon
Contact: updating soon
Timings: 10:00 AM – 10:00 PM (Mon–Sat)
