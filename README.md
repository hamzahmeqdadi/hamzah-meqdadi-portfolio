# Hamzah Meqdadi — Portfolio

A responsive personal portfolio starter built with HTML, CSS and vanilla JavaScript.

## Run locally
1. Extract the ZIP file.
2. Open the `hamzah-meqdadi-portfolio` folder in VS Code.
3. Open `index.html` in your browser, or use the VS Code Live Server extension.

## Personalize before publishing
- Replace the initials placeholder in the hero with your portrait (see below).
- Replace `YOUR_EMAIL@example.com` with your real public contact email.
- Replace the GitHub and LinkedIn profile URLs with your own profile URLs.
- Update the AstroGuard repository link to your actual repository.
- Add only skills and project details you can accurately describe.

## Add your photo
1. Create an `assets` folder beside `index.html`.
2. Copy your portrait into it, for example `assets/hamzah.jpg`.
3. In `index.html`, replace the `<div class="portrait-placeholder"> ... </div>` block with:
   `<img class="profile-photo" src="assets/hamzah.jpg" alt="Portrait of Hamzah Meqdadi">`
4. Add this CSS to `style.css`:
   `.profile-photo{width:100%;height:390px;object-fit:cover;object-position:center 30%;display:block;margin:12px 0;border:1px solid rgba(132,176,230,.15)}`
   For mobile, you can keep the same height or adjust it in the mobile media query.

## Notes
- This is a front-end portfolio. It does not need a backend or database at this stage.
- The skill section intentionally describes areas of exploration rather than claiming professional mastery.
- Check every external link and replace placeholders before publishing.
