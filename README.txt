Estimating arboreality and the effects of forest structure on detection of tropical tree-dwelling mesomammals using arboreal camera traps

Juliana Masseloux, Quy Tan Le, Jessica Burr, and Brian D. Gerber

-------------------------------------------------------------------------------

Detection history for arboreal single-season single-species occupancy models can be loaded into R using
> load(det_hist_arb_SSOM)

det_hist_arb is a list containing arboreal detection histories for each (9) arboreal species

Model list for each species was fit in R using package 'RMark" then exported into program MARK for Bayesian analyses.

Detection history for semi-arboreal multi-scale occupancy models can be loaded into R using
> load(det_hist_arb_MSOM)

det_hist_MARK is a list containing arboreal and terrestrial detection histories for each (4) semi-arboreal species

Unstandardized site-level covariates may be loaded into R using
> load(unstandardized_covariates)

Covariates were standardized in the model preparation code after removing rows (sites) from the species detection histories with all NAs

Data for arboreal species general linear mixed models can be loaded into R using 
> load(GLMM_arb)

Refer to 'Methods_workflow.pdf' for a more detailed summary of data and workflow.

