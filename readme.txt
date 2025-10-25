Aurora Studio — Responsive Landing Site

Project Description:
Aurora Studio is a fictional creative agency. This project is a fully responsive, multi-page landing website
built using HTML5 and CSS3 only (no JavaScript). It demonstrates semantic markup, accessible forms,
responsive design using Flexbox, CSS-only mobile navigation, and visually appealing layouts.

Project Structure:

project-name/
│
├─ index.html        --> Home page with hero section, services, and image gallery
├─ about.html        --> About page with company info, team, and packages table
├─ contact.html      --> Contact page with form, office info, and map placeholder
├─ css/
│   └─ style.css     --> Main stylesheet
├─ images/           --> All images used (work1.jpeg, work2.jpeg, work3.jpg, map.jpg)

How to Open the Site:

1. Download or unzip the project folder.
2. Open index.html in a web browser.
3. Use the site navigation to visit the About and Contact pages.
4. On clicking menu you can visit all pages
No server is required — all pages are static.

Features & Techniques:

HTML & Accessibility:
- Semantic HTML5 elements: header, nav, main, section, footer.
- Logical heading structure (h1 → h2 → h3).
- All images include descriptive alt attributes.
- Contact form on contact.html with Name, Email, Subject (select), Message (textarea), and Submit button.
- About page contains a table for “Our Packages” with features and pricing.
- Lists used for team members (ul > li).

CSS & Responsiveness:
- External stylesheet: css/style.css.
- Mobile-first design with three suggested breakpoints (mobile ≤600px, tablet 601–1024px, desktop ≥1025px).
- Flexbox used for layout of services section (.service cards).
- CSS variables used for colors, spacing, and typography.
- Hero section with heading, subheading, and CTA button.
- Responsive navigation menu using CSS-only checkbox hack (input[type="checkbox"] + label + ul).
- Image gallery on home page with CSS-only layout and hover scale/shadow effects.
- Buttons and form inputs include hover/focus transitions.
- Print-friendly rules included.

Visual Design & Effects:
-menu have alee three section about , contact and hone with the help of toogle
- Hero section with gradient background.
- Services and gallery items have hover effects (scale and shadow).
- Forms highlight on focus for better usability.
- Rounded cards and consistent shadows for modern look.

Known Issues:
- Contact form does not submit (action="#" placeholder).
- Map on contact page is a static placeholder image.
- Gallery lightbox or modal not implemented (CSS-only enhancement possible).

Special CSS-Only Techniques:
- Mobile navigation menu: Checkbox hack with hidden input and label.
- Gallery hover effect: Scale and shadow applied using :hover.
- Services cards hover: TranslateY and shadow on hover.
- Responsive layout: Flexbox for services, percentage widths for gallery.

Credits:
- Images: Placeholder images in images/ folder (use Unsplash or similar sources).
- Fonts: Google Fonts — Poppins.

Aurora Studio — Fully responsive, semantic, and visually polished landing site.
