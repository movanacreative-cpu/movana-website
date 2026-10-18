# Movana Website

A responsive, single-page corporate wellness website built with HTML, CSS and vanilla JavaScript.

## Files
- `index.html` — website content and layout
- `styles.css` — visual design and responsive styles
- `script.js` — mobile navigation, scroll reveals and current year
- `thank-you.html` — post-enquiry confirmation page

## Preview locally
Open `index.html` in your browser. For best results, use VS Code with the Live Server extension.

## Publish with GitHub + Netlify
1. Extract `movana-website.zip` on your computer.
2. Create a new repository on GitHub (for example, `movana-website`).
3. Open the repository and choose **Add file → Upload files**.
4. Drag the contents of the extracted folder into GitHub. Make sure `index.html`, `styles.css`, and `script.js` are at the repository root, not buried in an extra folder.
5. Commit the files.
6. In Netlify, choose **Add new site → Import an existing project**, connect GitHub and select the repository.
7. For this plain HTML website, leave the build command blank and set the publish directory to `.` if Netlify asks for one. Deploy.

## Important: contact form
The enquiry form is configured for Netlify Forms (`data-netlify="true"`). It should be detected after the site is deployed. Submit a test enquiry on the live site and check **Netlify → Forms**. If the form does not appear, confirm form detection is enabled for the site and redeploy after making a small commit.

## Before launch
- Replace any placeholder contact details or add official phone, email and social links when supplied.
- Confirm the services, wording and imagery are approved by Movana.
- The page currently uses remote Unsplash image URLs and Google Fonts, so internet access is needed to load those assets.
- Do not publish claims, testimonials, statistics or client logos unless Movana has verified them.


## Movana photo update
- `images/boxing-session.jpg` is the real boxing-session photo supplied for the Group Fitness card.
- The website accent has been shifted toward deep blue to match the selected Movana brand direction.
