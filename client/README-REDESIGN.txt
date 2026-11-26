GAIL Regional Operations & Maintenance Portal — UI Refresh

What changed:
- Refreshed the visual system with GAIL green, forest-green navigation, warm gold accents and calm light surfaces.
- Added a responsive homepage hero and a bundled local banner fallback when no hero image is configured in Admin.
- Rebuilt the Events & Meetings calendar with responsive month grid, date selection, selected-day agenda, upcoming list and region filter.
- Restyled the homepage events/calendar and JLPL route-map panels.
- Replaced the fragile remote GAIL logo URL with a bundled local image asset.
- Improved mobile layouts for navigation, events, calendar, route map and footer.

Setup:
1. Extract the client folder.
2. Open a terminal in the client folder.
3. Run: npm install
4. Run: npm run dev

The existing API endpoints and admin-managed event/meeting records are retained. The calendar reads from GET /calendar and homepage widgets continue to use the existing PortalContext data.
