# Example Sequence warmup-P3-PQ4000 README
[Zenodo Link for downloading the .mp4 file](https://doi.org/10.5281/zenodo.10037004)

## Overview

This example sequence is constructed to provide a balanced signal for both high and low-frequency characteristics, ideal for warm-up tests and performance assessments. The sequence comprises 16 individual segments, each 50 seconds long at 60fps, and is based on the Alpha3 and Alpha5 lossless `.mov` sequences.
The Spatio-Temporal noise in this example has been remapped to DCI-P3 in a BT.2020 container, using a PQ EOTF with a maximum of 4000 nits (MaxCLL). 

> **Note**: This is just one of many possible example configurations based on the original signals available in the GIT repository.

### Speed and Encoding

- **Speed**: Slowed down to 20%.
- **Encoding**: HEVC in an .mp4 container.

## Timecodes and Segment Descriptions

Each segment is detailed below with its corresponding timecodes and configurations. The signals in these segments undergo various spatial manipulations and signal level inversions to ensure a balanced test sequence.

### Segment 1: Alpha3 Original (00:00 - 00:50)

- **Timecode**: 00:00 - 00:50
- **Luminance Mapping**: 0-4000 nit ST.2084 PQ in narrow range.
- **Color Mapping**: DCI-P3 within a BT.2020 container.

### Segment 2: Alpha3 Flipped Horizontally (00:50 - 01:40)

- **Timecode**: 00:50 - 01:40
- **Spatial Manipulation**: Flipped horizontally.

### Segment 3: Alpha3 Flipped Vertically (01:40 - 02:30)

- **Timecode**: 01:40 - 02:30
- **Spatial Manipulation**: Flipped vertically.

### Segment 4: Alpha3 Flipped Horizontally & Vertically (02:30 - 03:20)

- **Timecode**: 02:30 - 03:20
- **Spatial Manipulation**: Flipped both horizontally and vertically.

### Segment 5: Alpha3 Signal Inverted (03:20 - 04:10)

- **Timecode**: 03:20 - 04:10
- **Signal Manipulation**: Signal levels inverted.

### Segment 6: Alpha3 Horizontally Flipped & Signal Inverted (04:10 - 05:00)

- **Timecode**: 04:10 - 05:00
- **Spatial and Signal Manipulation**: Flipped horizontally and signal levels inverted.

### Segment 7: Alpha3 Vertically Flipped & Signal Inverted (05:00 - 05:50)

- **Timecode**: 05:00 - 05:50
- **Spatial and Signal Manipulation**: Flipped vertically and signal levels inverted.

### Segment 8: Alpha3 Both Flipped & Signal Inverted (05:50 - 06:40)

- **Timecode**: 05:50 - 06:40
- **Spatial and Signal Manipulation**: Flipped both horizontally and vertically, and signal levels inverted.

### Segment 9: Alpha5 Original (06:40 - 07:30)

- **Timecode**: 06:40 - 07:30

### Segment 10: Alpha5 Flipped Horizontally (07:30 - 08:20)

- **Timecode**: 07:30 - 08:20
- **Spatial Manipulation**: Flipped horizontally.

### Segment 11: Alpha5 Flipped Vertically (08:20 - 09:10)

- **Timecode**: 08:20 - 09:10
- **Spatial Manipulation**: Flipped vertically.

### Segment 12: Alpha5 Flipped Horizontally & Vertically (09:10 - 10:00)

- **Timecode**: 09:10 - 10:00
- **Spatial Manipulation**: Flipped both horizontally and vertically.

### Segment 13: Alpha5 Signal Inverted (10:00 - 10:50)

- **Timecode**: 10:00 - 10:50
- **Signal Manipulation**: Signal levels inverted.

### Segment 14: Alpha5 Horizontally Flipped & Signal Inverted (10:50 - 11:40)

- **Timecode**: 10:50 - 11:40
- **Spatial and Signal Manipulation**: Flipped horizontally and signal levels inverted.

### Segment 15: Alpha5 Vertically Flipped & Signal Inverted (11:40 - 12:30)

- **Timecode**: 11:40 - 12:30
- **Spatial and Signal Manipulation**: Flipped vertically and signal levels inverted.

### Segment 16: Alpha5 Both Flipped & Signal Inverted (12:30 - 13:20)

- **Timecode**: 12:30 - 13:20
- **Spatial and Signal Manipulation**: Flipped both horizontally and vertically, and signal levels inverted.

## Technical Metadata

- **Resolution**: 3840x2160 pixels (Center-cropped from original 3840x3840)
- **Frame Rate**: 60fps
- **Color System**: YCbCr 4:2:0
- **Quantization Range**: Narrow Range
- **Chromaticities**: BT.2020
- **EOTF**: PQ - SMPTE ST 2084
- **Mastering Display Primaries**: DCI-P3
- **Mastering Display White Point**: D65
- **Maximum Display Mastering Luminance**: 4000 cd/m-2
- **Minimum Display Mastering Luminance**: 0 cd/m-2


[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--2868--8432-green.svg)](https://orcid.org/0009-0007-2868-8432)

# Part of: "Spatio-Temporal Noise Sequences: Multipurposed Pseudo-Random Visual Test Signals"

Author: Florian Friedrich | [FF.de](https://www.ff.de)

