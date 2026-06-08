# Pazcare Pulse — Support Intelligence Dashboard

A live analytics dashboard for the Pazcare support desk. It turns the ticket
export (Insurance & Non-Insurance) into KPIs, charts, agent scorecards, SLA and
CSAT analysis, a searchable data table, and plain-English insights — all
calculated live from the data.

**🔗 Live dashboard:** https://ayshalubna.github.io/pazcare-pulse/

## Features
- **Command Center** — headline KPIs with month-over-month change
- **Insights** — plain-English takeaways and recommended actions
- **Insurance & Non-Insurance desks** — per-segment deep dives
- **SLA & Response** — breach trends and compliance by agent/category
- **Team Performance** — full agent scorecard (resolution, SLA, CSAT)
- **Voice of Customer** — satisfaction and rating analysis
- **Data Explorer** — search, sort and export every ticket to CSV
- **Integrity Check** — reconciles every number against the source file
- **Power BI–style filtering** — month / segment / agent + click-to-focus
- **One-click data updates** — upload a new month right in the dashboard

## How to use
Open the live link above. To load new data, click **Update Data** and upload the
latest ticket Excel (choose *Add to current* to append a new month, or *Replace*).

## Built with
HTML, CSS and JavaScript (single self-contained file), with **Chart.js** for the
charts and **SheetJS** for reading Excel — no server or database required.

## Notes
Internal Pazcare tool. All metrics are computed in the browser; no data is sent
to any external server.
