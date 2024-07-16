# OpenHands
An Open-Source finger bony anatomy dataset

**DOI:** [![DOI](https://img.shields.io/badge/doi-10.1007/s10439--024--03560--7-brightgreen)](https://doi.org/10.1007/s10439-024-03560-7)
**License:** [![License](https://img.shields.io/badge/license-CC--BY--SA--4.0-green)](../main/LICENSE)

OpenHands is a resource which contains a statistical description of finger bones based upon CT scan data collected by the University of Southampton, UK. The Machine Learning method Principal Component Analysis (PCA) has been used to reduce the dimensionality of this anatomic dataset to generate a mean finger bone shape, and independent modes of shape variation (Figure 1, below). As such, the dataset describes the anatomic variation across the training dataset without including any identifiable representation of the individuals.

| <img src="../main/abstract/process.png" alt="Dorsal-Palmar and Radio-Ulnar plane views of four fingers; mean and extremes (+/- 2std) in PC1" width="800"/> | 
|:--:| 
| *Generating finger statistical shape models from 1) CT data, 2) segmented ahead of alignment and registration, allowing 3) PCA to generate principal modes of variation, plotted for all four fingers in Dorsal-Palmar and Radio-Ulnar plane views, at mean and extremes (+/- 2std) in PC1* |

This dataset is intended to allow the research community to perform more statistically robust hand biomechanics research, without the costs, inconvenience, and risk of putting our research participants through medical imaging, especially where CT involves ionising radiation.

This first version of OpenHands is not fully statistically robust as it is based upon only ten training datasets (from 5 female and 5 male participants), who are representative only of healthy individuals, free of hand and wrist injury, and from a narrow ethnic diversity. We are keen however to build further individuals into the dataset subject to completing data sharing agreements between our institutions, and will acknowledge contributing researchers here.

In the meantime you can download the preliminary model's mean shape as .stl files.

For more detailed descriptions of the dataset and statistical testing behind it, please refer to the publication linked below.

Funding
--------

The research behind this dataset was funded by the following organisations:
- the Engineering & Physical Sciences Research Council (EPSRC), UK (T Munyebvu)
- the Alan Turing Institute, UK (grant no. EP/N510129/1 (A Dickinson))

Ethical Approvals
--------

This secondary data analysis work was granted ethical approval by the University of Southampton's Ethics and Research Governance Office (ERGO 61718)

Original MRI data collection work was granted ethical approval by the UK's National Research Ethics Service (NRES, ref 14/LO/1059)

Acknowledgments
--------

This model is built using data collected with expert clinical partners at University Hospital Southampton NHS Trust, Professor David Warwick, Dr Leonard King, Dr Angela Darekar and Chris Everitt, with University of Southampton engineers Dr Chris Philipps and Dr Alex Forrester.

License
--------

This dataset uses a Creative Commons Attribution Share Alike 4.0 International license, which can be found [here](../main/LICENSE)
Share Alike means that if you remix, transform, or build upon the dataset, you must distribute your contributions under the same license.

How to acknowledge
------------------

OpenHands was presented at the 2023 European Society for Biomechanics conference on 10th July 2023, and the abstract is included here, and at the [conference web page](https://esbiomech.org/conference/esb2023/paper-abstracts/). The full peer-reviewed paper has now been accepted for publication. Please check back here in time, for a doi and full reference for you to cite if you use the dataset. 

Please cite as:
T.A. Munyebvu, C.D. Metcalf, C.B. Burson Thomas, D. Warick, C. Everitt, L. King, A. Darekar, M. Browne, M.O.W. Heller and A.S. Dickinson (2024), Open Hands: An Open-Source Statistical Shape Model of the Finger Bones. Annals of Biomedical Engineering, [(https://doi.org/10.1007/s10439-024-03560-7)](https://doi.org/10.1007/s10439-024-03560-7) [https://github.com/abel-research/OpenHands](https://github.com/abel-research/OpenHands).
