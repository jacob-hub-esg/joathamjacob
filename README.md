<div align="center">

<img src="preview/social.jpg" alt="Joatham Jacob — Energy, Decarbonization and ESG, Milan. From the emissions inventory to the measures that cut it." width="100%">

# Joatham Jacob · Energy, Decarbonization & ESG

Portfolio website of an energy and environmental engineer in Milan,<br>working from the emissions inventory to the measures that cut it.

**[Visit the site →](https://joathamjacob.com/)** &nbsp;·&nbsp; [Download CV](https://joathamjacob.com/CV.pdf) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/joatham-jacob) &nbsp;·&nbsp; [Email](mailto:joathamjacob@gmail.com)

</div>

---

## About

I measure and report emissions under the GHG Protocol, ISO 14064 and CSRD, and I cost and rank the measures that reduce them on marginal abatement cost curves (MACC) under EU ETS and CBAM. This repository holds my personal website: a featured case study, the tools I've built, what I know, my experience and my credentials.

## Featured case study: Acciaieria Arvedi, Cremona

Arvedi's Cremona EAF steelworks was the first steelmaker with a certified net-zero claim. I set the claim aside, rebuilt the plant's physical Scope 1 baseline from EU ETS verified emissions, and costed a 2030 abatement package.

| | |
|---|---|
| Verified Scope 1 baseline (CY2023, EU ETS) | **434,844 tCO₂** |
| Abated by the 2030 package | **44.3%** · 192,494 tCO₂ per year |
| Modelled package cost | **€11.44 per tonne of steel**, about 1.8% of product value |
| Annual ETS/CBAM liability, 2026 → 2034 | **€6.9M → €32.6M** |

Capex and opex are modelled estimates from public sources, not supplier quotes; only the Scope 1 baseline is third-party verified.

**[Read the full study (PDF, 39 pages)](arvedi-case-study.pdf)**

## Tools I've built

| Tool | What it does |
|---|---|
| [MACC & project finance tool](https://jacob-hub-esg.github.io/macc-finance-tool/) | Live abatement cost curve, cheapest measures first, with payback, NPV, IRR, LCOE and levelised cost of abatement for each measure. Updates with the EU ETS price. |
| [Building emissions benchmark & decarbonisation tool](https://jacob-hub-esg.github.io/esgbenchmark/) | Scope 1–2 for six building types in 20 European countries on IEA grid factors, benchmarked against EU peers, with CSRD checks and a 2050 net-zero pathway. |
| [CSRD readiness assessment](https://jacob-hub-esg.github.io/csrd-framework/) | About 40 weighted questions across all ten ESRS topics, scored 0–100 by section, with priority gaps and actions. |
| [CO₂ benchmark calculator](https://jacob-hub-esg.github.io/my-calculator/) | Operational carbon for commercial buildings by scope, rated against EU Taxonomy, EPBD and BREEAM. |
| Energy performance monitoring pipeline *(in progress)* | Python and Power BI: hourly meter data, a weather-normalised degree-day baseline and flagged deviations, following ISO 50001 performance monitoring. |

## What's on the site

<img src="preview/pages.jpg" alt="Six pages of the site on a laptop: case study, tools, knowledge, ESG, experience and credentials" width="100%">

| Page | What it shows |
|---|---|
| **Home** | Who I am and what I do, with links to my CV and LinkedIn |
| **Case study** | The Arvedi baseline, the 2030 cost curve and four findings |
| **Tools** | The apps above, plus field work: energy, water and load surveys at 8 railway stations in Bihar, a biogas plant evaluation in Palakkad, and solar design |
| **Knowledge** | Industrial energy systems, decarbonization methods, EAF steel, and energy data tools, each with where I've applied it |
| **ESG** | GHG inventories, reporting and disclosure, assurance, targets, LCA, and supply chains and buildings, each with evidence |
| **Experience** | Three roles (Industrious Global Technologies, Omtra, Earth Academy Global) that open to show details, plus my M.Sc. (University of Milan) and B.Tech (TNAU) |
| **Credentials** | Tools and languages, certifications, organisations I've worked with, and Earth Academy practitioner badges |
| **Contact** | Email, LinkedIn and CV downloads |

On phones it becomes one scrolling page with a menu, and the card sections swipe sideways:

<img src="preview/phone.jpg" alt="The site on a phone: landing page, knowledge cards and experience" width="640">

## How it's built

- **One static page.** `index.html` holds the content, styles and scripts in plain HTML, CSS and JavaScript: no framework, no build step, no cookies or tracking, and no requests to outside services. Fonts and images are served from this repository.
- **Laptops and desktops:** each section is a 16:9 page. You move between pages with the floating dock or the arrow keys, and each page has its own address (for example `#work`), so direct links and the back button work.
- **Phones and tablets:** one scrolling page with a menu bar.
- **Accessibility:** light and dark themes, keyboard navigation, and no animation for visitors who have "reduce motion" turned on.
- **Hosting:** GitHub Pages, which publishes the site automatically when the repository changes.

## Repository layout

| Path | What it is |
|---|---|
| `index.html` | The whole site: content, styles and scripts |
| `CV.pdf` | The CV behind the download buttons |
| `arvedi-case-study.pdf` | The full Arvedi case study |
| `hero.jpg`, `graduation.jpg` | Photos |
| `badge-*.webp` | Earth Academy practitioner badges |
| `*.woff2` | Self-hosted fonts |
| `LICENSE-*-OFL.txt` | Font licences |
| `preview/` | The share image and screenshots used here and in link previews |

## Updating the site

- **New CV:** replace `CV.pdf`, keeping the same name.
- **Organisation logos:** add `logo-<name>.svg`, `.png` or `.webp` next to `index.html`, and it replaces the name on its plate. The names are `cartier`, `busatti`, `isos`, `al-dabbagh`, `tanmiah`, `insight-energy` and `cgs-green`.
- **Tool links:** edit `PROJECT_LINKS` near the end of `index.html`.

## Credits and licence

- The text, photos, case study and CV are © Joatham Jacob, all rights reserved. Please ask before reusing them.
- The fonts are Bebas Neue, Fraunces, Quicksand and IBM Plex Mono, used under the SIL Open Font License 1.1; their licence files are included.
- Organisation names identify clients and partners I have worked with; they do not imply endorsement.

## Contact

[joathamjacob@gmail.com](mailto:joathamjacob@gmail.com) · [linkedin.com/in/joatham-jacob](https://www.linkedin.com/in/joatham-jacob) · Milan, Italy
