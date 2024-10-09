#  FEDI Toolbox

![GitHub issues](https://img.shields.io/github/issues/FEDIToolbox/FEDI)
[![Documentation Status](https://readthedocs.org/projects/fedi/badge/?version=latest)](https://fedi.readthedocs.io/en/latest/)
[![GitHub license](https://img.shields.io/github/license/FEDIToolbox/FEDI)](https://github.com/FEDIToolbox/FEDI/blob/main/LICENSE)


**Fetal and Neonatal Development Imaging (FEDI)** toolbox is a comprehensive, free, open-source toolbox that provides a suite of command-line tools dedicated to the processing and analysis of fetal and neonatal MRI data.


![FEDI_Dreaming](https://github.com/FEDIToolbox/FEDI/assets/20087558/754a9d42-858f-4445-b25c-98354903f34a)



## Note

**FEDI** is under active development, constantly expanding its functionalities.

## Key Features
While **FEDI** is primarily intended for the processing and analysis of fetal and neonatal MRI data, some tools can be used for any type of MRI data. In summary, **FEDI** features:

- Multiple Q-Shell Sampling
- Diffusion MRI Preprocessing
- Distortion Correction for Diffusion MRI
- Data Weighting and Outlier Detection
- Motion Correction for diffusion MRI

## Installation
To install the FEDI toolbox, clone the repository and add the necessary paths to your `.bashrc` file:


```bash
git clone https://github.com/FEDIToolbox/FEDI.git
cd FEDI/FEDI/scripts
FEDI_SCRIPTS=$(pwd)
echo 'export PATH="${FEDI_SCRIPTS}:$PATH"' >> ~/.bashrc
source ~/.bashrc
```
Additional installation methods will be available soon.

## Dependencies
Recommended to use Anaconda Python distribution.
- [DIPY](https://dipy.org/)
- [CVXPY](http://www.cvxpy.org/)
- [MRtrix3](https://www.mrtrix.org/)
- [FSL](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslInstallation)
- [ANTs](https://github.com/ANTsX/ANTs).
- Numpy, Scipy, Nibabel, Matplotlib

## Documentation
The full documentation is available at [FEDI](https://fedi.readthedocs.io)

For additional details, please visit the main repository: https://github.com/FEDIToolbox/FEDI


## Contact
For questions, issues, or suggestions, please open an issue [here](https://github.com/FEDIToolbox/FEDI/issues).
