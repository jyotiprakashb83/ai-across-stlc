# AI Across the Software Testing Life Cycle (STLC)

A browser-based, editable dashboard for tracking AI initiatives across the software testing lifecycle. The app visualizes testing phases, initiative status, platform/tool usage, and business impact in a single, easy-to-manage board.

![STLC Dashboard](https://img.shields.io/badge/Project-Editable%20Dashboard-0f172a?style=for-the-badge)
![STLC](https://img.shields.io/badge/Focus-AI%20in%20STLC-3b82f6?style=for-the-badge)
![HTML](https://img.shields.io/badge/Stack-HTML%20%2B%20CSS%20%2B%20JavaScript-22c55e?style=for-the-badge)

## Overview

This project is built as a single-page HTML dashboard that helps QA leaders, test architects, and delivery teams monitor how AI is being used across the STLC.

It includes:

- Six STLC phases represented as cards
- Initiative tracking by phase
- Color-coded status legend
- Overall status summary by count
- Tools/platforms in use section
- Business impact summary
- Data import/export as JSON
- Editable dashboard configuration in the browser

## Why this project

Modern testing teams often need a quick view of AI adoption across requirements, design, test planning, execution, defect management, and release readiness. This dashboard helps teams centralize and review that information without requiring a backend or database.

## Features

### Interactive dashboard
- View total initiative count at a glance
- See overall status distribution by count
- Expand each STLC phase and review its initiatives
- Click any initiative to edit it
- Add new initiatives directly from a phase card

### Customization
- Update dashboard title and subtitle
- Edit legend labels, colors, and symbols
- Adjust platform/tool names and business impact values
- Change font size for readability
- Print the dashboard or save as PDF

### Data management
- Store changes in browser local storage
- Export the dashboard configuration to JSON
- Import a previously saved JSON file
- Reset to the original bundled dataset

### UX support
- Responsive layout for desktop use
- Clean card-based design
- Lightweight implementation without framework dependencies

## Project files

- `STLC_Editable_Dashboard.html` - Main dashboard interface and application logic
- `data.json` - Default dataset used to populate the dashboard
- `README.md` - Project documentation

## How to run

1. Download or clone the repository.
2. Open `STLC_Editable_Dashboard.html` in a browser.
3. Use the gear icon in the bottom-right corner to access dashboard tools.

No installation or server setup is required for the basic version.

## How to use the dashboard

### Edit an initiative
- Click an initiative name in any phase card.
- Update the initiative ID, status, or name.
- Save the changes.

### Add a new initiative
- Click the `+ Add initiative` button in any phase card.
- Fill in the initiative details.
- Save it to the selected phase.

### Edit dashboard settings
- Click the gear icon.
- Choose `Edit Dashboard`.
- Update the title, subtitle, platform list, and impact list.

### Import/export data
- Use `Export JSON` to save the full dashboard state.
- Use `Import JSON` to restore a previously exported dashboard configuration.

## Dashboard structure

The dashboard is organized into:

- Header with title and subtitle
- Top metrics panel
- Overall status summary
- STLC phase cards
- Status summary and platform/impact sections
- Floating toolbar for actions

## Default data

The app loads default data from `data.json` when available. If the file is unavailable, it falls back to inline starter data embedded in the HTML file. This makes it easy to customize without changing the main UI logic.

## Tech stack

- HTML
- CSS
- JavaScript

## Use cases

This dashboard is suitable for:

- QA transformation programs
- AI adoption tracking in testing teams
- Release quality monitoring
- STLC maturity reviews
- Test strategy presentations

## License

This project is intended for educational, demo, and personal use.

## Future enhancements

Possible enhancements include:

- Add drag-and-drop reordering of initiatives
- Support categories and owners per initiative
- Add charts and trend summaries
- Convert to a React or Vue app
- Add authentication and database-backed persistence

If you would like, I can also help create a more advanced version of this dashboard with charts, export to PDF, and a backend-powered data store.
