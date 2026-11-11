# Migration Assurance Workbench — hosted build

Static build of the BI Migration & Assurance Workbench.

- `/` — standalone web app (runs on its built-in synthetic sample data: a fictional SaaS company)
- `/extension/` — Tableau dashboard extension (reads the workbook's own datasources via the Tableau Extensions API)

All data stays in the viewer's browser. Generated build output; source is maintained separately.
