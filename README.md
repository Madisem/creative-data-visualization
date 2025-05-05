# creative-data-visualization

When Genetic geography meets real-world geography

My goal/idea is Overlaying PCA results on a world map to show the correlation between genetic distances and geographical origins.

Creative-nontraditional-artistic output of the PCA <- How genetic world will look like?

Dataset is my own work from data replication project, which directly related to my field of study (population genetic analyses).

In population genetics, PCA (Principal Component Analysis) is commonly used to visualize genetic distances between populations. Often, the first two PCs reflect geography—e.g., PC1 follows a west–east cline, and PC2 a north–south cline. However, traditional PCA plots do not visually show how much closely the genetic relationships align with actual geography.

In this project, I developed a visualization pipeline that: 

1) Starts from traditional PCA using .evec files (from SMARTPCA)

2) Colors populations by country

3) Builds polygons around country-level genetic clusters

4) Extracts real-world country map shapes

5) Scales and warps each map to match its genetic shape in PCA space

6) Visually overlays these country maps in genetic space.

7) The final result is a warped genetic map of the world, shaped by PCA and filled with real country map and looks like geographic-genetic hybrid (shows which country interacts with eachother).

All final plots are saved in the output/ directory with high resolution. (because in quarto html they are not visually good, need to be enlarged - or better look shiny app)
