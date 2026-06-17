[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.nm000271-blue)](https://doi.org/10.82901/nemar.nm000271)

# Multi-paradigm EEG dataset for studying upper limb rehabilitation exercises

## Summary

This dataset contains scalp electroencephalography (EEG) recordings acquired while
participants performed/imagined **upper-limb rehabilitation exercises** under a
**multi-paradigm** protocol. It is intended to support research on motor-imagery and
rehabilitation brain–computer interfaces (BCI) for upper-limb function.

The BIDS conversion in this NEMAR record contains EEG data for **28 participants**
(`sub-*` folders), organised under the `eeg/` modality with a motor-imagery task
(`task-imagery`).

## Modality and paradigm

- **Modality:** EEG (scalp electroencephalography)
- **Task / paradigm:** Upper-limb motor imagery / rehabilitation exercises
  (`task-imagery`), multi-paradigm
- **Application:** Upper-limb rehabilitation, motor-imagery BCI

## Participants

This BIDS dataset includes **28 subjects**. Refer to `participants.tsv` and the
original data descriptor for demographic details.

## Original dataset / data paper

Please cite the original Scientific Data descriptor when using this dataset:

> Chang, W., Kong, W., Yan, G., Lv, R., Du, K., Sadiq, M. T., Guo, B., Yin, R., & Liu, X.
> (2025). *A multi-paradigm EEG dataset for studying upper limb rehabilitation
> exercises.* **Scientific Data, 12, 1877.**
> https://doi.org/10.1038/s41597-025-06147-6

- **DOI:** [10.1038/s41597-025-06147-6](https://doi.org/10.1038/s41597-025-06147-6)
- **Source / project:** School of Electronic and Information Engineering, Lanzhou
  Jiaotong University
- **Related record:** https://figshare.com/articles/dataset/28831730

## Attribution

All data were collected by the original authors (Wenwen Chang and colleagues, Lanzhou
Jiaotong University). Please credit the original creators and cite the data paper above.
This NEMAR record redistributes the dataset in BIDS format; EEG-BIDS and related BIDS
tools were used only for standardisation, not as the source of the data.

## License

CC-BY-4.0 (see `dataset_description.json`).
