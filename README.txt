SUNRISE INTERIORS WEBSITE
=========================
Static website. No build step. Open index.html in a browser.

FILES
  index.html    Home page (products, our work, about, contact)
  privacy.html  Privacy policy
  terms.html    Terms and conditions
  styles.css    All styling. Brand colours are at the top (:root).
  assets/       logo.svg, logo.png and all product / work images (.jpg)

IMAGES
  Product images are in assets/ (plywood.jpg, doors.jpg, acp.jpg ...).
  To change one, replace the file keeping the same name.
  Best size: 800 x 600 px (4:3), JPG, under 200 KB each.
  Work photos: assets/work-soffit.jpg, assets/work-wallpaper-living.jpg.
  To add more, copy a <figure> block in the 'Our work' section of index.html.

EDIT CONTACT DETAILS
  Opening hours: 10:00 am to 7:30 pm (index.html, footer, contact).
  Phone +91 83989 87474, email sunriseinteriorsdelhi@gmail.com. Search for these in index.html,
  privacy.html and terms.html and change them.
  Add your full shop address in the Contact section of index.html
  and update the map link (search for 'maps?q=').

PUBLISH ON GITHUB PAGES
  1. Create a repository and upload all files, keeping the assets folder.
  2. Settings > Pages > deploy from the main branch, root folder.

The privacy and terms pages are general drafts. Please review them
and adjust to your actual policies.
