# ssj-ucd-priestley-taylor
UC Davis Landsat and MODIS based Priestley Taylor ET method.

Lead: Yufang Jin, UC Davis

Uses the optimized semi-empirical Priestley-Taylor (PT) equations to estimate ET; net radiation, ground heat flux, and the PT coefficients are derived from MODIS and Landsat satellite data.

## [Results](./results)

This method will provide daily estimates of ET, G, and H based on MODIS Data. The MODIS data products will be sharpened using periodic Landsat Imagery.  In addition to ET, the daily products will include


Data | Date | Daily | Monthly
---  | --- | --- | ---
ET   | [l] | [d] | [m]
H    | [l] | [d] | [m]
G    | [l] | [d] | [m]
Ts   | [l] | [d] | [m]
Rlo  | [l] | [d] | [m]
Rli  | [l] | [d] | [m]


The following table describes some of the required data from the other sources.

Data | Date | Daily | Monthly
--------- | --- | --- | ---
ETo       | [W] | [W] | [W]
Z         | [O] | [O] | [O]
LandCover | [N] | [N] | [N]



[O]: https://github.com/ssj-delta-cu/ssj-overview
[W]: https://github.com/ssj-delta-cu/ssj-weather/cimis
[N]: https://github.com/ssj-delta-cu/ssj-nasa-landcover
[l]: ./results/dates
[d]: ./results/daily
[m]: ./results/monthly
