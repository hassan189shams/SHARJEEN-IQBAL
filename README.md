# Sharjeel Iqbal — Premium AMUSU President Website

## Candidate and design
- Candidate: Sharjeel Iqbal
- Role: AMUSU President candidate, 2026–27
- Primary slogan: “Awaz Aapki. Zimmedari Meri.”
- Secondary slogan: “Ilaaka Nahi, Alig. Lobby Nahi, Liyaqat.”
- Style: Premium refined, warm ivory, deep green, muted gold
- All three supplied photographs are included and displayed equally in the gallery.

## Files
- `index.html` — complete responsive website
- `assets/sharjeel-portrait.jpg` — supplied portrait photo
- `assets/amu-portrait.webp` — supplied university portrait photo
- `assets/amu-arch.webp` — supplied archway photo

## Included sections
- Premium candidate hero
- Slogans and campaign principles
- Eight manifesto priorities
- Department/hall visit placeholders
- Three-photo gallery
- Student grievance form requesting name and enrolment number
- WhatsApp sharing and Instagram link
- Election countdown configured for 5 November 2026 at a placeholder 9:00 AM IST

## Critical before launch
1. Replace visit placeholders with real, confirmed dates and details.
2. Verify the election date and exact polling time with official AMU notices. The 9:00 AM time is a placeholder.
3. The grievance form currently does not send or store submissions. Configure a secure backend before collecting real names, enrolment numbers, or complaints.
4. Because the form collects identifying information, do not describe it as anonymous. Add a privacy notice, restrict access to authorised handlers, use secure transport/storage, define retention/deletion practices, and test access controls.
5. Review the manifesto and campaign claims for accuracy; the priorities are proposed advocacy, not claims of achieved outcomes.
6. Obtain consent before publishing identifiable photos or testimonials of other students. No testimonials have been invented or included.

## Preview
Open `index.html` in a browser. For a local server:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy to GitHub + Vercel
Upload `index.html`, `README.md`, and the `assets` folder preserving the folder structure. Import the repository in Vercel and deploy as a static site. No build command is required.


## First 100 days roadmap
Added a proposed phased plan:
- Days 1–15: open student listening desk and explain privacy handling
- Days 1–30: map recurring campus issues
- Days 15–40: department/hall consultations
- Days 25–50: anonymised priority concerns summary
- Days 35–70: documented representations to appropriate offices
- Days 50–80: compile verified student resource links
- Days 70–90: track and follow up on issue status
- Days 90–100: publish a factual progress report

These are proposed priorities, not guaranteed outcomes or claims of control over university decisions.

## Owner-only editing
The site includes an owner editing guide. The static site itself does not provide a private admin dashboard. Edit access is controlled by GitHub repository permissions:
1. Sign in to the GitHub account that owns the repository.
2. Open `index.html`, click the pencil/Edit button, make changes, and commit.
3. If the repository is connected to Vercel, the new commit should trigger redeployment.

Do not add a password-only admin UI in client-side JavaScript; it cannot securely protect content. For an actual in-site CMS, configure an authenticated CMS and server-side permissions.


## Latest premium revision
- Refined visual details, hover states, shadows, typography smoothing and social-sharing metadata.
- Election countdown is displayed prominently for 5 November 2026 at 9:00 AM IST as a placeholder target.
- Footer credit: Website crafted by Hassan Shams (@hassan_sabir08); social media marketing and digital campaign presence by Hassan Shams.
- Verify the official election date and polling time with AMU notices before public launch.


## Added CPC student concerns section
- Clearly presents CPC students' questions about AMUSU election voting eligibility and hall allotment.
- Calls for transparent official rules and an administrative response without asserting unverified rules as fact.

## Added hall-by-hall concerns
- Boys' Halls of Residence: all 13 supplied hall names.
- Girls' Halls of Residence: all 6 supplied hall names, including SN Hall.
- Every hall has a dedicated textarea-style content area for questions and updates.
- These textareas are visual placeholders, not a submission or persistent storage feature. Edit the hall card placeholder/content in `index.html` and commit changes to publish updates.

## Original illustration
- `assets/amu-editorial-illustration.svg` is an original, non-controversial campus-heritage illustration created for this website.
- No invented testimonials or claims about official policy have been added.

## Owner editing limitation
The website does not pretend to have a secure in-browser CMS. Owner edits are made through authenticated GitHub repository permissions. A real dashboard for editing live content requires an authenticated backend/CMS and must not be simulated with a client-side password.


## Version 5 — campaign gallery, student questions and detailed hall concerns
- The fourth image supplied in this update (`IMG_9867(10).jpeg`) is used as the primary hero portrait.
- Added seven supplied photographs to the candidate gallery, each captioned “Sharjeel Iqbal for Presidentship 26–27”.
- Added “Five Questions Every Student Deserves Answered” directly after the First 100 Days section.
- Positioned the CPC students' concerns section below those five questions, as a subsection within the main campaign site rather than a separate page.
- Replaced generic hall cards with detailed, expandable hall-by-hall concerns for all 13 boys' halls and all 6 girls' halls.
- Hall-specific content is labelled as concerns supplied for the campaign and not independently verified; publish follow-up statuses only when confirmed.
- Each hall has an additional notes area for future questions/verified updates. Those textareas do not save or publish content.
- Website owner can update the source using authorised GitHub access; this is a static website, not an authenticated in-browser CMS.
