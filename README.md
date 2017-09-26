# Statistical issues in the analysis of Illumina data
This repository contains data and Supplementary Materials for [Statistical Issues in the Analysis of Illumina Data](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-9-85)

The data have been compressed using `BeadDataPackR` Bioconductor library and a minimal script to read the data is given in [statistical-issues.Rmd](statistical-issues.Rmd). 

- [Targets file](spike_targets.txt)
- [Results of re-annotation for all non-spikes and non-controls](NewAnnotationM1.txt)
- [Intensities of each control probe on every array as exported by BeadStudio](FullSpikeControls.txt)
- [Average control profile as exported from BeadStudio](SpikesAveragedControls.txt)
- [Sequences for the Illumina controls used in the experiment](ControlSequences.txt)
- [Pre-calculated thermodynamic values for each spike probe](spikeThermoProperties.csv)
- [File giving bead IDs, targets and sequences for the spikes](spikeins_profile.csv)
- [Bead summary data .rda](bsd.sharpen.subtract.raw.rda)
- [BeadStudio output (non-normalised)](spike_beadstudio_output.zip) The file `SampleProbeProfile.txt` contains summary data for the non-spikes. The file `ControlProbeProfile.txt` contains summary data for the spikes and other control probes. The spikes have 'DRC' as their TargetID
