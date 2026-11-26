# SumHours

Single-page website for **SumHours** (https://sumhours.com), built around the main keyword "SumHours".

## Files

| File | Purpose |
|---|---|
| `index.html` | Main page: luxury dark-emerald and champagne theme, animated hero clock, 1,300+ word SEO article, FAQs, conclusion |
| `robots.txt` | Lets all search engines crawl the site and points them to the sitemap |
| `sitemap.xml` | Lists the home page for search engines |
| `README.md` | This file |

## How to publish

1. Upload all four files to the root folder of your hosting (the same folder where your domain points).
2. Open `https://sumhours.com/robots.txt` and `https://sumhours.com/sitemap.xml` to confirm they load.
3. Submit `https://sumhours.com/sitemap.xml` in Google Search Console and Bing Webmaster Tools.

## Page notes

- Heading structure: one H1, one H2, then H3 and H4 for all other headings.
- Images are inline SVG illustrations, so they load instantly with no external requests. Each has an `aria-label` and a caption.
- The "See More" anchor text appears once, in the second paragraph, and links to https://sumhours.com. No other link to that address exists in the page body.
- No phone number and no call button anywhere on the page.
- Animations switch off automatically for visitors who prefer reduced motion.
- Fonts (Cormorant Garamond and Manrope) load from Google Fonts, with Georgia and system sans-serif as fallbacks.

## Editing tips

- Colours live in the `:root` block at the top of the `<style>` section in `index.html`.
- If you want a canonical tag, add `<link rel="canonical" href="https://sumhours.com/">` inside `<head>`. It was left out on purpose so the only visible link stays in the second paragraph.
