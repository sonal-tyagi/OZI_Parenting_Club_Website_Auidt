# OZi Parenting Club – Website Audit

A website audit of [ozi.in](https://ozi.in), a quick-commerce platform for baby care, maternity essentials and kids' products. It covers technical SEO, on-page SEO, conversion optimization (CRO) and UI/UX.

**Presented by:** Sonal Tyagi
**Audit date:** October 2026
**File:** [`OZI_website_audit.pdf`](./OZI_website_audit.pdf)

> **Note:** All observations are based on the website as it appeared in **October 2026**. The website may have been updated since then, so some issues may already be fixed or no longer relevant.

---

## About OZi

| Item | Details |
|------|---------|
| **Business model** | Online multi-category commerce platform |
| **Target audience** | Parents, caregivers and families with babies and growing children |
| **Core value proposition** | Children's and maternity essentials delivered to the doorstep, with delivery advertised in as little as 60 minutes in serviceable locations |
| **Categories** | Baby care and hygiene, feeding, toys, kids' fashion, school supplies, maternity care |

---

## Audit Scope

1. Technical Audit
2. CRO Audit
3. On-Page Audit
4. UI/UX Audit

---

## Key Findings (as per October 2026)

### Technical Audit

| # | Issue | Recommendation |
|---|-------|----------------|
| 1 | **Category URLs are not descriptive or consistent**, e.g. `/category/gear-furniture-c3` | Use concise, descriptive slugs (e.g. `/category/baby-gear`) and add 301 redirects |
| 2 | **Product URLs are lengthy and carry unnecessary identifiers**, e.g. `...-pack-of-23m-3y-prid-13855` | Shorten URLs to the main product keywords. Check organic performance and backlinks first, then add 301 redirects and update internal links and canonical tags |
| 3 | **Blog URL and content mismatch**: a related blog auto-loads at the bottom, and the address bar changes to its URL but doesn't change back on scroll up | Remove the auto-loading and add a "Related Blogs" section (image, title, short description, link). The URL should always match the article being read |

### CRO Audit

| # | Issue | Recommendation |
|---|-------|----------------|
| 4 | **"Free Trial at Home" CTA lacks visibility**: it appears as a small icon | Make the CTA more prominent, explain the benefits and steps, and A/B test placements |
| 5 | **Trial eligibility may create friction**: customers must select 10 items | Show eligibility criteria upfront, evaluate a lower item threshold or minimum order value, and compare trial completion and purchase rates before changing it |
| 6 | **Colour/design selection is unclear**: the product page shows several designs but offers no way to choose one | Add selectable variants and update images and availability per selection, or clearly state what the pack includes |

### On-Page Audit

| # | Issue | Recommendation |
|---|-------|----------------|
| 7 | **Generic and repetitive category page content**, e.g. `/category/fashion-c4`, `/category/toys-c6` | Write unique, category-specific descriptions with natural keywords, product types, features and buying considerations |
| 8 | **Blog section needs work**: generic content, missing author credentials on YMYL topics, weak internal linking, inconsistent product links, loose structure | Add original insights and expert input, author bios and medical reviews, contextual links to related articles and products, Article/BlogPosting structured data, and topic-based sections |

### UI/UX Audit

| # | Issue | Recommendation |
|---|-------|----------------|
| 9 | **Social media links missing from the footer** (Instagram, LinkedIn) | Add clickable icons, prioritizing Instagram for consumer content and LinkedIn for brand credibility |
| 10 | **Product images not loading in blogs**: blank white boxes, e.g. `/blogs/infants/crib-vs-cot-difference` | Check image URLs, paths, server responses and lazy-loading, link the correct images to each article, and test on desktop and mobile |

---

## Final Reflection

| Focus Area | Priority Actions |
|------------|------------------|
| **Technical SEO** | Improve URL consistency, fix broken images, validate structured data |
| **Content & SEO** | Build useful category content, strengthen blog credibility, improve internal linking |
| **User Experience** | Make sure product visuals load, improve navigation, make product info clearer |
| **Conversion Optimization** | Improve visibility of key offers and trial options, simplify the path to purchase |

**Recommended next step:** Fix issues affecting site functionality and product discovery first, then roll out content and conversion improvements. Measure progress through organic traffic, engagement, product-page interactions and conversion rate.

---

## Repository Contents

```
├── OZI_website_audit.pdf   # Full audit presentation
└── README.md
```

## Author

**Sonal Tyagi** – [GitHub](https://github.com/sonal-tyagi)
