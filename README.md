# RO-Crates from Calcium Imaging Experiments

This repository contains [Research Object Crates (RO-Crates)](https://w3id.org/ro/crate/1.1) bundling the research data and their retrospective provenance that was transferred from Electronic Lab Notebook (ELN) protocols using an automated structure-based approach.
The research data was previously published under the [CC-BY 4.0](http://creativecommons.org/licenses/by/4.0/) by:

Susanne Staehlke, J. Barbara Nebe.<br>
**Research data of Calcium Imaging after electrical stimulation.** <br>
Zenodo (2021).<br>
https://doi.org/10.5281/zenodo.4923173

The automated approach to create these bundles is described in full detail in this article:

Max Schröder, Susanne Staehlke, Paul Groth, J. Barbara Nebe, Sascha Spors, Frank Krüger.<br>
**Structure-based knowledge acquisition from electronic lab notebooks for research data provenance documentation.**<br>
Journal of Biomedical Semantics 13, 4 (2022).<br>
https://doi.org/10.1186/s13326-021-00257-x

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

In order to reference this dataset, please consider the information in the [CITATION.cff](CITATION.cff) file.

## Structure of the Repository

The repository contains seven folders that each represents a [RO-Crate](https://w3id.org/ro/crate/1.1) bundle about a Ca-imaging experiment.
The bundle contains a semantic representation of the retrospective provenance of the research data creation (`ro-crate-metadata.json`), i.e., the Ca-imaging procedure.
Furthermore, the research data (`Data`) and a copy of the ELN protocol and the used resources in the form of HTML files (`Protocol`) is contained.