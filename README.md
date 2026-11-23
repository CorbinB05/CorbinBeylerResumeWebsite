# Corbin Beyler · Resume and final web project

## Pages

- `index.html` — Bootstrap-based resume landing page with education, work history, and skills.
- `service.html` — Bootstrap page for service, former youth quorum leadership, and the current YSA ward FHE group leader role.
- `japanese.html` — from-scratch Japanese language learning page. It uses only its own stylesheet, `japanese.css`, and does not load Bootstrap.
- `language-lab.html` — single-file Japanese phrase recall app linked from the scratch page.
- `assets/corbin-portrait.jpg` — supplied portrait used on the resume and scratch page.

Open `index.html` in a browser to start. The two Bootstrap pages load the framework from its CDN, so an internet connection is needed for their layout and navigation menu. The scratch page, chart, and practice app are local HTML/CSS/JavaScript. The live Tableau view and video also need an internet connection. If the YouTube embed shows Error 153 in a local preview, use its “Watch on YouTube” link; the player may need the website to be hosted on an HTTPS address before it will load inside the page.

## Project rubric map

| Requirement | Where to find it |
| --- | --- |
| Professional Bootstrap pages and HTML resume | `index.html`, `service.html`, `styles.css` |
| From-scratch page with separate stylesheet | `japanese.html`, `japanese.css` |
| Nested list, image, YouTube embed, on-page anchors, custom background | `japanese.html` |
| At least three styled/positioned content blocks | `japanese.html` and `japanese.css` |
| Live interactive Tableau view | `japanese.html` — language and country dashboard |
| Link back to professional pages | Header and footer links in `japanese.html` |
| One-page AI-collaborative web app linked from scratch page, with furigana and romaji | `language-lab.html` |

## Tutorial concepts in the source

- HTML document structure, metadata, headings, paragraphs, semantic sections, image attributes, ordered and unordered lists, anchors, links, and comments.
- External CSS, element/class selectors, color and background rules, text alignment, inline spans, hover and visited link styles, and the box model.
- Positioning and stacking: the scratch page uses a sticky navigation header, an absolutely layered label with `z-index`, a floated portrait on wide screens, and a fixed back-to-top control. Its reading order remains in the HTML source order.
- Bootstrap CDN integration and targeted custom overrides on the professional pages.
- Responsive media queries and reduced-motion preferences on the from-scratch page.
- A local interactive comparison chart, live Tableau embed, video embed, and a small JavaScript practice app.

## Data and editorial notes

The Japanese learner comparison uses the Japan Foundation's FY2021 and FY2024 overseas institutional survey values: learners, teachers, and institutions. It lets readers switch the measure. It does not represent every person learning independently. The interactive Tableau dashboard offers a broader language-and-country view; it is a third-party live visualization, not a chart of the Japan Foundation survey. The phrase lab displays furigana over kanji and romanized pronunciation below each phrase.

The discussion of possible cognitive benefits is cautious because research findings vary. The page links to the British Academy and International Baccalaureate reviews for more detail. The page also cites the Japan Foundation and Japan's Ministry of Foreign Affairs for Japanese-learning context. The おおきに section uses a video about Osaka speakers' views on how often the expression is used and includes a direct YouTube link as a fallback if the embedded player cannot load.

## Review before submitting or publishing

Some resume bullets are polished drafts based on the roles and dates provided and typical responsibilities. Confirm that each bullet accurately describes what you personally did, especially BYU IT Surplus, office cleaning, landscaping, and church leadership. Add your BYU major and expected graduation date if you want them listed. High school is omitted because the resume currently includes college education.

The class instructions recommend replacing personal contact information for a school-only public project. No email, phone number, or home address is included. Review the portrait and resume content before publishing online.

## Publishing notes

For GitHub Pages, upload the **contents of this folder** to the repository root so `index.html` is at the top level. Keep capitalization and the `assets/` folder intact. The Bootstrap CSS/JavaScript, Tableau dashboard, YouTube embed, and source links need internet access. Verify the pages in a desktop-sized and phone-sized browser window before submission, and check the public site after GitHub Pages finishes publishing.

## Sources

- [Bootstrap 5.3 documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [Japan Foundation: Survey on Japanese-Language Education Abroad 2024](https://www.jpf.go.jp/e/project/japanese/survey/result/information.html)
- [Tableau Public: Are We Speaking?](https://public.tableau.com/app/profile/bridget/viz/AreWe/SpeakingtheSameLanguage)
- [The British Academy: Cognitive benefits of language learning](https://www.thebritishacademy.ac.uk/publications/cognitive-benefits-language-learning-findings-implications/)
