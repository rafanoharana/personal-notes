# Remote Sensing

**Summary**: Notes on satellite and aerial Earth observation, including imagery, geospatial foundation models and Earth embeddings.
**Last updated**: 2026-11-18

---

- [Stop using LST to quantify heat hazard (LinkedIn post by TC Chakraborty)](https://www.linkedin.com/feed/update/urn:li:activity:7478690057026207745/): Argues that satellite land surface temperature (LST) is the "skin" temperature of roofs, canopies and asphalt, not the air temperature people feel. LST maps exaggerate heat hazard, overstate how much trees cool the air in cities ([[Urban_Planning]]) and erode trust in heat science ([[Climate_Change]]). Commenters noted LST is still useful where data is scarce if its limits are disclosed. *Keywords*: land surface temperature, air temperature, extreme heat, urban heat, science communication
- [The Technical Debt of Earth Embedding Products](https://cloudnativegeo.org/blog/2026/02/the-technical-debt-of-earth-embedding-products/): Isaac Corley (CNG, Feb 2026) compares Earth [[Embeddings]] products (Clay, Major TOM, AlphaEarth, Tessera, Presto and others) by resolution, size, license and storage cost. He argues that distribution, not model quality, is the bottleneck and calls for cloud-native formats such as GeoParquet, COG and Zarr (see [[Data]]). *Keywords*: earth embeddings, geospatial foundation models, GeoParquet, Zarr, interoperability, quantization
