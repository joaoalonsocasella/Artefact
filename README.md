Answer to Problem 1.A.:
Metric	Granularity	Unit	Explanation
Sales history	Store × SKU × day	Units sold	Main driver of demand; captures seasonality and consumption peaks.
Inventory levels	Store × SKU × day	Units available	Shows available stock and shipments; needed to predict depletion.
Replenishment orders	Order-level timestamps	Days (lead time)	Lead time variability explains gaps between supply and demand.
Promotions & campaigns	SKU × store × start/end	Binary / % discount	Strongly affect demand and risk of stockouts.
Prices	Store × SKU × day	Currency (e.g., R$)	Price changes influence demand volumes.
Store capacity	Per store	Units (max capacity)	Limited storage/refrigeration increases vulnerability to stockouts.
Shrinkage/spoilage	Store × SKU × day	Units lost	Losses reduce effective inventory, raising risk of stockouts.
Weather	Daily, per store location	°C / mm rainfall	Warmer weather boosts demand, rainfall reduces it.
Local events & holidays	Date × region/store	Categorical (event)	Special events create demand spikes.
Socioeconomic factors	Regional (city/area)	Index / categorical	Explains structural differences in baseline demand between stores.