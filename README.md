# AI Across the Software Testing Life Cycle (STLC)

A lightweight, editable dashboard for tracking AI initiatives across the Software Testing Life Cycle. This project presents a visual STLC board where each testing phase can show initiative progress, status categories, tools/platforms in use, and business impact.

## Overview

The dashboard is built as a single-page HTML application and allows users to:

- View AI initiatives organized by STLC phase
- Track initiative status using color-coded legend categories
- Add, edit, and delete initiatives
- Customize dashboard title and subtitle
- Update platforms in use and business impact sections
- Import/export dashboard data as JSON
- Adjust font size and print to PDF
- Reset the dashboard to the original dataset

## Files

- `STLC_Editable_Dashboard.html` – Main dashboard UI and logic
- `data.json` – Default dataset used to populate the dashboard
- `README.md` – Project documentation

## How to use

1. Open `STLC_Editable_Dashboard.html` in a browser.
2. Use the gear icon in the bottom-right corner to access dashboard tools.
3. Edit task entries, legend labels, or dashboard metadata as needed.
4. Export or import JSON if you want to save or share a custom configuration.

## Dashboard sections

The dashboard includes:

- Total AI initiatives count
- Overall status summary by count
- STLC phase cards with initiative tasks
- Status legend with clickable editing
- Tools/platforms used
- Business impact summary

## Features

### Editable workflow
- Add initiatives to any lifecycle phase
- Update initiative ID and status
- Edit initiative names directly from the UI

### Customization
- Rename dashboard title and subtitle
- Modify status legend labels, colors, and symbols
- Set platform and business impact values as line-separated lists

### Data management
- Save data in browser local storage
- Export dashboard configuration to JSON
- Import previously exported JSON files
- Reset the dashboard to the bundled default data

### Presentation support
- Resize text for readability
- Print or save the dashboard as PDF

## Example data source

The project loads its initial configuration from `data.json` if available, and otherwise falls back to inline starter data. This makes the dashboard easy to customize without changing the main HTML file.

## Tech stack

- HTML
- CSS
- JavaScript

## Project purpose

This application is designed for QA leaders, test architects, and delivery teams who want a quick, visual view of where AI is being applied across the software testing lifecycle and how those initiatives are progressing.

## License

This project is provided for educational and demonstration purposes.

If you want, I can also help turn this into a more polished GitHub README with badges, screenshots, and deployment instructions.
