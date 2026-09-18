# Change Log 

**Date:** 2026-09-18

## Summary
This changelog documents the second phase ("Part 2") of styling and structural updates applied to the Valambya Mobile Freezers site.

## Highlights
- Applied a blue-and-white theme and global CSS reset.
- Reworked header / navigation layout and enlarged the site title.
- Added utility classes and accessibility improvements (focus outlines, responsive images, skip-link support).
- Replaced and standardized page structure on root HTML files to use `.container` / `.card` / `.site-header` patterns.
- Redesigned and improved the enquiry form (better inputs, layout, and submit button).
- Added tablet and phone responsive breakpoints with tailored layout adjustments.

## Files Added / Modified
- `css/style.css` — main stylesheet; theme, reset, utilities, responsive rules.
- `index.html` — new header, hero, container/card layouts, footer.
- `about.html` — converted to container/card layout and linked stylesheet.
- `services.html` — converted to container/card layout and linked stylesheet.
- `enquiry.html` — improved form markup, accessible inputs, submit button.
- `contact.html` — contact container + responsive map iframe.
- `CHANGELOG-part2.md` — this changelog file.

## Notable Changes (short)
- Header: navigation centered above the title; title moved beneath nav and enlarged.
- Hero: larger type on desktop; scaled down on tablet/phone.
- Buttons: `.btn-primary` and `.btn-outline` variants added.
- Forms: clearer labels, improved input types, focus states, and submit styling.
- Layout: `.container` and `.card` used across pages for consistent spacing and alignment.

## Accessibility & Responsiveness
- Focus-visible outlines added to interactive controls for keyboard users.
- Images and iframes set to `max-width:100%` for responsiveness.
- Breakpoints added for tablet (<=1024px) and phone (<=600px).

## Next Steps / Recommendations
- Replace the decorative `.site-title` div with a semantic `h1` on the homepage for SEO and accessibility.
- Add site-wide meta and open-graph tags in the `<head>` of the pages.
- Run a contrast/AX audit (e.g., Lighthouse or axe) and adjust colors if needed.
- Optionally DRY the header/footer by extracting them into reusable includes (server-side or simple JS include) if you plan to scale.

## References
- Detailed part-2 changelog: [CHANGELOG-part2.md](CHANGELOG-part2.md)
- Main stylesheet: [css/style.css](css/style.css)
- Homepage: [index.html](index.html)
- Accessibility (WCAG): https://www.w3.org/WAI/standards-guidelines/wcag/
- Contrast checker (WebAIM): https://webaim.org/resources/contrastchecker/
- Responsive design guidance (MDN): https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design
