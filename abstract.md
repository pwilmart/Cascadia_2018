## Title
#### Reproducible quantitative proteomics analyses using Jupyter notebooks, the R language, and Github.

## Author
#### Phillip A. Wilmarth, OHSU
##### wilmarth@ohsu.edu

<br>

**Abstract:** Proteomics data analyses grow more complicated every year and are difficult to effectively communicate in traditional scientific publications. Jupyter notebooks [(jupyter.org)](www.jupyter.org) allow computer code, computer output, formatted text, and HTML content to be combined into live documents. The interactivity and ability to add rich descriptions make notebooks ideal for learning and sharing best data analysis practices. Notebooks increase transparency and mark a significant step forward in reproducible proteomics. Notebooks are logical additions to supplemental materials for scientific publications.

Jupyter notebooks support several languages including R. There are many proteomic and genomic data analysis packages available in R, along with advanced data visualizations. Github can directly render Jupyter notebooks. Hosting results files, analysis scripts, and notebooks at Github is a nice alternative to journal supplemental files because content can be changed during review and after publication.

To illustrate Jupyter notebooks for quantitative proteomics data analyses, a TMT dilution experiment is presented (available at https://github.com/pwilmart/TMT_analysis_examples.git). A complex mouse brain sample was TMT labeled and combined in relative abundances of 25/20/15/10/5/2.5 and analyzed on a Thermo Fusion in SPS MS3 mode. The data were processed using Proteowizard, Comet, and in-house Python scripts. How well the measured reporter ion intensities reflected the known dilutions at the PSM (peptide spectral match), peptide, and protein levels was examined. Data aggregation in TMT experiments dramatically reduced the dataset dimensionality (60K PSMs, 20K peptides, and 2.7K proteins); there were 22 times fewer proteins than PSMs. Aggregation of reporter ion intensities also greatly reduced variance (median CVs): 13.6% for PSMs, 11.1% for peptides, and 6.5% for proteins. The notebook contains examples of basic R data manipulations and visualizations.
