VPAW by Kitware, Inc.
=====================

A Virtual Pediatric Airways Workbench (VPAW) is a patient-centered surgical planning software system targeted to pediatric patients with airway obstruction.

It aims to enable a full surgical planning pipeline for the evaluation of surgical outcomes. See [features][#Features] for more details.

This project contains the new generation of VPAW based on [3D Slicer](https://www.slicer.org/) and
it was created using [Slicer Custom App Template](https://github.com/KitwareMedical/SlicerCustomAppTemplate).

_This project is in active development and may change from version to version without notice._

## Features

The project is being actively developed and our plan is to implement the following functionalities to enable users to express potential surgical treatment planning options for patients with airway obstruction.

A typical workflow will consist of the following steps:

* Importing computed tomography (CT) DICOM images
* Segmenting the airway (as described by _Hong et al_ [^1])
* Interactive 3D editing of airway geometries leveraging integration of 3D pointing devices such as [3D Systems Touch](https://www.3dsystems.com/haptics-devices/touch) through the OpenHaptics interface
* Creating input files for offline geometric analysis and Computational fluid dynamics (CFD) simulations

[^1]: See section 2.1 of Hong, Yi, et al. "A pediatric airway atlas and its application in subglottic stenosis." 2013 Ieee 10th International Symposium on Biomedical Imaging. IEEE, 2013. Link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4769591/

## Maintainers

* [Contributing](CONTRIBUTING.md)
* [Building](BUILD.md)

## History

The initial version of this project was developed between 2010 and 2015 in the context of supporting predictive modeling for treatment of upper airway obstruction in young children, the project as well as the team involved are respectively described and acknowledged in the [referenced](#how-to-cite) publication.

In 2022, the development of the next generation of VPAW based on [3D Slicer](https://www.slicer.org) was initiated.

## Acknowledgment

We gratefully acknowledge support from National Heart, Lung, and Blood Institute (NIH/NHLBI grant nos: 5R01HL105241 and 5R01HL154429 ), and National Health Institute of Dental and Craniofacial Research (NIH/NHIDC grant no: R43DE024334).

## License

This software is licensed under the terms of the [Apache License Version 2.0](LICENSE).

## How to cite ?

Quammen, C. W., Taylor, R. M., 2nd, Krajcevski, P., Mitran, S., Enquobahrie, A., Superfine, R., Davis, B., Davis, S., & Zdanski, C. (2016). The Virtual Pediatric Airways Workbench. Studies in health technology and informatics, 220, 295–300.\
See https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5588666/
