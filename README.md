# Justin B. Smith portfolio

A static, public-facing portfolio for operations, data, and practical technology work. Open `index.html` locally or serve this directory with any static file server. No build process or third-party scripts are required.

The homepage features College Hockey Data, followed by the sports archive catalog, business systems examples, and a compact selection of independent projects. `college-hockey-data.html` explains the collection, reconciliation, visualization, and maintenance work behind the site. Shared styles live in `index.css`; the original project pages use the same editorial design. The GLI gallery uses the existing `images/gli_program` assets.

## October 2026 visual refresh

- Warm ivory, charcoal, deep green, and restrained copper accents connect the portfolio to CH Data while serif headings give it a separate identity.
- A compact introduction retains the existing operations headline and uses a small portrait. The original photo is preserved; its crop, brightness, contrast, and saturation are adjusted in CSS.
- `images/ch-data/` contains the CHD badge and actual Player Atlas and Roster Origins screenshots captured from the project's local public build. These are static examples; the adjacent links open the interactive site.
- The archive and internal business examples retain their status labels. The 2025–26 hockey project is now labeled as earlier work.
- There is no new build step or third-party dependency. To preview, run `python -m http.server 8765 --bind 127.0.0.1` from this directory.

## Editorial approach

- Lead with business problems and specific work, rather than a broad list of tools or an unsupported job title.
- Label internal work as case studies. The underlying business data and systems are not public.
- Link public projects where visitors can inspect methods and outputs.
- Feature College Hockey Data as current work and keep the 2025–26 research available as an earlier case study.
- Present the archive catalog as ongoing work with private source material, and describe the police chart as exploratory rather than a current risk ranking.
- Keep the 2023 résumé PDF off the homepage; a current résumé should replace it only after its content is reviewed.

## Before publishing

Confirm each business case study is described accurately and that sharing the company names is comfortable. Review the public project repositories and Tableau dashboard for current presentation. Check the contact email and LinkedIn URL. The page is self-contained and can be deployed to GitHub Pages or any static host.
