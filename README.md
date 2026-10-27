# Sharjeel Iqbal — AMUSU President campaign website

A responsive, single-page HTML/CSS/JavaScript campaign website with an original editorial style.

## Personalised details
- Candidate: Sharjeel Iqbal
- Position: AMUSU President, 2026–27
- Tagline: Student First. Always.
- Instagram: https://www.instagram.com/sharjeel_iqbal4president
- Election date entered: 5 November 2026 (provided by the user)
- Countdown time currently uses a placeholder of 9:00 AM IST; verify the official polling time before launch.

## Included
- Responsive campaign landing page
- Editable manifesto
- Department and hall visit section
- Candidate photo and gallery slots
- Testimonial placeholders (not real endorsements; replace with genuine consented quotes or remove)
- WhatsApp share-only button
- Instagram profile links
- Election countdown
- Feedback form interface (does not send or save submissions until a real endpoint is configured)

## Add the candidate photo
Place the uploaded candidate portrait in this folder named `candidate.jpg`. The site references that filename. If the photo has a different filename, update the `src="candidate.jpg"` reference in `index.html`.

No candidate photo was embedded in this package because no image file was attached with the customisation request. Add the intended image before publishing.

## Important before launch
1. Replace the visit placeholders with confirmed visits and dates.
2. Replace or remove all testimonial placeholders. Do not publish invented endorsements.
3. Confirm the election date, polling time, eligibility, and voting instructions against official AMU notices. The 9:00 AM countdown time is only a placeholder.
4. Configure `FORM_ENDPOINT` in the JavaScript to a real, privacy-reviewed form service or backend. Until configured, the form intentionally does not send or store anything.
5. Review privacy disclosures, form-provider logging and retention, campaign rules, image consent, accessibility, and mobile display.
6. Test all links and functions before sharing the site publicly.

## Preview locally
Open `index.html` in a browser, or run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy on Vercel
1. Upload `index.html`, `README.md`, and your image files to a GitHub repository.
2. Import the repository into Vercel and deploy as a static site (no build command required).
3. Test the generated URL on mobile and desktop before publishing.
