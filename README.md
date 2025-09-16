# 2024-2025 Timetable — Glaine Amoni

## Files
- `index.html` — main HTML file containing a semantic `<table>` timetable.
- `style.css` — styling for fixed layout, borders, and highlights.
- `timetable_preview.png` — screenshot preview of the timetable.

## Accessibility
- Table uses `<thead>` and `<tbody>`.
- Column headers use `<th scope="col">`, row headers use `<th scope="row">`.
- Table has a `<caption>` describing contents.
- Special cells (Break / Lunch / Activities) have distinct background styles and `title` attributes for screen-reader clarity.
- **Alt text for preview image**: "Screenshot of the timetable for 2024–2025 showing Mon–Fri, periods 1–13; breaks and lunch highlighted."

## Notes
- The table is fixed-width and centered for readability as requested.
- Merged cells use `rowspan` for vertical merges (e.g., break and lunch spanning Years 7–11) and `colspan` for multi-period lessons.
- Validate `index.html` (W3C Markup Validation Service) and `style.css` (W3C CSS Validator) before submission.

