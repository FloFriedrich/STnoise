# Spatio-Temporal Noise Sequences: Multipurposed Pseudo-Random Visual Test Signals

Author: Florian Friedrich | [FF.de](https://www.ff.de)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--2868--8432-green.svg)](https://orcid.org/0009-0007-2868-8432)

## General Description

This repository hosts a range of spatio-temporal noise sequences designed for use in various technology evaluations in the video field, including display metrology, workflow testing, encoding stress tests, display warm-up, and algorithm design.

### Features

- **Format**: TIFF (16Bit half float, LZW compressed), MOV (H.265 lossless 12Bit)
- **Resolution**: 3840x3840 pixels, lower resolutions by utilizing cropping, higher resolutions by tiling)
- **Aspect Ratio**: Agnostic
- **Framerate**: Agnostic
- **Colorspace**: Agnostic
- **File Size**: Up to 50GB per sequence

## Data Download

The full dataset is too large to be hosted directly on GitHub. You can download the sequences from Zenodo as described below.

## Directory Structure

This repository is organized as follows:

- `Example_Implementations/`: Folder planned for containing sample code and use-case scenarios (currently empty; see `Planned_Implementations.md`).
- `LUTs_and_Transformations/`: Folder planned for containing Lookup Tables and transformation files (currently empty; see `Planned_LUTs_and_Transformations.md`).

#### Media Directories (Hosted on Zenodo)
The following directories contain a `ZENODO_LINK.md` file with the DOI link for downloading the actual media sequences from Zenodo:

- `STNOISE_alpha1_MOV_sequence/`: MOV file for alpha value 1.
- `STNOISE_alpha1_TIFF_sequence/`: TIFF files for alpha value 1.
- `STNOISE_alpha2_MOV_sequence/`: MOV file for alpha value 2.
- `STNOISE_alpha2_TIFF_sequence/`: TIFF files for alpha value 2.
- `STNOISE_alpha3_MOV_sequence/`: MOV file for alpha value 3.
- `STNOISE_alpha3_TIFF_sequence/`: TIFF files for alpha value 3.
- `STNOISE_alpha4_MOV_sequence/`: MOV file for alpha value 4.
- `STNOISE_alpha4_TIFF_sequence/`: TIFF files for alpha value 4.
- `STNOISE_alpha5_MOV_sequence/`: MOV file for alpha value 5.
- `STNOISE_alpha6_TIFF_sequence/`: TIFF files for alpha value 6.
- `STNOISE_alpha7_MOV_sequence/`: MOV file for alpha value 7.
- `STNOISE_alpha7_TIFF_sequence/`: TIFF files for alpha value 7.

See `ZENODO_LINK.md` in each media directory for the corresponding download link.


## Usage Variabilities

You can modify these sequences in numerous ways, including:

- Mapping, swapping, or flipping the R, G, B channels.
- Changing the seed order or applying different blending methods.
- Cropping, tiling, or scaling the images.
- Converting to different color gamuts through computational transformations or LUTs.

## Analysis and Fine-Tuning

For specific project goals, seeds and sequences can be selected, excluded, or combined for desired spatio-temporal distribution. Filters in the frequency domain can be used for additional customization.

## References

1. Kunkel, T., & Friedrich, F. (2022). Utilizing advanced spatio‐temporal backgrounds with dynamic test signals for high dynamic range display metrology. *Special Section Paper*. [DOI: 10.1002/sdtp.15469](https://doi.org/10.1002/sdtp.15469) (Distinguished Paper), [DOI: 10.1002/jsid.1125](https://doi.org/10.1002/jsid.1125) (Full Paper).
  
2. Kunkel, T., & Daly, S. (2020). 57-1: Spatiotemporal noise targets inspired by natural imagery statistics. *SID Symposium Digest of Technical Papers*. [DOI: 10.1002/sdtp.14001](https://doi.org/10.1002/sdtp.14001).
  
3. Field, D. J. (1987). Relations between the statistics of natural images and the response properties of cortical cells. *Journal of the Optical Society of America A*. [DOI: 10.1364/JOSAA.4.002379](https://doi.org/10.1364/JOSAA.4.002379).
  
4. Webster, M., & Mollon, J. (1997). Adaptation and the color statistics of natural images. *Vision Research*. [DOI: 10.1016/S0042-6989(97)00125-9](https://doi.org/10.1016/S0042-6989(97)00125-9).

5. Lennon, J. J. (2000). Red-shifts and red herrings in geographical ecology. *Ecography*. [DOI: 10.1111/j.1600-0587.2000.tb00265.x](https://doi.org/10.1111/j.1600-0587.2000.tb00265.x).


## License

This project is released under the [Creative Commons Attribution 4.0 International License](LICENSE). For attribution, mention "Spatio-Temporal Noise Sequences: Multipurposed Pseudo-Random Visual Test Signals by Florian Friedrich | FF.de".

## Author Information

- ORCID: [0009-0007-2868-8432](https://orcid.org/0009-0007-2868-8432)
