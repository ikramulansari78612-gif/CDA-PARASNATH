# CDA Parasnath Website

A responsive, static HTML/CSS/JavaScript website prepared for GitHub Pages.

## Files
- `index.html` — page content, SEO metadata, sections and forms
- `style.css` — responsive design and accessibility styling
- `script.js` — mobile menu, student directory, practice quiz, WhatsApp enquiry/review forms
- `images/logo.svg` — original academy-inspired emblem and favicon
- `images/` — add academy-approved photographs here

## Deploy on GitHub Pages (mobile-friendly)
1. Open the repository: https://github.com/ikramulansari78612-gif/CDA-parasnath/
2. Open the repository's file list.
3. Upload/replace `index.html`, `style.css`, and `script.js` at the repository root. Upload the `images` folder and its contents too.
4. Commit the changes to the branch configured for GitHub Pages (usually `main`).
5. In GitHub, open **Settings → Pages** and confirm the publishing source/branch and root folder.
6. Wait for the Pages build to finish, then open: https://ikramulansari78612-gif.github.io/CDA-parasnath/
7. If the old site still appears, refresh after a few minutes or clear the browser cache.

## Add photographs
Use genuine academy photographs with permission. Suggested filenames:
- `images/hero.jpg` — optional hero background photo
- `images/director.jpg` — director portrait
- `images/group-training.jpg`
- `images/classroom.jpg`
- `images/fitness.jpg`
- `images/academy-event.jpg`
- `images/study-session.jpg`

Current gallery and director areas use labelled visual placeholders, so no broken image links are shown. To use a photo in the hero, add this to `.hero` in `style.css` before its gradients:
`background-image: url("images/hero.jpg"); background-size: cover; background-position: center;`
For the director, replace the `.portrait-placeholder` div in `index.html` with:
`<img src="images/director.jpg" alt="Director of CDA Parasnath" class="director-image">`
Add styling such as `.director-image{width:100%;height:360px;object-fit:cover;}`.

## Important functional notes
- **Admission enquiry:** validates the form and opens WhatsApp with a prefilled message to +91 81464 72092. The user must press Send in WhatsApp.
- **Student review:** validates fields and opens WhatsApp with the review for manual moderation. The static site does not save or publish reviews. Do not describe it as an online database.
- **Student directory:** the eight names and course interests are shown together in a compact directory. All statuses are labelled “Currently Preparing”; no selection or qualification is claimed.
- **Quiz:** five original practice questions with scoring and restart functionality. They are not represented as official SSC PYQs.
- **Timetable/results:** placeholders are used because confirmed schedules and verified results were not supplied.
- **Course availability, fees, timings and services:** confirm directly with the academy before publishing as guaranteed offerings.
- **Contact/map:** location is shown as Dumri, Jharkhand. A precise map is omitted until a verified location pin/address is supplied.
- **External resources:** buttons link to official portals or authorised learning platforms; links may change, so check them periodically.

## Quality checklist
- Mobile navigation: implemented.
- Student directory: implemented.
- Student profile modal: implemented with honest placeholder text.
- Quiz answer feedback, score, next and restart: implemented.
- Form validation and WhatsApp message construction: implemented.
- Real database, admin dashboard, photo upload, automatic review approval and saved submissions: **not included**. These require a backend/service and configuration.


## Academy photos added
The package now includes the supplied director portrait and academy photographs:
- `images/director.jpg`
- `images/group-training.jpg`
- `images/award-ceremony.jpg`
- `images/academy-event.jpg`
- `images/hill-activity.jpg`
- `images/flag-ceremony.jpg`

The director section displays **Surendar Kumar Mandal — Director, CDA Parasnath Defence Academy**. Confirm that everyone pictured has given permission before publishing the photos publicly.
