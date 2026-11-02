Keitu's Cake and Bakery Website

Student: ST10520902 - 

Module: WEDE5020 - POE Part 2

Location: Kagiso, Gauteng



Project Overview

This website is for Keitu's Cake and Bakery. It showcases custom cakes and allows customers to place orders via enquiry form. This README documents Part 2 - CSS styling and responsive design.



2.1 External Stylesheet

\- Created `css/style.css` and linked to ALL pages

\- Link: `<link rel="stylesheet" href="css/style.css" />`



2.2 Base Style

\- Reset: `\* { margin:0; padding:0; box-sizing:border-box; }`

\- Body: font-family Arial, font-size 1rem, color #333, bg #, padding 2%

\- Background Image: `url('../images/bakery-bg.jpeg')` cover center fixed



2.3 Typography

\- h1 2.5rem 700 weight, h2 2rem, h3 1.5rem, line-height 1.6, letter-spacing 0.05em



2.4 Layout

\- Flexbox header: `display:flex; justify-content:space-between; align-items:center;`

\- Grid gallery: `grid-template-columns: repeat(3, 1fr); gap:2rem;`



2.5 Visual Styles

\- border-radius, box-shadow, hover `nav a:hover`, `button:hover`, `input:focus`



3.1 Breakpoints

\- Tablet 768px: 2-column gallery

\- Mobile 480px: 1-column gallery, font 0.9rem



3.2 Relative Units

\- Used rem and % not px



3.3 Responsive Images

\- width:100% scaling, srcset planned



Changelog

Part 1 Fixes: Added alt text, fixed nav link, added meta description, added viewport meta

Part 2:

\- 2026-05-10: Created http://style.css linked all pages

\- 2026-05-10: Added background image

\- 2026-05-11: Added Flexbox/Grid and hover effects

\- 2026-05-11: Added media queries 768px \& 480px

\- 2026-05-11: Created README and screenshots



Responsive Testing Screenshots

Tested with Chrome DevTools F12 > Device Toolbar

\- Desktop 1920x1080, Tablet iPad Air, Mobile iPhone SE

\- Saved in screenshots/desktop.png, http://tablet.png, http://mobile.png



!\[Desktop](screenshots/desktop.png)

!\[Tablet](screenshots/tablet.png)

!\[Mobile](screenshots/mobile.png)



File Structure



keitu\_site/

├── index.html

├── css/style.css

├── images/bakery-bg.jpeg

├── screenshots/

└── README.md



References

\- W3Schools Flexbox https://www.w3schools.com/css/css3\_flexbox.asp

\- W3Schools Grid https://www.w3schools.com/css/css3\_grid.asp

\- MDN Media Queries https://developer.mozilla.org/en-US/docs/Web/CSS/Media\_Queries



GitHub

\- Repo: Add your link after push

\- Commit: `git commit -m "Part 2: responsive CSS and README"`



