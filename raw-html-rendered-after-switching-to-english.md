# LOC-RND-001 – Raw HTML Code Rendered Instead of Page After Switching Language to English

* **Severity:** High
* **Environment:** Production · macOS Sonoma 14.4 · MacBook Air (Apple M1) · Safari 17.4
* **Reproducibility:** Observed

## Summary
Switching the website language from Georgian to English navigates to the English URL path but renders raw HTML markup on a dark screen instead of the formatted web page.

## Preconditions
User is browsing a catalog page in Georgian on the website with the language switcher available in the header.

## Steps
1. Open a product category page while the website language is set to Georgian.
2. Click the language switcher to change the language to English ("EN").
3. Observe the page content and browser rendering.

## Actual
The URL switches to the English path, the screen appears dark, and raw HTML code (tags, attributes, links, and SVG markup) is displayed as text instead of a rendered page.

## Expected
Switching to English should load and render the English version of the page properly with normal UI styling and layout.

## Notes
Localization & rendering issue in Production when switching to the English locale; possible incorrect Content-Type header or broken response/template rendering on the English route.
