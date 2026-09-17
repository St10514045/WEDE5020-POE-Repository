**WEDE5020-POE-Repository**

***Sitemap***
<img width="2720" height="1440" alt="salon_website_sitemap" src="https://github.com/user-attachments/assets/9b6ba944-e4fd-4a45-b037-071b322307da" />

**Changelog:**
**PART 1**
- Created all five HTML pages (Home, About, Menu, Enquiry, Contact) with consistent navigation.
# Structure
- Built a 5-page website for **Hope Traditional Kitchen**: `index.html` (Home), `about.html`, `products.html` (Menu), `enquiry.html`, and `contact.html`.
- All pages share a consistent `<header>` with an `<h1>` site title and a `<nav>` menu linking to every page.
- Each page ends with a `<footer>` containing the copyright notice.
  
# Page Content
- **index.html:** Welcome section with a hero image, brief intro to the restaurant, and call-to-action links to the Menu, Contact, and Enquiry pages.
- **about.html:** Sections for Our History, Mission, Vision, and a "Meet Our Team" list with a team photo.
- **products.html:** Menu divided into Starters, Main Courses, and Sides, each item showing a name, description, price, and image. Includes a Dietary Information section.
- **enquiry.html:** A form with two `<fieldset>` groups (Your Details and Enquiry Details), including a dropdown for enquiry type and a message textarea.
- **contact.html:** Contact details, opening hours, two Google Maps `<iframe>` embeds for the Polokwane and Seshego branches, and a full contact form.

## HTML Elements Used
- Semantic tags: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
- Text elements: `<h1>`–`<h3>`, `<p>`, `<ul>`, `<li>`, `<strong>`.
- Forms: `<form>`, `<fieldset>`, `<legend>`, `<label>`, `<input>`, `<select>`, `<textarea>`.
- Media: `<img>` for food and team photos, `<iframe>` for Google Maps.
- All pages include `<!DOCTYPE html>`, `<meta charset="UTF-8">`, and the responsive `<meta name="viewport">` tag.
- Every page links to the shared external stylesheet: `css/style.css`.

**PART 2**
- Added a new team photo to the "Meet Our Team" section on the About page.
- Updated `css/style.css` to center the new image, limit its maximum width, and add rounded corners and a subtle shadow for a polished look.
- Created and linked an external stylesheet (`css/style.css`) to all pages.
- Applied base styles, custom typography, Flexbox/Grid layouts, and visual styling (colors, borders, shadows, hover effects).
- Implemented responsive design using media queries, relative units (rem, %), and responsive images.
