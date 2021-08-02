# Pattern Analysis of Oxygen Saturation Variability

## Description of Dataset
This dataset was collected as part of the following study: [Pattern Analysis of Oxygen Saturation Variability in Healthy Individuals: Entropy of Pulse Oximetry Signals Carries Information about Mean Oxygen Saturation](https://www.frontiersin.org/articles/10.3389/fphys.2017.00555/full).This database contains one-hour oxygen saturation measurements of 36 patients, used for the analysis of oxygen saturation variability. The sampling frequency (SF) used to be 1kHz, but through preprocessing, the SF of the saved data is 1Hz.

## Citing this Dataset
Please cite the original study this dataset was developed for:

> Amar S. Bhogal and Ali R. Mani. Pattern Analysis of Oxygen Saturation Variability in Healthy Individuals: Entropy of Pulse Oximetry Signals Carries Information about Mean Oxygen Saturation. Frontiers in Physiology, 8, 555. DOI:10.3389/fphys.2017.00555. ([Link to Open Access Article](https://www.frontiersin.org/articles/10.3389/fphys.2017.00555/full)

> Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220. ([Link to Open Access Article](https://pubmed.ncbi.nlm.nih.gov/10851218/)

Please also cite the DBDP if you are using any module from Digital Biomarker Discovery Pipeline:

> Bent, B., Wang, K., Grzesiak, E., Jiang, C., Qi, Y., Jiang, Y., Cho, P., Zingler, K., Ogbeide, F.I., Zhao, A., Runge, R., Sim, I., Dunn, J. (2020). The Digital Biomarker      Discovery Pipeline: An open source software platform for the development of digital biomarkers using mHealth and wearables data. Journal of Clinical and Translational Science, 1-28. doi:10.1017/cts.2020.511 ([Link to Open Access Article](https://www.cambridge.org/core/journals/journal-of-clinical-and-translational-science/article/digital-biomarker-discovery-pipeline-an-open-source-software-platform-for-the-development-of-digital-biomarkers-using-mhealth-and-wearables-data/A6696CEF138247077B470F4800090E63))


## Previous Studies utilizing Dataset

Previous studies utilizing this dataset include the [Pattern Analysis of Oxygen Saturation Variability in Healthy Individuals: Entropy of Pulse Oximetry Signals Carries Information about Mean Oxygen Saturation](https://www.frontiersin.org/articles/10.3389/fphys.2017.00555/full). Other studies may be ongoing.


## Dataset

The dataset and documentation is available at the following link: [Link to the Oxygen Saturation Variability Dataset](https://www.physionet.org/content/osv/1.0.0/)

## Additional Usage Information
The oxygen saturation data files are provided in standard WFDB format. The sampling frequency of the measurements is 1Hz as specified in the header files. The participants.csv file contains metadata about each participant.

## Useful DBDP Modules
The DBDP provides code to help analyze this dataset:

* [Pre-processing module](https://github.com/DigitalBiomarkerDiscoveryPipeline/Pre-process)
* [Human Activity Recognition](https://github.com/DigitalBiomarkerDiscoveryPipeline/Human-Activity-Recognition)
* [wearablecompute](https://github.com/DigitalBiomarkerDiscoveryPipeline/wearablecompute)
