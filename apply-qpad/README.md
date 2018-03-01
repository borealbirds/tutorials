Apply QPAD to Generate Offset models
=====================

Preamble about QPAD and what it does. 

## List of Necessary Covariates

### Removal Model component (singing rate)

* JDAY: Julian day / 365
* JDAY2: JDAY^2
* TSSR: time since sunrise (requires time zone)
* TSSR2: TSSR^2
* DSLS: days since local spring. (Julian date – day of first spring) / 365
* DSLS2: DSLS^2

### Distance Estimation component (effective detection radius)

* TREE: percent tree cover
* LCC2OpenWet: Indicator variable - if habitat is open or wet (from LCC2)
* LCC4Conif: Indicator variable – if habitat is coniferous (from LCC4)
* LCC4Open: Indicator variable – if habitat is open (from LCC4)
* LCC4Wet: Indicator variable – if habitat is wet (from LCC4)
* MAXDIS: maximum distance band for point count in m, divided by 100

