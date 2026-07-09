# Houston Port Freight Flows — Regional Picture

An animated flow map of goods movement through the Houston port complex:

- **Ships arriving** — 1,868 real vessel arrivals (Apr–Jun 2025) from USCG AIS tracking (NOAA MarineCadastre)
- **Port freight by truck** — modeled import/export truck flows (FHWA FAF 5.7.1, 2024) routed from five terminal gate clusters (Bayport, Barbours Cut, Turning Basin, Jacintoport, channel bulk) over alternate k-shortest paths, with congestion-aware route choice from observed TxDOT volumes; corridor and gateway splits calibrated against the TxDOT Houston District Truck Mobility Study (StreetLight/ATRI GPS); anchored to USACE Waterborne Commerce port tonnage
- **All highway freight** — total truck tonnage by corridor (FAF5 highway assignment)
- **Everyday car traffic** — TxDOT Roadway Inventory daily volumes, Houston District

**≈31% of the Houston region's inter-zonal truck tonnage moves through the port complex.**

**[View the live map](https://bschmitz-builds.github.io/houston-freight-flows/)**

Built with deck.gl · basemap © OpenStreetMap contributors, © CARTO.
Data: BTS/FHWA FAF5 · USACE WCSC · TxDOT · NOAA MarineCadastre (all public sources).
