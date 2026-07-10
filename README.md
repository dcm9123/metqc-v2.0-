[metqc_icon.html](https://github.com/user-attachments/files/29905629/metqc_icon.html)
# Metqc v2.0
## Daniel Castaneda Mogollon, PhD
### July 10th, 2026

![Alt Text]metqc_icon.html

This forked repository has a few modifications from the original one, including some filtering steps, change of parameters and software, and modifying the Snakemake files linked to it.

The modifications include:
- `Cutadapt` replacement with `bbduk` (this change allows the user to not specify the exact sequence for the adapters, and it gets to remove polyGs and polyCs in the case of a NextSeq or NovaSeq instrument)
- 


What you need:
- A `logs` folder (found in this repository, so if you clone it you should be good)
- A `config.yaml` file with your specified parameters
- A `Snakefile` (best if you don't modify this one.
- A `cluster.json` file that can be used when submitting a Snakemake job in a Slurm-supported server

Versions we recommend for the pipeline to run just fine:
- Snakemake 7.32.4
- Bbduk 39.26
- FastQC v0.12.1
- MultiQC v1.0.dev0
- PRINSEQ-lite 0.20.4
- BBMap 39.26
- Bmtagger 1.1.0

Output:
Folders 
Files

