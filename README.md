Edward Gunning’s Thesis Chapter 3
================

## Summary

This repository contains the code for Chapter 3 of Edward Gunning’s
Ph.D. thesis. It mainly deals with the processing and preparation of the
RISC dataset for analysis.

## Repository Structure

- :open_file_folder: <b>[code](code/)</b>
  - 📁 <b>[analysis](code/analysis/)</b> – scripts used to perform all
    the steps of the data analysis (i.e., processing and preparation of
    the RISC dataset). The [master
    script](code/analysis/00-data-preparation-master-script.R) runs all
    of the steps sequentially.
  - 📁 <b>[figures](code/figures/)</b> – scripts to produce figures
    presented in chapter 3 of the thesis.
  - 📁 <b>[functions](code/functions/)</b> – custom functions written
    for data processing and preparation.
- :open_file_folder: <b>[outputs](outputs/)</b>
  - 📁
    <b>[basis-expansion-diagram](outputs/basis-expansion-diagram/)</b> –
    files to produce the flow chart for the basis expansion.
  - 📁 <b>[data](outputs/data/)</b> – intermediate copies of the dataset
    saved at various stages of the analysis (<i>not publicly
    available</i>).
  - 📁 <b>[plots](outputs/plots/)</b> – outputs of figures made during
    the process. Most are outputted as `.tex` files and are compiled in
    the [](outputs/plots/figures.tex) master file. Some are compiled
    locally in `R` so a `.pdf` and `.tex` version is stored.
  - 📁 <b>[tables](outputs/tables/)</b> tables created at different
    stages of the process.
- :open_file_folder: <b>[data](data/)</b> – initial copies of the raw
  datasets (<i>not publicly available</i>)

## Contact

📧 <Edward.Gunning@ul.ie>
