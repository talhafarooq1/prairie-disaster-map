# Canadian Prairies Disaster Events Map, 1961–2025

Interactive web map of **133,259 disaster events** across **Alberta, Saskatchewan and Manitoba**, compiled exclusively from official sources for a disaster-calibrated Actuaries Climate Index (DC-ACI) research project.

**Live map:** open `index.html` via GitHub Pages (Settings → Pages → Deploy from branch → main / root).

## What is mapped

| Layer | Events | Source(s) |
|---|---|---|
| Wildfire density (all sizes) | 126,792 | CNFDB / National Fire Database point data |
| Wildfire ≥200 ha (points) | 8,054 | CNFDB / NFDB |
| Hail | 4,010 | Integrated Canadian Hail Database (2005–2022), Northern Hail Project (2022–2025) |
| Tornado | 2,149 | ECCC verified tornado database (1980–2009), Northern Tornadoes Project (2010–2025) |
| Flood | 83 | Canadian Disaster Database, NRCan Historical Flood Events |
| Drought | 35 | Canadian Disaster Database (documented events) |
| Winter storm | 14 | Canadian Disaster Database |
| Severe storm (other) | 168 | Canadian Disaster Database |

Click any point for full event details: date and date precision, province/municipality, source, fatalities/injuries/evacuees, area burned, EF rating, hail size, insured and economic losses (nominal CAD), significant-disaster flag and duplicate-resolution confidence.

## Notes

- 87 events have province-level locations only in the official record and are deliberately **not** placed on the map (no fabricated centroids); they are listed in `events_without_coordinates.csv` in the project archive.
- Monetary values are nominal (not inflation-adjusted), kept in separate insured / economic / assistance fields.
- The map requires an internet connection to load basemap tiles (OpenStreetMap / Esri).
- Reference period for the underlying study: 1961–1990.

## Citation

If you use this map, please cite the Prairie DC-ACI research project and the underlying official data providers: Public Safety Canada (Canadian Disaster Database), Natural Resources Canada (CNFDB/NFDB, Historical Flood Events), Environment and Climate Change Canada, and the Northern Tornadoes / Northern Hail Projects (Western University).
