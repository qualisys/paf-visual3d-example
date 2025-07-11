# Qualisys PAF – Visual3D/Sift example

## Getting started
To download this example project to your computer, you can either:

* [Click here](https://github.com/qualisys/paf-visual3d-example/archive/refs/heads/main.zip) to download it as a zip file.
<br>_— or —_
* Clone this repository to your computer.

## Preparing for processing

Either Visual3D or Sift can be used with this example. Sift will run the same script and generate the same output files as Visual3D. 

### Visual3D processing

1. Install Visual3D.
2. In QTM, set Project Options > Miscellaneous > Folder Options for "Visual3D" to ```C:\Program Files\Visual3D x64\Visual3D.exe``` (adapt if Visual3D is installed at different location).

### Sift processing

1. Install Sift.
2. In QTM, set Project Options > Miscellaneous > Folder Options for "Visual3D" to ```C:\Program Files\Sift\Sift.exe``` (adapt if Sift is installed at different location).

## Resources for using the Qualisys Project Automation Framework (PAF)

The purpose of the ***Project Automation Framework*** (PAF) is to streamline the motion capture process from data collection to the final report. This repository contains an example project that illustrate how PAF can be used to implement custom automated data collection in [Qualisys Track Manager (QTM)](http://www.qualisys.com/software/qualisys-track-manager/), and how QTM can be connected to a processing engine. 

### PAF Documentation

The full documentation for PAF development is available here: [PAF Documentation](https://github.com/qualisys/paf-documentation).


### PAF Examples

Our official examples for various processing engines:
- [AnyBody](https://github.com/qualisys/paf-anybody-example)
- [Cleanse](https://github.com/qualisys/paf-cleanse-example)
- [Excel](https://github.com/qualisys/paf-excel-example)
- [Matlab](https://github.com/qualisys/paf-matlab-example)
- [OpenSim](https://github.com/qualisys/paf-opensim-example)
- [Python](https://github.com/qualisys/paf-python-example)
- [Theia Markerless](https://github.com/qualisys/paf-theia-markerless-example)
- [Theia Markerless Comparison](https://github.com/qualisys/paf-theia-markerless-comparison-example)
- [Theia Markerless True Hybrid](https://github.com/qualisys/paf-theia-markerless-true-hybrid-example)
- [Visual3D](https://github.com/qualisys/paf-visual3d-example)

_As of QTM version 2.17, the official Qualisys PAF examples can be used without any additional license. Note that some more advanced analysis types require a license for the "PAF Framework Developer kit" (Article number 150300)._
