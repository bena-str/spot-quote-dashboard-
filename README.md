# Air Spot Quote — Dashboard Preview

Interactive prototype for the Air Spot Quotation tool (One Platform, NAM Phase 1).

## Live preview

Once GitHub Pages is enabled, the preview is available at:

`https://<your-username>.github.io/<repo-name>/`

## Notes

- Single-file prototype: all HTML, CSS, and React JSX live in `index.html`.
- React + Babel are loaded from CDN — the page needs internet, and first load compiles JSX in the browser (expect ~1–2s).
- Access is behind a client-side password gate. This is a speed bump, not a security boundary — anyone who views page source can read the password.
- Data shown is illustrative mock data, not real customer quotes.

## Source

The corresponding React component (for integration into One Platform) is maintained separately in `spot-quote-dashboard.jsx` and not published here.
