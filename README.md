# INFR3120 Assignment 1 — Personal Portfolio

## Student details
- **Name:** Tayyab Farooq 100920589
- **Course:** INFR3120 – Web and Scripting Programming
- **Assignment:** Portfolio Site using HTML5 and CSS3

## Website pages
This portfolio uses four separate HTML files, rather than a single-page application:
- `index.html` — Home page and navigation
- `about.html` — Short biography, personal photo, and introductory video
- `projects.html` — Five project summaries
- `contact.html` — Contact form with browser-side validation

## File structure
```text
portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── README.md
├── css/
│   ├── style.css
│   ├── mobile.css
│   ├── tablet.css
│   └── laptop.css
└── assets/
    ├── profile-placeholder.svg
    ├── video-poster.svg
    └── your-introduction-video.mp4  (add your own video)
```

## Responsive design and viewport sizes
The shared rules are in `css/style.css`. The site links separate viewport stylesheets on every page:
- **Mobile:** `max-width: 600px`, in `css/mobile.css`. Cards and content stack vertically for narrow screens and navigation spacing is reduced.
- **Tablet:** `601px–1024px`, in `css/tablet.css`. Cards use two columns and content gutters are adjusted for medium-width screens.
- **Laptop/desktop:** `min-width: 1025px`, in `css/laptop.css`. Cards use three columns and content has wider margins for larger displays.

Fluid widths (`width: 100%`, percentage widths, and `max-width`) help content adapt to the available viewport. **Flexbox is not used.** Layout uses normal document flow, inline-block, and media queries.

## Gradients
- A standard linear gradient is used on the home page hero in `css/style.css` under `.hero`: `linear-gradient(120deg, #132238 0%, #245b8f 58%, #2b8c88 100%)`.
- An angled linear gradient is used on the page heading in `css/style.css` under `.page-heading`: `linear-gradient(35deg, #e7f0f3, #ffffff 65%, #d5efea)`.
- The video poster placeholder also uses a gradient in `assets/video-poster.svg`.

## Colour scheme
The palette is a cool, professional blue/teal scheme:
- Navy `#132238` — header, footer, main headings
- Blue `#245b8f` — links and gradient
- Teal `#2b8c88` — buttons and accents
- Cream `#f6f4ef` — page background
- White `#ffffff` — cards and form backgrounds
- Ink `#263342` — body text

## Contact form and validation
The contact form uses HTML attributes including `required`, `type="email"`, `type="tel"`, `pattern`, `minlength`, and `maxlength`. Browser validation is built in. The form is a front-end demonstration and does not deliver messages to an inbox until a backend or approved form service is connected.

## Semantic HTML and accessibility
Pages use semantic elements such as `header`, `nav`, `main`, `section`, `article`, `figure`, `footer`, `form`, `label`, and headings in logical order. Images have alternative text, form controls have labels, and keyboard focus is visible. Replace placeholder alternative text with an accurate description of your photo.


