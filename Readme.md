# CONVID-19-datasets
|数据集|图像格式|标签格式|任务|下载|大小|时间|
|---|---|---|---|---|---|---|
|covid-chestxray-dataset|PNG|CSV|分类|[直接下载](https://github.com/ieee8023/covid-chestxray-dataset)|1 GB|2021|
|COVIDGR datasets|PNG|CSV|分类|[直接下载](https://github.com/ari-dasci/OD-covidgr)|1 GB|2020|
|Novel COVID-19 Chestxray Repository|PNG|CSV|分类|[直接下载](https://www.kaggle.com/datasets/subhankarsen/novel-covid19-chestxray-repository)|1.41 GB|2021|
|Synthetic COVID-19 CXR Dataset|PNG|CSV|分类|[直接下载](https://github.com/hasibzunair/synthetic-covid-cxr-dataset)|0.5 GB|2020|
|BrixIA (BrixIA Covid-19)|DICOM|CSV|分类（打分）|[需要申请](https://brixia.github.io/)|1 GB|2020|
|Tuberculosis Chest X-rays (Shenzhen)|PNG|CSV|分类|[直接下载](https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen)|3.77 GB|2014|
|NIH Chest X-rays|PNG|CSV|分类、检测|[直接下载](https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345)|45.7 GB|2017|
|VinBigData Chest X-ray Abnormalities Detection|DICOM|CSV|分类|[直接下载](https://vindr.ai/datasets/cxr)、[需要申请](https://vindr.ai/datasets/cxr)|1 GB|2020|

# cite
## covid-chestxray-dataset
```
@article{MAGUOLO20211,
title = {A critic evaluation of methods for COVID-19 automatic detection from X-ray images},
journal = {Information Fusion},
volume = {76}, pages = {1-7}, year = {2021},
issn = {1566-2535},
doi = {https://doi.org/10.1016/j.inffus.2021.04.008},
author = {Gianluca Maguolo and Loris Nanni}
}
```
```
@Article{ijerph17186933,
TITLE = {Unveiling COVID-19 from CHEST X-Ray with Deep Learning: A Hurdles Race with Small Data},
AUTHOR = {Tartaglione, Enzo and Barbano, Carlo Alberto and Berzovini, Claudio and Calandri, Marco and Grangetto, Marco},
JOURNAL = {International Journal of Environmental Research and Public Health},
VOLUME = {17}, YEAR = {2020}, NUMBER = {18},
ARTICLE-NUMBER = {6933},
PubMedID = {32971995},
ISSN = {1660-4601},
DOI = {10.3390/ijerph17186933}
}
```

## COVIDGR datasets
```
@misc{tabik2020covidgr,
    title={COVIDGR dataset and COVID-SDNet methodology for predicting COVID-19 based on Chest X-Ray images},
    author={S. Tabik and A. Gómez-Ríos and J. L. Martín-Rodríguez and I. Sevillano-García and M. Rey-Area and D. Charte and E. Guirado and J. L. Suárez and J. Luengo and M. A. Valero-González and P. García-Villanova and E. Olmedo-Sánchez and F. Herrera},
    year={2020},
    eprint={2006.01409},
    archivePrefix={arXiv},
    primaryClass={eess.IV}
}
```

## Novel COVID-19 Chestxray Repository
```
@article{bhowal2021choquet,
  title={Choquet Integral and Coalition Game-based Ensemble of Deep Learning Models for COVID-19 Screening from Chest X-ray Images},
  author={Bhowal, Pratik and Sen, Subhankar and Yoon, Jin Hee and Geem, Zong Woo and Sarkar, Ram},
  journal={IEEE Journal of Biomedical and Health Informatics},
  year={2021},
  publisher={IEEE}
}
```

## Synthetic COVID-19 CXR Dataset
```
@article{zunair2021synthesis,
  title={Synthesis of {COVID}-19 chest {X}-rays using unpaired image-to-image translation},
  author={Zunair, Hasib and Hamza, A Ben},
  journal={Social Network Analysis and Mining},
  volume={11},
  number={1},
  pages={1--12},
  year={2021},
  publisher={Springer}
}
```

## BrixIA (BrixIA Covid-19)
```
@article{borghesi2020covid,
  title={COVID-19 outbreak in Italy: experimental chest X-ray scoring system for quantifying and monitoring disease progression},
  author={Borghesi, Andrea and Maroldi, Roberto},
  journal={La radiologia medica},
  volume={125},
  pages={509-513},
  year={2020},
  publisher={Springer}
}
```
```
@article{BS-Net2021,
title = {BS-Net: learning COVID-19 pneumonia severity on a large Chest X-Ray dataset},
journal = {Medical Image Analysis},
pages = {102046},
year = {2021},
issn = {1361-8415},
doi = {https://doi.org/10.1016/j.media.2021.102046},
author = {Alberto Signoroni and Mattia Savardi and Sergio Benini and Nicola Adami and Riccardo Leonardi and Paolo Gibellini and Filippo Vaccher and Marco Ravanelli and Andrea Borghesi and Roberto Maroldi and Davide Farina},
}
```

## Tuberculosis Chest X-rays (Shenzhen)
```
@article{shenzhenTuberculosis,
title={Two public chest X-ray datasets for computer-aided screening of pulmonary diseases},
author={Jaeger, Stefan and Candemir, Sema and Antani, Sameer and Wáng, Yì-Xiáng J and Lu, Pu-Xuan and Thoma, George},
journal={Quantitative imaging in medicine and surgery},
volume={4},
pages={6},
year={2014},
issn = {2223-4292.2014.11.20},
doi = {https://doi.org/10.3978/j},
}
```

## NIH Chest X-rays
```
@INPROCEEDINGS{8099852,
  author={Wang, Xiaosong and Peng, Yifan and Lu, Le and Lu, Zhiyong and Bagheri, Mohammadhadi and Summers, Ronald M.},
  booktitle={2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  title={ChestX-Ray8: Hospital-Scale Chest X-Ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases},
  year={2017},
  volume={},
  number={},
  pages={3462-3471},
  doi={10.1109/CVPR.2017.369}}
```
## VinBigData Chest X-ray Abnormalities Detection
```
@misc{nguyen2020vindrcxr,
      title={VinDr-CXR: An open dataset of chest X-rays with radiologist's annotations},
      author={Ha Q. Nguyen and Khanh Lam and Linh T. Le and Hieu H. Pham and Dat Q. Tran and Dung B. Nguyen and Dung D. Le and Chi M. Pham and Hang T. T. Tong and Diep H. Dinh and Cuong D. Do and Luu T. Doan and Cuong N. Nguyen and Binh T. Nguyen and Que V. Nguyen and Au D. Hoang and Hien N. Phan and Anh T. Nguyen and Phuong H. Ho and Dat T. Ngo and Nghia T. Nguyen and Nhan T. Nguyen and Minh Dao and Van Vu},
      year={2020},
      eprint={2012.15029},
      archivePrefix={arXiv},
      primaryClass={eess.IV}
}
```
