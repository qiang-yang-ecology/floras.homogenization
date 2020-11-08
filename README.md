This repository includes the core data and R codes for the manuscript: Yang et al. Global homogenization of regional floras.


Files in this repository include:

The pdf document includes the R codes for the main analysis of the project. 

df.average.Rdata: the average extent of taxonomic and phylogenetic homogenization of each region to other regions.

df.average.similarity.Rdata: the average taxonomic and phylogenetic similarity of each region to other regions.

df.region.social.economic.Rdata: the aggregated human-activity data for each region.

df.regional.coredata.Rdata: including the extent of homogenization, geographic distance, climatic dissimilarity, and administrative relationship between regions.

df.tidy.pairwise.similarity.and.homogenization.Rdata: including the extent of homogenization and similarity between regions.

df_island.Rdata: indicating whether one region is an island or mainland region.

gams.LL.Rdata: results of the generalized additive models.

new.data.explanatory.variable.Rdata: a new dataset of the explanatory variables to make predictions.

small.island.centroids.Rdata: sf data including the coordinates of the centroids of the small islands (homogenization values included).

small.island.centroids.similarity.Rdata: sf data including the coordinates of the centroids of the small islands (similarity values included).

sp.centroids.combined.regions.Rdata: Spatial points including the coordinate of the centroid of each region.

sp.combined.regions.Rdata: Spatial polygons of the regions.

wrld.regional.level.Rdata: sf data of the regions including the average extent of homogenization of each region.

wrld.regional.level.similarity.Rdata: sf data of the regions including the average similarity of each region to other regions.

wrld.sf.Rdata: sf data of the global regions (including regions that are not included in the analysis).

full.phylo.tre: the phylogeny of seed plants with accepted names in The Plant List.

df.species.matching.and.addition.Rdata: including the information of the name of the taxa in the Plant List, and how they are matched or added to the ALLMB  phylogeny constructed by Smith and Brown 2018, and the corresponding tip.label of each taxon in the phylogeny.
