# STEP Dataset

## Description of Dataset
This dataset was collected as part of a study on [investigating the sources of inaccuracy in wearable optical heart rate sensors](https://www.nature.com/articles/s41746-020-0226-6) across a variety of activities (sitting, deep breathing, walking, and typing). The original study examined covariates including skin tone, signal lag, and device type. The dataset includes the heart rate given by the ECG and corresponding heart rate given by each smartwatch used in the study. Activity, Skin Tone, and internal subject ID are also columns in this dataset. This dataset was recorded July-August 2019 and includes 53 participants. The data is completely de-identified and data has already been time-synced, removing the need for time in this dataset and providing further de-identification. This dataset is comprised of data to explore the accuracy of wearables across the full range of skin tones and across a range of activities assessing motion artifact and potential signal crossover.

## Citing this Dataset
Please cite the DBDP and the original study this dataset was developed for:

> Bent, B., Wang, K., Grzesiak, E., Jiang, C., Qi, Y., Jiang, Y., Cho, P., Zingler, K., Ogbeide, F.I., Zhao, A., Runge, R., Sim, I., Dunn, J. (2020). The Digital Biomarker      Discovery Pipeline: An open source software platform for the development of digital biomarkers using mHealth and wearables data. Journal of Clinical and Translational Science, 1-28. doi:10.1017/cts.2020.511 ([Link to Open Access Article](https://www.cambridge.org/core/journals/journal-of-clinical-and-translational-science/article/digital-biomarker-discovery-pipeline-an-open-source-software-platform-for-the-development-of-digital-biomarkers-using-mhealth-and-wearables-data/A6696CEF138247077B470F4800090E63))

> Bent, B., Goldstein, B.A., Kibbe, W.A. et al. Investigating sources of inaccuracy in wearable optical heart rate sensors. npj Digit. Med. 3, 18 (2020). https://doi.org/10.1038/s41746-020-0226-6


## Previous Studies utilizing Dataset

Previous studies utilizing this dataset include the [original study examining inaccuracies in optical heart rate measurements from wearable sensors](https://www.nature.com/articles/s41746-020-0226-6) and a study on [data compression of wearable sensors](https://www.mdpi.com/1424-8220/21/2/516). Other studies are ongoing.


## Dataset Format and Structure
The dataset is in a .csv and contains 10 columns:

* ECG = heart rate (HR) reported by Bittium Faros 180 ECG Patch (beats per minute, bpm) (~1000 Hz)

* Apple Watch = HR reported by Apple Watch (bpm) (variable sampling frequency)

* Empatica = HR reported by Empatica E4 (bpm) (~1Hz)

* Garmin = HR reported by Garmin (bpm) (variable sampling frequency)

* Fitbit = HR reported by Fitbit (bpm) (variable sampling frequency)

* Miband = HR reported by Xiaomi Miband (bpm) (variable sampling frequency)

* Biovotion = HR reported by Biovotion Everion (bpm) (~1Hz)

* ID = internal study ID

* Skin Tone = skin tone of participant (standard Fitzpatrick skin tone scale, 1-6)

* Activity = the activity a participant was participating in (Rest, Activity, Breathe, Type). For a complete description of these conditions, please see the associated publication.

## Additional Usage Information
For a full description of the data and the protocol, please visit the [original study](https://www.nature.com/articles/s41746-020-0226-6).