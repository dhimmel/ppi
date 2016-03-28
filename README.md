# Compiling human protein–protein interactions

This repository collects protein interactions from several resources and creates an integrated catalog of interactions. An interaction refers to when two genes produce protein products that physically interact. Genes are identified using Entrez Gene. See the [Thinklab discussion](http://doi.org/10.15363/thinklab.d85#9) for additional information.

## Execution

[`compile-PPIs.ipynb`](compile-PPIs.ipynb) is a notebook (Python 3.4) which performs the analysis. The combined interaction catalog is exported to [`data/ppi-sources.tsv`](data/ppi-sources.tsv) (each row is a gene–gene–source combination) and [`data/ppi-hetio-ind.tsv`](data/ppi-hetio-ind.tsv) (each row is a gene–gene combination, these interactions are used in the [rephetio](http://doi.org/10.15363/thinklab.4) hetnet).

## License

All original content in this repository is licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/ "CC0 1.0 Universal: Public Domain Dedication"). `hetio-dag` data is licensed as [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Incomplete Interactome data is used [with permission](http://doi.org/10.15363/thinklab.d111#3). Please contact the [Human Interactome Database](http://interactome.dfci.harvard.edu/H_sapiens/) regarding the licensing status of their data.
