# HUCU Home Page Modules

`../index.html` is now a lightweight shell that loads these partials with `data-include="modules/..."`
slots and a small client-side loader. The homepage is no longer meant to be maintained as one long
inline document.

When a homepage section changes, update the matching partial here so the homepage and future inside
pages can reuse the same section markup.

Suggested reuse approach for inside pages:

- `topbar.html` and `navigation.html` for global header chrome
- `alert-bar.html` for urgent notices and holiday messaging
- `hero.html` when an inside page needs a featured campaign lead
- `quick-actions.html` for high-priority member tasks
- `services.html`, `rates.html`, `promotions.html`, `why-hucu.html`, `fraud.html`, and `testimonials.html` as reusable content modules
- `about-hero.html`, `about-story.html`, `about-timeline.html`, `about-principles.html`, `about-faqs.html`, and `about-access.html` for the About page system
- `about-locations.html` for the dedicated About page office-location cards
- `about-policies.html` for holiday/partnership/privacy accordion content near the bottom of About
- `page-banner-about.html` for the About page title banner directly under the global navigation
- `page-banner-rates.html` for the Rates page title banner with a page-specific background image
- `page-banner-loans.html` and `loans-content.html` for the Loans landing-page pattern (inside-page hero + option tiles)
- `cta.html` for end-of-page conversion blocks
- `footer.html` for the global footer and branch-location section

- `alert-bar.html`
- `topbar.html`
- `navigation.html`
- `hero.html`
- `about-hero.html`
- `page-banner-about.html`
- `about-story.html`
- `about-timeline.html`
- `about-principles.html`
- `about-faqs.html`
- `about-locations.html`
- `about-policies.html`
- `about-access.html`
- `page-banner-rates.html`
- `page-banner-loans.html`
- `loans-content.html`
- `quick-actions.html`
- `services.html`
- `rates.html`
- `promotions.html`
- `why-hucu.html`
- `fraud.html`
- `testimonials.html`
- `cta.html`
- `footer.html`
