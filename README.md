# A workflow using pySCENIC (https://scenic.aertslab.org/)

### input: edit config files for inputs
    "sample.csv" - sample sheet with sample ids and correspoinding loom file, "sample" and "loom". 
    "config.pyscenic.yaml" - all running parameters. 
    "cisTarget_databases" - target databaees can be downloaded from SCENIC website (https://resources.aertslab.org/cistarget/) 
    "tfs" - all TFs
### Run:
    snakemake --cores 20 -s Snakefile.pyscenic --rerun-incomplete
