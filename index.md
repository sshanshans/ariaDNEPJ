---
layout: page
title: ariaDNE - A Robustly Implemented Algorithm for Dirichlet Normal Energy
description: project webpage
--- 

[Shan Shan](https://sshanshans.github.io) &emsp; &emsp; Shahar Z. Kovalsky &emsp; &emsp; Julie M. Winchester &emsp; &emsp; Doug M. Boyer &emsp; &emsp; Ingrid Daubechies

![teaser](./ARIADNE/images/teaser.jpg?raw=true)

Paper &emsp; &emsp; &emsp;  Supplementary &emsp; &emsp; &emsp; [Code](https://github.com/sshanshans/ariaDNE_code) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1465949.svg)](https://doi.org/10.5281/zenodo.1465949)

### Abstract
The *Dirichlet energy of the normal* measures how much a 3D surface bends; DNE, a discretized version for 3D meshes, is effective for biological studies of morphological surfaces. Recent studies found that the DNE algorithm is sensitive to various surface preparation procedures, raising concerns regarding comparability and objectivity when utilizing DNE in morphological research. We provide _a_ _r_obustly _i_mplemented _a_lgorithm for computing the Dirichlet normal energy (ariaDNE) on 3D meshes. We show that ariaDNE is much more stable than DNE when preparation-related mesh surface attributes such as resolution (polygon count), mesh representation (i.e., a different set of points/nodes or triangles representing the same continuous surface) and noise are varied through simulation. We also show that the effects of smoothing and boundary faces are more limited on ariaDNE than DNE. Further, ariaDNE retains the potential of DNE for biological studies, illustrated by it effectively differentiating species by dietary preferences. AriaDNE can be a useful tool to uniformly quantify shape on samples of surface meshes collected with different instruments or at different resolutions, and prepared by varying procedures. To facilitate the field to move towards this goal, the supplementary materials provide ariaDNE values for specimens used in previously published DNE analyses. Scripts for computing ariaDNE can be found by link within this manuscript.

### Bibtex

### License
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <https://www.gnu.org/licenses/>.

### ariaDNE for previously published DNE analysis
