# INFR3120 Assignment 1 — Personal Portfolio

## Student details
- **Name:** REPLACE WITH YOUR FULL NAME
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

**Before submitting:** use Adobe Color (https://color.adobe.com/create) to create or confirm a scheme, then update this section with the actual scheme name/type you chose and the colours shown by Adobe Color. Do not claim an Adobe scheme was generated unless you actually did so.

## Contact form and validation
The contact form uses HTML attributes including `required`, `type="email"`, `type="tel"`, `pattern`, `minlength`, and `maxlength`. Browser validation is built in. The form is a front-end demonstration and does not deliver messages to an inbox until a backend or approved form service is connected.

## Semantic HTML and accessibility
Pages use semantic elements such as `header`, `nav`, `main`, `section`, `article`, `figure`, `footer`, `form`, `label`, and headings in logical order. Images have alternative text, form controls have labels, and keyboard focus is visible. Replace placeholder alternative text with an accurate description of your photo.

## Testing checklist
Complete these checks after adding your own information and publishing the site:
- [ ] Validate each HTML file with https://validator.w3.org/
- [ ] Validate each CSS file with https://jigsaw.w3.org/css-validator/
- [ ] Check links with https://validator.w3.org/checklink
- [ ] Run spelling/grammar checking and correct all issues
- [ ] Test the deployed website with https://wave.webaim.org/
- [ ] Test navigation, video playback, form validation, and layout at mobile/tablet/desktop widths
- [ ] Fix any errors and re-run the checks

Record the date and any remaining warnings here:
- HTML validation:
- CSS validation:
- Link checker:
- Spell check:
- WAVE accessibility:

## GitHub version control and deployment
1. Create a **public** GitHub repository for this assignment.
2. Upload the project files, keeping the folder structure shown above.
3. Commit changes in stages with meaningful messages, for example:
   - `Create four portfolio pages`
   - `Add responsive CSS layouts`
   - `Add profile image and introduction video`
   - `Add contact form validation`
   - `Complete README and testing fixes`
4. In repository **Settings → Pages**, choose the `main` branch and `/ (root)` folder, then save.
5. Wait for GitHub Pages to publish. Copy the live URL and repository URL into your course submission.
6. Zip the project folder and submit the ZIP on Canvas.

- **GitHub repository URL:** ADD YOUR REPOSITORY URL
- **Live GitHub Pages URL:** ADD YOUR LIVE WEBSITE URL

## External code and attribution
This starter was written for this assignment using standard HTML and CSS patterns. If you add any code from websites, tutorials, or other sources, cite the source and author in this README, explain the code in comments, and follow the assignment's external-code limit. Course lecture code may be used as allowed by the assignment instructions.
# assignment-1
# assignment-1
