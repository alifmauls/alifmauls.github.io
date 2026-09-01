# Alif Maulana — Finance & Creative Portfolio

Personal portfolio site. Financial reporting, accounting system design and process improvement work, alongside a creative and editing background.

**Live site:** https://alifmauls.github.io

---

## About

Financial Management student at Universitas Brawijaya (GPA 3.82), with two years of finance work carried alongside the degree.

Built a motorcycle spare-parts retailer's finance function from nothing: chart of accounts, transaction recording process, monthly close, P&L, COGS and gross margin analysis by product line, and bank and e-wallet reconciliation. Built the accounting system in-house rather than buying one, which shortened the monthly reporting cycle.

The through line across the work: financial rigour on one side, creative craft on the other. I care as much about how the numbers read as whether they are right.

## What's in this repository

| File | Description |
|------|-------------|
| `index.html` | The entire site. Single self-contained file with CSS, JavaScript and the profile photo all embedded. No build step, no dependencies, no framework. |
| `README.md` | This file. |

## Site features

- Projects filterable by category: Finance & Accounting, Business Analysis, Creative & Editing
- Responsive down to 390px
- Adapts to the visitor's light or dark system theme
- Respects `prefers-reduced-motion`
- Runs entirely offline once loaded, except for the Google Fonts stylesheet

## Editing the site

Everything lives in `index.html`, so all edits happen in that one file.

**Change the profile photo.** Find `<div class="photo-frame">` and replace the `src="data:image/jpeg;base64,..."` value with a new base64 data URI. Keep roughly a 4:5 portrait crop so the frame proportions hold.

**Add a project.** Copy any `<article class="card">` block inside `<div class="grid">` and edit the content. Set `data-cat` to `finance`, `analysis`, `creative`, or a space-separated combination such as `data-cat="finance creative"` for work that belongs in two places. Update the counts in the filter buttons afterwards.

**Change the accent colour.** Edit `--mint` and `--mint-deep` in the `:root` block at the top of the stylesheet. Both light and dark theme values need updating.

**Change the headline.** It sits in `<h1 class="rv">` near the top of the `<body>`.

## A note on project images

Client materials and internal system diagrams are deliberately not published here. Parts of that documentation contain third-party business information and named individuals, so it is shared only on request and with the relevant permissions in place.

## Contact

- Email: malifrmaulana@gmail.com
- LinkedIn: [m-alif-r-maulana](https://www.linkedin.com/in/m-alif-r-maulana/)
- GitHub: [@alifmauls](https://github.com/alifmauls)
- Instagram: [@alifmauls](https://www.instagram.com/alifmauls/)
- Music: [Mauls Music](https://www.youtube.com/@Mauls_Music)
- Location: Malang, East Java, Indonesia
