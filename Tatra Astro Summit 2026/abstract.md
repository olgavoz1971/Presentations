#  A Web-Based Workflow for Variable-Star Light Curves: Exploring and Processing TESS Data
**Authors:** **Olga Vozyakova** (Presenter), Co-Authors: V. Marsakova, M. Kamenec
**Conference:** Tatra Astro Summit 2026, Stará Lesná, Slovakia
**Date:** 5-9 October 2026

---

### Abstract
We present a web-based workflow for variable-star light curves, the part related to the TESS data. This application is part of a multipage web portal designed to provide a quick and user-friendly path from data discovery and retrieval through light-curve preparation and visualisation to subsequent scientific analysis. 

The application uses the Lightkurve package for the underlying data handling. The application allows an easy way to discover TESS data, both ready-made light curves prepared by pipelines and FFI/TPF cutouts for independent lightcurve extraction.

It’s known that instrumental and data processing effects can produce features that resemble genuine stellar variability. It is especially important in variable star extreme timing, where the lightcurve distortion due to rapid background change could affect timing and the resulting O-C diagram, potentially leading to a spurious astrophysical interpretation.

The application is equipped with visualisation tools that let users inspect not only the resulting light curves, but also the background subtracted by each pipeline and the different flux products available (SAP, PDCSAP, KSPSAP, etc.), helping choose and clean data more consciously. 

The application requires no local installation, and users can export and import light curves at any stage using standard Virtual Observatory-compliant formats.
