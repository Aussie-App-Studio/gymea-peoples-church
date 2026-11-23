# Gymea Peoples Church — Website Redesign

A warm, welcoming, single-file static website redesign for **Gymea Peoples Church** (`166 Gymea Bay Road, Gymea Bay NSW 2227`).

- **Live Preview (GitHub Pages):** https://aussie-app-studio.github.io/gymea-peoples-church/
- **Original Site:** https://gpc.org.au/

## Included Pages & Features
- **Home (`#home`):** Service times (10:00am & 7:00pm Sundays), church identity pillars, ministry highlights, and global missions overview.
- **Plan a Visit (`#visit`):** What to expect, kids Sunday School & crèche info, step-free access & parking details, and an optional visit note form (`mailto:` ready).
- **About & Beliefs (`#about`):** Full *Who We Are* & *Aims & Objectives*, interactive *What We Believe* accordion with clickable Bible Gateway (NIV) Scripture pills, Elders section, and Safe Ministry & Public Policy document links.
- **Ministries (`#ministries`):** Sunday School & Crèche, *Kids at GPC*, *‘Central’ for Teens*, *Holiday Kids Club*, and *SRE (Scripture)* including Youthworks *Connect* & NSW Department of Education documentation.
- **Missions (`#missions`):** Interactive stylized global partner map and regional filter for all 8 mission partners.
- **Contact (`#contact`) & Give (`#give`):** Topic-routed contact form, embedded Google Map with directions, and Direct Bank Transfer (EFT) giving info.

## Before Publishing to Production
1. **Bank Details (`#give`):** Replace `[Insert Church BSB]` and `[Insert Account Number]` in `index.html` with Gymea Peoples Church's official EFT details.
2. **Form Submissions (Optional):** Both `#visit` and `#contact` forms currently prepare `mailto:` emails; see the HTML comments above each form if you wish to wire a static form endpoint such as Formspree or Netlify Forms.
