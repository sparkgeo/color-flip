# Transcript

## 2026-06-05

**Prompt:** Can you make the copyright year dynamic so it automatically gets set to the current year?

**Response:** Replaced the hardcoded `2026` in the footer of `index.html` with a `<span id="copyrightYear">` element, and added a one-line script that sets its text content to `new Date().getFullYear()` so the year always reflects the current year in the visitor's browser.
