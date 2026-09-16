# Portfolio audit — September 2026

## What was there

The site is a static HTML/CSS/JavaScript portfolio with local photos, project screenshots, a hospitality image library, several stand-alone visualization pages, and a 2023 résumé PDF. No package manager or build step is required. Its main page emphasized a broad "Data Analyst" identity, a long software list, sports projects, and a hospitality photo carousel.

## Main issues found

- The strongest bridge to technical work—Excel/Access inventory and costing, reservations, production tracking, records, and process design—was barely visible.
- The introduction used general claims rather than a clear account of problems solved. Some project descriptions described future machine-learning goals alongside finished work, making the status hard to judge.
- The résumé link led to a 2023 document. It should be reviewed and replaced before returning to the public page.
- Several links used `#` placeholders, and the main page relied on third-party Bootstrap, jQuery, Popper, icon images, and analytics scripts. The navigation markup was also invalid (list items outside a list).
- The repository includes several very large stand-alone HTML maps (roughly 13–52 MB each), old alternate CSS, and a large image library. They are not needed to load the new homepage, but they still deserve a separate archival and repository-size review.
- The project shortlist spreadsheet marks the baseball map as needing JavaScript map fixes and the sports atlas as needing a data refresh. Those items should not be presented as newly maintained.

## Changes made

- Rewrote the homepage around operations systems, data, and process improvement, with a direct invitation to discuss remote or project work.
- Added two accurately labeled internal case studies and three linked public projects, including a practical sports-to-Excel automation tool. Internal data and code are not implied to be public.
- Replaced the skills cloud with a short background and a focused toolkit. Hospitality experience remains central to the story.
- Removed the outdated résumé link, dead links, carousel, and third-party scripts from the homepage.
- Added responsive layout, semantic sections, a skip link, descriptive image text, visible keyboard focus, and reduced-motion support.
- Kept the site static and simple to host. Old project pages and images remain in the repository; none were deleted in this pass.

## September 2026 project-selection revision

- Replaced the link to the original college hockey statistics repository with the more substantial 2025–26 season project. Its public README is minimal, so a local case-study page explains the scope and links to the repository.
- Promoted the sports publication archive from a brief mention to a featured ongoing case study. The verified baseline contains 9,039 unique card images and record IDs; the source scans and review database remain private.
- Rebuilt the unofficial 2023 GLI program page as a responsive gallery using page images already in the portfolio. It is clearly labeled as an unofficial fan project.
- Added the historical policing visualization as a smaller exploratory project with a methods caution. Its 1992–2018 comparison is not presented as a current ranking.

## Next editorial pass

Review the business case-study wording with Justin, update the public project repositories and dashboard where needed, and prepare a current résumé before posting a download link. If a deeper technical showcase is desired, the Excel/Access and reservation examples would benefit from redacted screenshots or short diagrams showing inputs, decisions, and outputs.
