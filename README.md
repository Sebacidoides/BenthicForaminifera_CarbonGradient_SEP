# Benthic foraminifera Carbon Gradient in the South East Pacific

## Repository's Overview

This repository contains data and the scripts related to the article "Carbon stable isotopes of deep infaunal and epifaunal benthic foraminifera in the Southeast Pacific: lessons from shallow-water samples for a paleoxygenation proxy" (in preparation)

## Research's Abstract

The difference between the carbon isotopic composition between the calcareous test δ13C of Cibicidoides wuellerstorfi (δ<sup>13</sup>C<sub>Cw</sub>) and Globobulimina species (δ<sup>13</sup>C<sub>Gb</sub>) is directly related to the dissolved oxygen concentration in the bottom water (BWDO). This difference is known as the carbon gradient proxy, which can reconstruct bottom water oxygenation over the geological record. Calibrations for the proxy have been performed globally, including the Atlantic, North, and Equatorial Pacific oceans and the Arabian and Mediterranean seas, but lacking in the Southeast Pacific (SEP). Significant oxygen gradients characterize the SEP, which hosts one of the most important oxygen depleted zones in the world: the SEP-ODZ. We calibrated the carbon gradient proxy in the SEP using carbon isotope analyses of C. wuellerstorfi and Globobulimina species from 79 surface sediment samples covering from 4°N to 50°S and 124 to 3,960 m water depth. We complemented the Δδ<sup>13</sup>C<sub>Cw-Gb</sub> with the difference between the bottom water dissolved inorganic carbon δ<sup>13</sup>C<sub>DIC</sub> and Globobulimina δ<sup>13</sup>CGb (Δδ<sup>13</sup>C<sub>DIC-Gb</sub>). Then, we compared the Δδ<sup>13</sup>C<sub>Cw-Gb</sub> and Δδ<sup>13</sup>C<sub>DIC-Gb</sub> to BWDO at different water depths, assessing the effects of environmental factors like bottom water nitrate concentration (BWNO<sub>3</sub><sup>-</sup>), carbonate ion concentration (BWCO<sub>3</sub>2<sup>-</sup>), pH, and ocean net primary productivity. Cibicidoides wuellerstorfi δ13CCw is affected by BWCO<sub>3</sub><sup>2-</sup> and pH above 1,000 m, and primarily above 500 m. For Globobulimina species, BWNO<sub>3</sub><sup>-</sup> seems to impact their δ<sup>13</sup>C<sub>Gb</sub> above 500 m, while below 500 m, BWDO is the main driver. Consequently, we identified two proxies: one for depths below 1,000 m (R<sup>2</sup> = 0.74), and another for depths 500–1,000 m (R<sup>2</sup> = 0.67). Higher reliability was found at 500–1,000 m if only G. affinis is used (R<sup>2</sup> = 0.72). The calibrated proxies extend the applicability of benthic foraminiferal δ<sup>13</sup>C to the SEP, providing a region-specific tool with worldwide potential for reconstructing past oceanic oxygenation, with an error of around ±14 µmol kg<sup>-1</sup> for the reconstructed BWDO values.

## Authors

- Sebastián Garrido <sup>1,2</sup>
- Babette Hoogakker <sup>1</sup>
- Dharma Reyes-Macaya <sup>1,2,3</sup>
- Magali Schweizer <sup>4</sup>
- María Yolanda Núñez <sup>5</sup>
- Iván Hernández-Almeida <sup>6</sup>
- Jorge Cardich <sup>7,8</sup>
- Eugenia M. Gayo <sup>2,9</sup>
- Dierk Hebbeln <sup>3</sup>
- Melanie Leng <sup>10</sup>
- Kotryna Savickaite <sup>10</sup>

Affiliations:

<sup>1</sup> Lyell Centre, Heriot-Watt University, Edinburgh, UK

<sup>2</sup> ANID - Millennium Science Initiative Program Nucleo Milenio UPWELL, La Serena, Chile

<sup>3</sup> MARUM – Center for Marine Environmental Sciences, University of Bremen, Bremen, Germany

<sup>4</sup> Université d'Angers, Nantes Université, Le Mans Université, CNRS, Laboratoire de Planétologie et Géosciences, LPG UMR 6112, Angers, France 

<sup>5</sup> Escuela de Diseño, Pontificia Universidad Católica de Chile, Santiago, Chile

