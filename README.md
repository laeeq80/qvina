# Multi-QuickVina #

Multi-QuickVina is modified version of Autodock QuickVina 2 so you can dock multiple ligands at a time which was not 
possible by the original Autodock Vina and Autodock QuickVina 2. Now you won't need to use vina_split anymore to split the ligands 
as single ligands.

AutoDock Vina is an open-source program for doing molecular docking. It was been designed and implemented by Dr. Oleg Trott in the Molecular Graphics Lab at The Scripps Research Institute. 

# Build
Install Boost and build multi-qvina with Boost using following commands

`make`

`makedepend`

# Execution

`./vina --receptor receptor.pdbqt --config conf.txt < conformers.pdbqt`


# QuickVina 2
Accurately speed up AutoDock Vina, the famous molecular docking tool.

This is the source code repository and the temporary website until I release a new version and build new nice website.

Quick Vina 2 is a fast and accurate molecular docking tool, attained at accurately accelerating AutoDock Vina. It was tested against 195 protein–ligand complexes that compose the core set of the 2014 release of the PDBbind using default exhaustiveness level of 8, QVina 2 successfully attained up to 20.49-fold acceleration over Vina. The Pearson’s correlation coefficient between Vina’s QVina 2’s binding energy was 0.967 for the first predicted mode and 0.911 for the sum of all predicted modes.

It is also witnessed that QVina 2 is more accurate than GOLD 5.2 and is only slightly less accurate than Dock 6.6. This shows that QVina 2 has paved the way for some high-throughput and sufficiently accurate virtual screening of molecular libraries. This in turn brings great value to the fragment-based computer-aided drug design.

to cite Quick Vina 2 please cite:

Amr Alhossary, Stephanus Daniel Handoko, Yuguang Mu, and Chee-Keong Kwoh. "Fast, Accurate, and Reliable Molecular Docking with QuickVina 2". Bioinformatics (2015) 31 (13): 2214-2216. doi:10.1093/bioinformatics/btv082
