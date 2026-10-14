# SAMUH Weekly Production Plan template

This is a lightweight, no-build static dashboard generated from **only** the `WEEKWISE UNIT WISE PLAN` worksheet in the supplied Excel workbook.

## Included
- `index.html` — responsive weekly production dashboard with unit/product search, week filter, summary cards and CSV export.
- `weekly-data.json` — extracted weekly worksheet data.
- No dependencies, API keys, database or Python runtime required for hosting.

## Publish with GitHub + Vercel
1. Create a new GitHub repository (for example `samuh-weekly-production-plan`).
2. Upload both `index.html` and `weekly-data.json` to the repository root.
3. In Vercel, choose **Add New → Project**, import that repository and deploy. No build command is needed; output/root directory is `./`.
4. Test the new Vercel deployment URL before changing any existing domain settings.

## Important about your existing URL
`productioncontroltowerhalaniupdated-mu.vercel.app` is a Vercel project URL. It cannot serve two separate projects simultaneously. To use that exact URL for this new repository, you would need to move/reassign the domain from the old project to the new one in Vercel, which can cause downtime and changes what the URL serves. Keep the old project untouched until the new deployment has been checked, then move the domain only if you want this new template to replace the existing site. If you want the weekly plan as an additional tab in the original dashboard, the original app source code is needed instead.

## Data note
The workbook's weekly grand-total row shows W1 96, W2 122, W3 134, W4 127, total 479. This dashboard displays the sheet values as provided and treats blank weekly cells as zero for display.
