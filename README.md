# DeepMRSeg

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/abb2c20d73ed464180494bf2fed3f0eb)](https://app.codacy.com/gh/CBICA/DeepMRSeg?utm_source=github.com&utm_medium=referral&utm_content=CBICA/DeepMRSeg&utm_campaign=Badge_Grade_Settings)

DeepMRSeg is a Python-based package for processing and analysis of MRI images. The package is developed and maintained by the [Center for Biomedical Image Computing and Analytics (CBICA)](https://www.cbica.upenn.edu/) at the University of Pennsylvania. As the name implies, main modules of DeepMRSeg are built upon Deep Learning models that perform a set of image segmentation steps on initial scans.

DeepMRSeg aims to provide users a ***robust*** and ***accurate*** toolset for performing common image processing tasks in neuroimaging. In order to be able to meet these challenges DeepMRSeg uses a modified UNet architecture that combines an ensemble of learners. A second major feature of DeepMRSeg is the set of pre-trained models provided for various tasks. Importantly, we applied intensive model training using very large and diverse MRI datasets with carefully verified ground-truth labels.  

## Supported Platforms
These are the platforms we have tested. 
-   Windows 10 x64
-   Ubuntu 20.4 64 bit

It may also work on other platforms.

## Prerequisities
-   [Python 3](https://www.python.org/downloads/)
-   If you prefer conda, you may install it from [here](https://www.anaconda.com/products/individual)

## Installation Instructions

### 1) Direct installation at default location 
```
git clone  https://github.com/CBICA/DeepMRSeg.git
cd DeepMRSeg
python setup.py install
```

### 2) Installation in conda environment
```
conda create --name DeepMRSeg python=3.7.9
conda activate DeepMRSeg
```
Then follow steps from [direct installation](#direct-installation-at-default-location)

## Usage

On the cmd prompt (or on Anaconda prompt) type

For testing
```bash
deepmrseg_test
```

For Training
```bash
deepmrseg_train
```

Please see the user manual

## License

## How to cite DeepMRSeg

## Publications

## Authors and Contributors

The DeepMRSeg package is currently developed and maintained by:

Others who contributed to the project are:

## Grant support

Development of the DeepMRSeg package is supported by the following grants:

## Disclaimer
-   The software has been designed for research purposes only and has neither been reviewed nor approved for clinical use by the Food and Drug Administration (FDA) or by any other federal/state agency.
-   This code (excluding dependent libraries) is governed by the license provided in https://www.med.upenn.edu/cbica/software-agreement.html unless otherwise specified.
-   By using DeepMRSeg, you agree to the license as stated in the [license file](https://github.com/CBICA/DeepMRSeg/blob/main/LICENSE).

## Contact
For more information, please contact <a href="mailto:software@cbica.upenn.edu">CBICA Software</a>.