<sup>6</sup> PAGES - University of Bern, Bern, Switzerland

<sup>7</sup> Universidad Peruana Cayetano Heredia (UPCH), Lima, Perú

<sup>8</sup> J’EAI-CHARISMA (UMNG-Colombia; UCM-Chile; UCH-Chile; UPCH-Peru; IGM-Peru; IRD-France)

<sup>9</sup> Departamento de Geografía, Universidad de Chile, Santiago, Chile

<sup>10</sup> Stable Isotope Facility – Centre for Environmental Geochemistry, British Geological Survey, Keyworth, UK


## Research's Data and Methods

### Samples
- Our data comes from the Southeast Pacific between 4°N and 50°S along the continental margin of Chile and Peru, at depths ranging from 124 to 3,390 m. 
- Sampling methods included Multicorer, Petersen grab, and gravity core through the cruises (SONNE 156, SONNE 211, SONNE 161, Meteor 92, USNS Eltanin).

### Specimens and Stable Isotope analyses
- Cibicidoides wuellerstorfi and Globobulimina were picked from the samples and analyzed at the Keyworth BGS's Stable Isotope laboratories.
- Additional stable isotope measurements were sourced from Garrido et al. (in review), Graham et al. (1981), and Reyes-Macaya et al. (in preparation).
- The dataset that includes all the stable isotope Analysis is in this repository under the name "Stable Isotope Dataset SEP Carbon Gradient" in .csv format. This is the file you will use in the Python code (Jupyter Notebook).

### Data Analysis
- The scripts to perform the statistical analysis of our stable isotope data are in this repository under the name "Carbon Gradient Analysis.ipynb" (Jupyter Notebook), when using the file "Stable Isotope Dataset SEP Carbon Gradient.csv", be aware that this must be in the same environment (folder) than the code file. 
- Regression Analysis was performed to find the best fit between the carbon isotopic composition difference between C. wuellerstorfi and Globobulimina species and bottom water dissolved oxygen concentrations (BWDO).
- Principal component analysis (PCA) and Spearman heatmaps were performed.  

## Declaration of generative AI and AI-assisted technologies 

### Declaration of generative AI and AI-assisted technologies in the writing process
- During the preparation of this work, the author(s) used Grammarly and ChatGPT to improve language and grammar. After using this tool/service, the author(s) reviewed and edited the content as needed and take(s) full responsibility for the publication's content.  
### Declaration of generative AI and AI-assisted technologies in the code preparation process
- During the preparation of this work, the author(s) used ChatGPT Model 4 and Model 4o to assist, check, and improve code writing. After using this tool/service, the author(s) reviewed and edited the content as needed and take(s) full responsibility for the publication's content.
## References

Garrido, S., Hoogakker, B., Richirt, J., Reyes-Macaya, D., Hernández-Almeida, I., Cardich, J., Castillo-Bruna, A., Fouet, M. P. A., Gayo, E. M., Hebbeln, D., Farías, L., and Jorissen, F.: A species-specific approach to benthic foraminifera pore patterns as a paleoxygenation proxy in the Southeast Pacific (in review), Paleoceanography and Paleoclimatology.

Graham, D. W., Corliss, B. H., Bender, M. L., and Keigwin, L. D.: Carbon and oxygen isotopic disequilibria of recent deep-sea benthic foraminifera, Mar Micropaleontol, 6, 483–497, https://doi.org/10.1016/0377-8398(81)90018-9, 1981.

Reyes-Macaya, D., Hoogakker, B., Garrido, S., Paoloni, T., Hebbeln, D., Mohtadi, M., Kuh-ner, H., MartínezFontaine, C., Michel, E., Tapia, R., Martínez-Méndez, Davis, C., Bird, C., Glock, N., Krause, S., Erdem, Z., Aguilera, V., Gayo, E., McCorkle, D. C., Holder, A., Santamaria, P., Troncoso-Ojeda, R., De Pol Holz, R., Cardich, J., Vargas, C. A., Marchant, M., Tavera, L., Floras, E., Schmiedl, G., Thomsen, E., Yokoyama, Y., Muñoz, P., Lückge, A., Castillo-Bruna, A., Ingle, J., and Hromic, T.: Carbon and oxygen isotopes in modern Southeast Pacific Benthic Foraminifera: Paleoceanographic implications (in preparation), Biogeosciences.
