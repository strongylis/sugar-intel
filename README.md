# sugar-intel

**Open Brazilian Sugar & Ethanol Market Data** — interactive charts,
downloadable datasets and primary sources for the sugar-energy community.
Free for all.

**Live site:** https://igorstrongylis.github.io/sugar-intel/ *(GitHub Pages)*

## What's inside

| Section | Panels |
|---|---|
| Overview | KPI strip — spot, futures, FX, pump parity, ENSO |
| Climate | INMET COSMO-7 precipitation forecast · ENSO / ONI (NOAA) |
| Sugar | ICE #11 front + forward curve · CFTC positioning · CEPEA/ESALQ crystal (crop-year) · USDA world balance |
| Ethanol | Hydrous FOB Ribeirão (crop-year + B3 futures) · B3 forward curve · CEPEA SP/GO · Pump parity by state (ANP) · Otto-cycle sales · ABICOM import-parity gap |
| Harvest | CONAB official crop survey |
| Macro | Brent · WTI · USD/BRL PTAX · weekly commodity tape |

Every panel ships with a collapsible data table, a one-click **CSV download**
(`data/*.csv`) and a link to the **primary source** (CEPEA, ANP, UNICA, CONAB,
USDA, CFTC, NOAA, INMET, ABICOM, B3, BCB, ICE).

## How it works

The site is 100% static — a Python exporter reads a consolidated workbook,
renders Plotly charts and writes `index.html` + CSVs. No server, no tracking.

Data is refreshed periodically by re-running the exporter and pushing.

## License

Code: MIT. Data belongs to the respective primary sources, redistributed
here as CSV for convenience with attribution.

— developed by [Igor Strongylis](https://www.linkedin.com/in/igorstrongylis/)
