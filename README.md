# Causality in SE - Data

This repository contains the large data files for the CausalityInSE project. It is included as a Git submodule in the main [CausalityInSE](https://github.com/hehao98/CausalityInSE) repository to prevent large files from interfering with tools like Overleaf.

## Files
- `commits.csv.zip`: A compressed dataset of software engineering commits used for causal analysis.
- `se_papers_metadata.csv`: Metadata of software engineering papers analyzed in our project.

## Usage
If you clone the main repository, ensure you initialize and update submodules to fetch this data:

```bash
git clone --recurse-submodules https://github.com/hehao98/CausalityInSE.git
```
Or, if you already cloned the repository without the data:
```bash
git submodule update --init --recursive
```
