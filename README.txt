Da3wet 3arousa — Landing Page for GitHub Pages
======================================

FILES
- index.html: page structure and Arabic/English copy
- style.css: responsive design, layout and colors
- script.js: language switcher and Google Form button configuration

PUBLISH TO GITHUB PAGES
1. Create a GitHub repository (Public is simplest for GitHub Pages).
2. Upload all files directly into the repository root (not inside another folder).
3. Open Settings > Pages.
4. Under Build and deployment, choose "Deploy from a branch".
5. Choose branch "main" and folder "/ (root)", then Save.
6. Wait for the published URL to appear on the Pages settings page.

CONNECT YOUR GOOGLE FORM LATER
1. Create your Google Form and copy its responder link.
2. Open script.js and replace the empty value in:
   const GOOGLE_FORM_URL = "";
   with your form link, e.g.
   const GOOGLE_FORM_URL = "https://docs.google.com/forms/d/e/FORM_ID/viewform";
3. Commit/save the change. The main order button will open your form.
4. To collect form answers in a spreadsheet, open the Form > Responses > green Google Sheets icon > Create new spreadsheet. Responses will be added as new rows automatically.

CUSTOMIZE
- Brand name: edit the "Da3wet 3arousa" / "دعوة عروسة" text in index.html.
- Colors: edit the CSS variables at the beginning of style.css.
- The sample invitation names are examples only.
- Google Fonts are loaded online; fallback fonts are included.

This is a static site. Form responses are collected by Google Forms/Sheets, not by GitHub itself.
