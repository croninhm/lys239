# Human MDH2
# Uniprot ID: P40926
# Variation: Acetylation of K239


## Lysine acetylation of MDH2 has been investigated in previous work which
demonstrated a decrease in catalytic activity of the protein following
the modification. Lysine 239 was located as a post translation
modification site on malate dehydrogenase 2. No previous literature has
described acetylation of this specific modification site.

# Comparison of MDH2 models and acetyl modified MDH2

1. Alignment of unmodified MDH2 (blue), MDH2 with acetylK 239 (red), and K239Q (green)
![Alignment of unmodified MDH2, MDH2 with acetylK 239, and K239Q](images/superimposed.png)

2. Modification site alignment within MDH2
![Modification site alignment within MDH2](images/alignment.png)

The modification site is not near any key sites, and cannot make ionic
or hydrogen bonds with adjacent amino acids due to the direction the
side chain protrudes.

## Effect of the sequence variant and PTM on MDH dynamics

1. The RMSD from MD simulations of unmodified MDH2 and MDH2K239Q was 1.11
Å. Unmodified MDH2 is shown in blue while the acetyl form is shown in purple. 
![Alignment of unmodified MDH2 and MDH2K239Q](images/unmodified_and_PTM.png)

2. After the MD simulation the general protein structures and key sites remain unaffected. The acetyl variant showed an extra hydrogen bond in the active site but this proved to have no effect on protein dynamics and the active site pKa.
![Modification site alignment of unmodified MDH2 and MDH2K239Q](images/mod_site_align.png)

3. After the MD simulation, protein dynamics were described by root mean square fluctuation (RMSF) and the values were compared. The RMSF plot shows no variation between the unmodified (blue) and acetyl variant (purple). The vertical line indicates the end of one subunit.
![RMSF plot of unmodified and acetyl variant MDH2](images/images/RMSF_git.png.png)

4. Generally the modification had no effect on the pKa of histidine in the active site. The pKa remains stable over the course of the simulation in both variants. Very few outliers in pKa are visible.
![pKa trajectory of active site histidine in unmodified and acetyl variant](images/pKa_traj_git.png)


## Comparison of the mimic and the authentic PTM

Comparison of the mimic and the authentic PTM The RMSD of K239Q and
acetylK239 MDH2 was 0.59 Å. The overall structures are similar with no
major differences in structure or position. The only difference is an
extra hydrogen bond at the active site histidine, which proved to have
no effect on active site function.

![Alignment of K239Q and acetylK239 MDH2](images/PTM_mimic_git.png)

### Colab notebook links

(data/Colab_1/Unmodified/Unmodified.ipynb)
(data/Colab_1/PTM/MIMIC_Colab_Step_1.ipynb)
(data/Colab_2/Unmodified/Unmodified_step_2.ipynb)
(data/Colab_2/PTM/MIMIC_Colab_Step_2.ipynb)

## Authors

Harrison M. Cronin

## Deposition Date

12/6/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

Jumper, J.; Evans, R.; Pritzel, A.; Green, T.; Figurnov, M.; Ronneberger, O.; Tunyasuvunakool, K.; Bates, R.; Žídek, A.; Potapenko, A.; Bridgland, A.; Meyer, C.; Kohl, S. A. A.; Ballard, A. J.; Cowie, A.; Romera-Paredes, B.; Nikolov, S.; Jain, R.; Adler, J.; Back, T. Highly Accurate Protein Structure Prediction with AlphaFold. Nature 2021, 596, 583–589. ![10.1038](https://doi.org/10.1038/s41586-021-03819-2)

Venkat, Sumana, et al. “Studying the Lysine Acetylation of Malate Dehydrogenase.” Journal of Molecular Biology, vol. 429, no. 9, May 2017, pp. 1396–405. PubMed Central ![10.1016](https://doi.org/10.1016/j.jmb.2017.03.027)
