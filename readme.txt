this is Exploratory data analysis of the Air Quality dataset
____________________________________________________________
# Summary
# - 500 rows, 10 numeric columns, no missing values in describe().
# - NOx, NO2 and SO2 have small negative minimums, which shouldn't
#   happen for concentrations. Decide whether to clip them at 0.
# - PM2.5, PM10, SO2 and VOCs have mean above median, so right skew.
#   NOx is the opposite and very spread out (0 to ~226).
# - Scales are very different (CO2 in the hundreds, CH4 around 2),
#   so scaling is needed before any distance-based model.
# - Temperature is symmetric and compact, a reasonable target.
# - Correlations / outliers: fill in after running the cells above.