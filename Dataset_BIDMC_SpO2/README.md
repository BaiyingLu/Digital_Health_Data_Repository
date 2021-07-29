# BIDMC Blood Oxygen Saturation Dataset (32 seconds window)

## Description of Dataset
This dataset was collected as part of the following study: [Toward a Robust Estimation of Respiratory Rate From Pulse Oximeters](https://ieeexplore.ieee.org/document/7748483).The original data was acquired from critically-ill patients during hospital care at the Beth Israel Deaconess Medical Centre (Boston, MA, USA). Two annotators manually annotated individual breaths in each recording using the impedance respiratory signal. The 53 recordings within the dataset, each of 8-minute duration.

## Citing this Dataset
Please cite the original study this dataset was developed for:

> Pimentel, M.A.F. et al. Towards a Robust Estimation of Respiratory Rate from Pulse Oximeters. IEEE Transactions on Biomedical Engineering, 64(8), pp.1914-1923, 2016. [DOI: 10.1109/TBME.2016.2613124](http://doi.org/10.1109/TBME.2016.2613124).([Link to Open Access Article](https://ieeexplore.ieee.org/document/7748483))

> Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.

Please also cite the DBDP if you are using any module from Digital Biomarker Discovery Pipeline:

> Bent, B., Wang, K., Grzesiak, E., Jiang, C., Qi, Y., Jiang, Y., Cho, P., Zingler, K., Ogbeide, F.I., Zhao, A., Runge, R., Sim, I., Dunn, J. (2020). The Digital Biomarker      Discovery Pipeline: An open source software platform for the development of digital biomarkers using mHealth and wearables data. Journal of Clinical and Translational Science, 1-28. doi:10.1017/cts.2020.511 ([Link to Open Access Article](https://www.cambridge.org/core/journals/journal-of-clinical-and-translational-science/article/digital-biomarker-discovery-pipeline-an-open-source-software-platform-for-the-development-of-digital-biomarkers-using-mhealth-and-wearables-data/A6696CEF138247077B470F4800090E63))

## Previous Studies utilizing Dataset

Previous studies utilizing this dataset include the [Toward a Robust Estimation of Respiratory Rate From Pulse Oximeters](https://ieeexplore.ieee.org/document/7748483). Other studies may be ongoing.


## Dataset

The dataset and documentation is available at the following link: [Link to BIDMC Blood Oxygen Saturation Dataset](https://physionet.org/content/bidmc/1.0.0/)

## Additional Usage Information
The dataset contains:
1. Physiological signals, such as the PPG, impedance respiratory signal, and electrocardiogram (ECG). These are sampled at 125 Hz.
2. Physiological parameters, such as the heart rate (HR), respiratory rate (RR), and blood oxygen saturation level (SpO2). These are sampled at 1 Hz.
3. Fixed parameters, such as age and gender
4. Manual annotations of breaths.
This dataset was first reported in the referenced publication, in which the data was used to evaluate the performance of different algorithms for estimating respiratory rate from the pulse oximetry, or PPG signal.

## Useful DBDP Modules
The DBDP provides code to help analyze this dataset:

* [Pre-processing module](https://github.com/DigitalBiomarkerDiscoveryPipeline/Pre-process)
* [Human Activity Recognition](https://github.com/DigitalBiomarkerDiscoveryPipeline/Human-Activity-Recognition)
* [wearablecompute](https://github.com/DigitalBiomarkerDiscoveryPipeline/wearablecompute)
