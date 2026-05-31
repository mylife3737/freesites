# Free Website Offer — Landing Page + Questionnaire

A two-page static site. No build step, no dependencies to install — just HTML
(fonts load from Google Fonts over the web).

- `index.html` — the landing page (the "Free Website Design Giveaway" offer)
- `questionnaire.html` — the intake form the CTA button links to

## Launch it free on GitHub Pages

1. Create a new repository on GitHub (e.g. `free-website-offer`).
2. Upload these files to the repo root (`index.html`, `questionnaire.html`,
   and this `README.md`). You can drag-and-drop them in the GitHub web UI via
   **Add file → Upload files**, then **Commit changes**.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set **Branch** to `main` and the folder to `/ (root)`, then **Save**.
6. Wait ~1 minute. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

The landing page loads first; clicking **Reserve My Spot** opens the
questionnaire (`questionnaire.html`) in the same window.

## Custom domain (optional)

In **Settings → Pages → Custom domain**, enter your domain and follow the DNS
instructions GitHub shows. Add a `CNAME` file (GitHub creates it for you) and
point your domain's DNS to GitHub Pages.

## Notes

- The forms are front-end only — submitting shows a success message but does
  not send data anywhere yet. To actually receive responses, wire the form to a
  service like Formspree, Google Forms, or Netlify Forms.
