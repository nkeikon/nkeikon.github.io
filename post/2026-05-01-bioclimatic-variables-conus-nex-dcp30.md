---
title: "New release: High-resolution bioclimatic variables for CONUS"
date: 2026-05-01
date_note: "Estimated from LinkedIn's relative timestamp ('2mo'); confirm exact date before publishing"
original: https://www.linkedin.com/posts/keiko-nomura-0231891_new-release-high-resolution-bioclimatic-activity-7455013060521615360-zsY6
---

New release: High-resolution bioclimatic variables for the conterminous USA (CONUS), derived from NASA NEX-DCP30-CMIP6 (links in the comment).

The USDA Forest Service Research Data Archive has just published a new bioclim dataset (Kim et al., 2026) derived from NEX-DCP30-CMIP6, the 30 arc-second downscaled climate projections our team developed (Thrasher et al., 2024). Bioclim variables turn raw temperature and precipitation into metrics that are more relevant to species, such as seasonality, extremes, and quarterly means. They're commonly used as inputs for species distribution modeling, but also support invasive species risk assessment, conservation planning, forestry research, and more.

What's in it:
- 20 bioclimatic variables capturing monthly, seasonal, and annual climate metrics
- 30 GCMs, two emissions scenarios (SSP2-4.5 and SSP5-8.5)
- Three time periods: historical (1970-1999), mid-century (2035-2064), late-century (2070-2099)
- PRISM-derived bioclim for the historical period as a reference baseline
- Water-year adjusted, packaged as multi-band TIFs

A few things make this dataset particularly well-suited for ecological modeling in the US: It's bias-corrected against PRISM, the high fidelity gridded climate record for CONUS. The underlying DCP30-CMIP6 archive uses daily BCSD downscaling across 30 CMIP6 GCMs and the latest SSP scenarios, preserving the frequency of extreme events better within each scenario rather than just shifting monthly means. The 30-GCM ensemble also gives users a much richer basis for quantifying model uncertainty in projections.

Data access and full citation: Kim, J.B. et al. 2026. Bioclimatic variables of conterminous USA from NASA NEX-DCP30-CMIP6 climate projections. Forest Service Research Data Archive.
