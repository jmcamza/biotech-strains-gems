# biotech-strains-gems
Genome-scale metabolic models of industrially important strains.

This repository contains genome-scale metabolic models of industrially important strains created with the tool CarveMe.

These GEMs were created based on the reference sequence of complete genomes of selected bacteria.
Strains were selected from a list of ~7942 fully sequenced genomes according to their importance an applications in biotechnology.
Strains were separated in two groups: gram-positive and gram-negative strains. Then, using the advanced options of CarveMe for each group an alternative universe was created specifying its corresponding biomass function.
Gapfilling and initialization of the models were done taking LB as a reference medium.

The purpose of this project is to analize the intrinsinc metabolic potential of each strain for the efficient production of plant natural products.
The key metabolites that represent the building blocks of the major classes of plant natural products are: HMBDP, malonyl-CoA, and chorismate for the biosynthesis of isoprenoids, polyketides, flavonoids and alkaloids.
Fluxes through the reactions involving these metabolites were analyzed in order to stablish which strains have a better potential for the biosynthesis of which types of products.


This is an ongoing project...

The ipython notebook includes a functions for the building of a customized biomass function for each strain, based on the metabolites content of each model.

Pending tasks:

- Normalize biomass function for each strain
- Perform gapfilling again
- Generate a new database of media composition that includes commonly used media for each strain.

