<p align="center">
  <img src="https://user-images.githubusercontent.com/115654234/213008369-a3a3cc5b-498d-47ea-bd36-4569ce6c4e51.png">
</p>

## HH-TRP Dataset

HH-TRP Dataset is an open audio collection of drum recordings in the style of modern hip hop (urban trap) music. It features 15,000 audio loops provided in uncompressed stereo WAV format, along with paired JSON files containing label data for supervised training of generative AI audio models.

## Overview

The dataset was developed using an algorithmic framework to randomly generate audio loops from a customized database of MIDI patterns and one-shot drum samples. Data augmentation included random sample-swapping to generate unique drum kits and sound effects. It is intended for training or fine-tuning AI models with paired labels, adaptable for prompt-driven drum generation and other supervised learning objectives.

Its primary purpose is to provide accessible content for machine learning applications in music. Potential use cases include text-to-audio, prompt engineering, feature extraction, tempo detection, audio classification, rhythm analysis, music information retrieval (MIR), sound design and signal processing.

**Specifications**

- 15,000 audio loops (approximately 55 hours)
- 16-bit WAV format
- Tempo range: 130-220 BPM
- Paired label data (WAV + JSON)
- Variational drum kit and patterns
- Subgenre styles (drill, trapsoul, cloud rap, emo rap)

A key map JSON file is provided for referencing and converting MIDI note numbers to text labels. You can update the text labels to suit your preferences.

## Examples

See the examples folder to preview mp3 demos.


## License

This dataset was compiled by WaivOps, a crowdsourced music project managed by Patchbanks. All recordings have been sourced from verified composers and providers for copyright clearance.


The HH-TRP Dataset is licensed under Creative Commons Attribution 4.0 International [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Download

Direct WAV Download (22.3 GB): [hh_trp_wav.tar.gz](https://zenodo.org/records/15734094/files/hh_trp_wav.tar.gz?download=1&preview=1)

Direct JSON Download (642.9 kB): [hh_trp_json.tar.gz](https://zenodo.org/records/15734094/files/hh_trp_json.tar.gz?download=1&preview=1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15734094.svg)](https://doi.org/10.5281/zenodo.15734094)
## File Name Reference

| **Label**             | **Reference**                                                  |
| ----------------- | ------------------------------------------------------------------ |
| bpm  | The tempo of the audio file|
| hh_trp | Dataset name|
| id | Identification number|
| 000000 | Playlist track number|

## Citation

If you use this dataset for a research or development project, please cite the following references:
```bash
@dataset{HH-TRP Dataset,
author = {WaivOps},
title = {WaivOps HH-TRP: Open Audio Resources for Machine Learning in Music},
year = {2025},
doi = {10.5281/zenodo.15734094},
url = {https://doi.org/10.5281/zenodo.15734094},
}
```
## Additional Info

For any questions or feedback please email info@patchbanks.com.
