# In the Name of the People — public website

A bilingual (Spanish/English), static public-facing website supporting community work, immigrant-support navigation, and youth volunteering.

- `index.html` — founding story, community videos, education and public action links.
- `actions.html` — genuinely usable public routes to volunteer opportunities and external support resources; no fake signup form.
- `public_updates.json` — **confirmed public events only**. Leave `events` empty if no event is verified.
- `founder.html` — short founder navigation view under the same site. The word `founder` unlocks its UI as a convenience, **not as authentication or encryption**.
- `founder_view.json` — sanitized, explicitly public-safe summary derived from the organization's private records; it is a dated projection, not the source of truth.

Private canonical source: [Our_Volunteering_Organization](https://github.com/JadanPoll/Our_Volunteering_Organization), whose access permissions still apply. Do not paste private notes, participant information, grant correspondence, unpublished finances, confidential project plans or tokens into a public repo, its JSON, or its pages. Anyone can read this site’s HTML and JSON regardless of the founder view's casual unlock.

## Update flow

1. Record real changes in the private organization repo.
2. If a verified activity is ready for public announcements, add it to `public_updates.json` with both language titles, confirmed status, date label and official URL.
3. When founder-facing priorities materially change, revise `founder_view.json` from the canonical source. This is currently a manual, dated projection; **do not claim automatic sync**.
4. Verify the public action page on a normal browser. Do not invent signup confirmation or partner affiliation.

The site's first priority is to help visitors complete real tasks, not increase page count. The public story and design are preserved.
