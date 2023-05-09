This creates the file containing ecosystem experiments data that is used for analysis of Peng et al. (in prep., Chapter 2 of Yunke Peng's PhD).

Script: `submission/data_processing.R`, `submission/define_paths.R`
Output file: `"~/data/gcme/MS_data/plot_data.csv"` (now changed to be written to "./data/plot_data.csv"

pmodel_modified is different to pmodel (dafault) only for specific use.

Now it cahnges calc_ftemp_inst_vcmax and calc_ftemp_inst_jmax, newly using parameters from Smith and Keenan 2020 GCB.
