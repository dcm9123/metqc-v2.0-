# Metqc v2.0
## Daniel Castaneda Mogollon, PhD
### July 10th, 2026

This forked repository has a few modifications from the original one, including some filtering steps, change of parameters and software, and modifying the Snakemake files linked to it.

The modifications include:
- `Cutadapt` replacement with `bbduk` (this change allows the user to not specify the exact sequence for the adapters, and it gets to remove polyGs and polyCs in the case of a NextSeq or NovaSeq instrument)
- 
