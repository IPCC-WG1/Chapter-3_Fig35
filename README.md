
SAM INDICES IN THE LAST MILLENIUM
=================================
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6787289.svg)](https://doi.org/10.5281/zenodo.6787289)

Figure number: Figure 3.35
From the IPCC Working Group I Contribution to the Sixth Assessment Report: Chapter 3

![Figure 3.35](ar6_wg1_chap3_figure3_35_sam_millennium.png?raw=true)


Description:
------------
Southern Annular Mode (SAM) indices in the last millennium. (a) Annual SAM 
reconstructions by Abram et al. (2014) and Dätwyler et al. (2018). (b) The 
annual-mean SAM index defined by Gong and Wang (1999) in CMIP5 and CMIP6 
Last Millennium simulations extended by historical simulations. All indices 
are normalized with respect to 1961-1990 means and standard deviations. Thin 
lines and thick lines show 7-year and 70-year moving averages, respectively. 


Author list:
------------
- Kosaka, Y.: University of Tokyo, Japan; ykosaka@atmos.rcast.u-tokyo.ac.jp
- Kazeroni, R.: DLR, Germany


ESMValTool Branch:
------------------
- ESMValTool-AR6-OriginalCode-FinalFigures: [ar6_chapter_3](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/tree/ar6_chapter_3)


ESMValCore Branch:
------------------
- ESMValCore-AR6-OriginalCode-FinalFigures: [fix_cmip6_models_newcore](https://github.com/ipcc-wgi/ESMValCore-AR6-OriginalCode-FinalFigures/tree/fix_cmip6_models_newcore)


Recipe & diagnostics:
---------------------
Recipe used: [recipes/ipccwg1ar6ch3/recipe_ar6ch3_sam_millennium.yml](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/ar6_chapter_3/esmvaltool/recipes/ipccwg1ar6ch3/recipe_ar6ch3_sam_millennium.yml)

Diagnostic used: [diag_scripts/ar6ch3_sam_millennium/draw_samindex_millennium.ncl](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/ar6_chapter_3/esmvaltool/diag_scripts/ar6ch3_sam_millennium/draw_samindex_millennium.ncl)


Expected image path:
--------------------
- recipe_ar6ch3_sam_millennium_YYYYMMDD_HHMMSS/plots/sam_index_millenium/draw_samindex_millenium/sam_millenium.pdf


Software description:
---------------------
- ESMValTool environment file: [IPCC_environments/ar6_newcore_remi_conda_environment.yml](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/main/IPCC_environments/ar6_newcore_remi_conda_environment.yml)
- pip file: [IPCC_environments/ar6_newcore_remi_pip_environment.txt](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/main/IPCC_environments/ar6_newcore_remi_pip_environment.txt)


Hardware description:
---------------------
Machine used: Mistral
