# Working on the website

The first question is whether someone can actually do what they came here to do.

The everyday paths are **volunteer**, **find community help**, **contact the organizers**, and **check the next event**. The story and videos live on `journey.html`, prominently linked from the homepage. A first-time visitor should find these without an explanation, and a returning visitor should not need to remember a hidden feature.

- Keep the light, handwritten community-notebook feel. Preserve Bryan's story and the bilingual video content.
- Buttons must lead somewhere useful. Don't add an action unless the destination works; never simulate registration or successful submission.
- Keep the Spanish and English versions complete, including links when switching pages.
- Events are shown only after the date, host, public contact link and permission are confirmed. Public entries in `public_updates.json` need `public: true`, `status: "confirmed"`, `title_es`, `title_en`, `date_label` and an HTTPS `url`. An empty list is fine.
- The website is publicly served. Do not put participant information, credentials, internal documents or private notes in any HTML, CSS, JavaScript or JSON file.
- Write text for visitors, not for developers or AI agents. Do not put process explanations, self-justifying warnings, empty evidence fields, or implementation terminology into page copy. Keep development instructions here.
- Before making a large change, compare what happens on the first visit, after a month away, and during quick repeat use. Prefer removing friction over adding another page, menu or card.
- Check real links, language toggling, event states, mobile navigation, story and video controls after substantive edits. Keep the existing design archived instead of starting over.

The founder view is a public shortcut page, not protected storage. Its links to restricted documents still require GitHub or Google permissions.
