# avaPopeletzbach

## Event 20090407

### Changelog 
#### V0 -> V1 
* forest shp file
  * keep all polygons with height class >= 10 and merge adjacent polygons if not holes in resulting polygon
  
   -> info on tree specification, forest damage, density and height classes lost as polygons were merged 
---
#### V0
* forest shp file
  * height classes: 2-5, 5-10, 10-15, 15-20, 20-25 meters (HEIGHTCL)
  * canopy density: dense (no space between crowns), closed (crowns are in close contact), open (roughly 1/2 crown diameter distance between crowns), sparse (more than a crown diameter distance between individual crowns) (DENSITY)
  * partly forest type specification (TREESPEC)
  * forest damage (0 - not destroyed, 1 - destroyed) (FORDAM)
---

### General description 
* Type of avalanche: wet snow avalanche
* Date: 7.04.2009

### Available data
* release area shp file (releaseArea20090407.shp)
* forest shp file (forest20090407.shp)
  * forest height >= 10 m taken into account
  * all canopy density classes considered as forest (dense, closed, open, sparse)
* reference area shp file (area covered by avalanche event) (eventArea20090407.shp)
* reference deposition area shp file (area associated with avalanche deposit) (eventDepositionArea20090407.shp)
  * type is dense flow deposition 

A digital terrain model for this region can be found at: https://www.data.gv.at/.

### Data source 
Data was collected by Frank Perzl (Austrian Research Centre for Forests).
*Original Identifier Information: event 6534*
