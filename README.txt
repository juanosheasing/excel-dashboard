Excel Dashboard Upload Package

Files:
- index.html
- vendor/xlsx.full.min.js
- vendor/plotly-2.35.2.min.js

How to use in SharePoint:
1) Drag this entire folder into your SharePoint document library.
2) Open index.html from SharePoint.
3) Upload your Excel workbook in the page and use the slicers/treemaps.

Notes:
- This package uses local JS files (no CDN dependency).
- If SharePoint opens HTML in preview instead of as a web page, use Open in browser / Download then open, or place it in Site Assets and link directly.
- Some tenants block JavaScript in uploaded HTML. If that policy is enabled, this must be hosted as a SharePoint page (SPFx/web part) or on an approved internal web host.
