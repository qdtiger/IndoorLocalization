# Datasets for indoor localization

Indoor localization research has drawn much attention recently. However,  comparison of different methods cannot be comprehensively conducted owing to the lack of standardized datasets. For fair comparison, we find the following datasets, including WiFi, INS, UWB, Bluetooth, etc.    

## WiFi fingerprinting

|                             Name                             |                        #Samples                         |                        #APs                        | Main Features                                                | Reference |
| :----------------------------------------------------------: | :-----------------------------------------------------: | :------------------------------------------------: | :----------------------------------------------------------- | :-------: |
| [IPIN 2016 Tutorial](http://indoorlocplatform.uji.es/databases/get/2/) |                          1629                           |                        168                         | Crowd  sourced RSS database collected by 8 students. Only a small corridor was covered ($\approx$120 m$^2$. The data can be used for fingerprinting. |    [1]    |
| [TUT dataset](http://www.cs.tut.fi/tlt/pos/MEASUREMENTS_WLAN_FOR_WEB.zip) | Building1: 1476 Building1_NEW: 505       Building2: 584 | Building1: 309 Building1_NEW:  238  Building2: 354 | Three small datasets collected with one device each. The data can be used for fingerprinting, path loss models, and tracking. |    [2]    |
| [uiuc/uim dataset](http://crawdad.org/uiuc/uim/20120124/) (Need to create an account) |                            \                            |                         13                         | A Wi-Fi trace file collected by 28 people for analyzing human movement. This is not a database for indoor positioning. |    [3]    |
| [Fingerprint tracest from mannheim/compass dataset](https://crawdad.org/mannheim/compass/20080411/fingerprint/) (Need to create an account) |                          14300                          |                         27                         | A traceset of RSS collected from 802.11 APs . It can be used for fingerprinting, tracking. |    [4]    |
| [UJIIndoorLoc Database](https://archive.ics.uci.edu/ml/datasets/ujiindoorloc) |                          25948                          |                        520                         | Database collected at 3 different buildings with 4 floors each.This dataset can be used for building and floor identification. |    [5]    |
| [Indoor User Movement Prediction from RSSI dataset](https://archive.ics.uci.edu/ml/datasets/Indoor+User+Movement+Prediction+from+RSS+data) |                          13197                          |                         4                          | Data collected during user movements at the frequency of 8 Hz (8 samples per second). The data can be used for predicting the pattern of user movements. |    [6]    |
| [Geotec Database](http://indoorloc.uji.es/databases/geotecDatabaseWGS.zip) |       680 training samples,  460 testing samples        |                         97                         | The data can be used for fingerprinting.                     |    [7]    |
| [Alcalá tutorial database](http://indoorlocplatform.uji.es/databases/get/4/) |                          1075                           |                        152                         | The data can be used for fingerprinting.                     |    [8]    |
| [Crowdsourced WiFi fingerprinting database](https://zenodo.org/record/1001662#.XTQGbugzaUk) |                          4638                           |                        991                         | Data collected via 21 different devices and users. The data can be used for crowdsourced fingerprinting. |    [9]    |
| [Long-term fingerprint dataset](https://zenodo.org/record/1478083#.XTPcS-gzaUk) |                         103584                          |                        576                         | Data collected by one person during 25 months at a two floor building. The data can enable  the analysis of long-term variations in WiFi fingerprints. |   [10]    |

## UWB

|                             Name                             |                        Main Features                         | Reference |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :-------: |
| [UWB LOS and NLOS Dataset](https://github.com/ewine-project/UWB-LOS-NLOS-Data-Set) | Measurements were taken on 7 different indoor scenarios. Each scenario collected 3000 LoS samples and 3000 NLoS samples. |   [11]    |



## INS

|                             Name                             |      #Samples      |                        Main Features                         | Reference |
| :----------------------------------------------------------: | :----------------: | :----------------------------------------------------------: | :-------: |
| [EuRoC MAV](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) |   11 seqs, 0.9km   |                                                              |   [12]    |
| [TUM VI](https://vision.in.tum.de/data/datasets/visual-inertial-dataset) |   28 seqs, 20km    |                                                              |   [13]    |
|        [ADVIO](https://github.com/AaltoVision/ADVIO)         |   23 seqs, 4.5km   |                                                              |   [14]    |
|             [OxIOD](http://deepio.cs.ox.ac.uk/)              | 158 seqs, 42.587km | The measurements were collected with four different attachments (handheld, in the pocket, in the handbag and on the trolley), four motion modes (halting, walking slowly, walking normally, and running), five different users, four types of off-the-shelf consumer phones, and large-scale localization from office buildings. |   [15]    |
| [IPIN 2018 Competition Track 4](https://zenodo.org/record/3228012#.XS7XTugzaUk) |         \          |                                                              |     \     |
|         [NaveGo](https://github.com/rodralez/NaveGo)         |         \          | NaveGo is an open-source MATLAB/GNU Octave toolbox for processing integrated navigation systems and simulating inertial sensors and a GNSS receiver. |   [16]    |

## mmWave

|                   Name                   |                    Main Features                     | Reference |
| :--------------------------------------: | :--------------------------------------------------: | :-------: |
| [DeepMIMO](http://www.deepmimo.net/?i=1) | A  generic dataset for mmWave/massive MIMO channels. |   [17]    |

## Hybrid

|                             Name                             |                 Measurement                 |                        Main Features                         | Reference |
| :----------------------------------------------------------: | :-----------------------------------------: | :----------------------------------------------------------: | :-------: |
| [IPIN 2016 Competition](http://indoorloc.uji.es/ipin2016track3/) | RSS, accelerometer, gyroscope, magnetometer |     Data collected at a total of 4 different buildings.      |   [18]    |
| [IPIN 2017 Competition Track 3](http://www.ipin2017.org/callforcompetition.html) | RSS, accelerometer, gyroscope, magnetometer |                                                              |   [19]    |
| [WiFi RSSI, Bluetooth and magnetometer dataset](https://archive.ics.uci.edu/ml/datasets/Hybrid+Indoor+Positioning+Dataset+from+WiFi+RSSI%2C+Bluetooth+and+magnetometer) |              RSS, magnetometer              | The measurements were recorded by the same kind of Android devices in a three-story building. The recording was preformed at weekend to reduce the noise of the environment. |   [20]    |
| [Geo-Magnetic field and WLAN  dataset](https://archive.ics.uci.edu/ml/datasets/Geo-Magnetic+field+and+WLAN+dataset+for+indoor+localisation+from+wristband+and+smartphone) | RSS, accelerometer, gyroscope, magnetometer | Data collected from a smartwatch and a smartphone worn by users. |   [21]    |

[1] Montoliu, R.; Sansano, E.; Torres-Sospedra, J.; Belmonte, O. IndoorLoc Platform: A Public Repository for
Comparing and Evaluating Indoor Positioning Systems. In Proceedings of the 2017 International Conference
on Indoor Positioning and Indoor Navigation (IPIN), Sapporo, Japan, 18–21 September 2017.

[2] Lohan, E.; Talvitie, J. TUT Datasets. Available online: http://www.cs.tut.fi/tlt/pos/Software.htm
(accessed on 21 July 2019).

[3] Nahrstedt, K.; Vu, L. CRAWDAD Dataset Uiuc/Uim (v. 2012-01-24). Available online: http://crawdad.org/uiuc/uim/20120124 (accessed on 21 July 2019).

[4] King, T.; Kopf, S.; Haenselmann, T.; Lubberger, C.; Effelsberg, W. CRAWDAD Dataset Mannheim/Compass
(v. 2008-04-11). Available online: https://crawdad.org/mannheim/compass/20080411/fingerprint  (accessed on 21 July 2019).

[5] J. Torres-Sospedra, R. Montoliu, A. M. Uso, J. P. Avariento, T. J. Arnau, ´ M. Benedito-Bordonau, and J. Huerta, “Ujiindoorloc: A new multibuilding and multi-floor database for WLAN fingerprint-based indoor localization problems,” in Proceedings of the 2014 International Conference on Indoor Positioning and Indoor Navigation (IPIN’14), 2014, pp. 261–270.

[6] Bacciu, D.; Barsocchi, P.; Chessa, S.; Gallicchio, C.; Micheli, A. Indoor User Movement Prediction from
RSS Data Data Set. Available online: https://archive.ics.uci.edu/ml/datasets/Indoor+User+Movement+
Prediction+from+RSS+data (accessed on 21 July 2019).

[7] Torres-Sospedra, J.; Montoliu, R.; Mendoza-Silva, G.M.; Belmonte, O.; Rambla, D.; Huerta, J. Geotec Database. Available online: http://indoorloc.uji.es/databases/geotecDatabaseWGS.zip (accessed on 21 July 2019).

[8] Montoliu, R.; Sansano, E.; Torres-Sospedra, J.; Belmonte, O. IndoorLoc Platform Databases. Available online: http://indoorlocplatform.uji.es/databases/get/4/ (accessed on 21 July 2019).

[9] Lohan, E.S.; Torres-Sospedra, J.; Leppäkoski, H.; Richter, P.; Peng, Z.; Huerta, J. Wi-Fi Crowdsourced
Fingerprinting Dataset for Indoor Positioning. Data 2017, 2, 32.

[10] G.M. Mendoza-Silva, P. Richter, J. Torres-Sospedra, E.S. Lohan, J. Huerta, "Long-Term Wi-Fi fingerprinting dataset and supporting material", Zenodo repository, DOI 10.5281/zenodo.1066041.

[11] K. Bregar, A. Hrovat, and M. Mohorˇciˇc, “Nlos channel detection with multilayer perceptron in low-rate personal area networks for indoor localization accuracy improvement,” in Proceedings of the 8th Joˇzef Stefan International Postgraduate School Students’ Conference, Ljubljana, Slovenia, 2016.

[12] M. Burri, J. Nikolic, P. Gohl, T. Schneider, J. Rehder, S. Omari, M. W. Achtelik, and R. Siegwart, “The euroc micro aerial vehicle datasets,” The International Journal of Robotics Research, vol. 35, no. 10, pp. 1157–1163, 2016.

[13] D. Schubert, T. Goll, N. Demmel, V. Usenko, J. St¨uckler, and D. Cremers, “The tum vi benchmark for evaluating visual-inertial odometry,” in Proc. IEEE  IROS, pp. 1680–1687, 2018.

[14] S. Cort´es, A. Solin, E. Rahtu, and J. Kannala, “Advio: An authentic dataset for visual-inertial odometry,” in Proc. ECCV, pp. 419–434, 2018.

[15] Chen C, Zhao P, Lu C X, et al. OxIOD: The Dataset for Deep Inertial Odometry[J]. arXiv preprint arXiv:1809.07491, 2018.

[16] R. Gonzalez, J. I. Giribet, and H. D. Patino, “Navego: a simulation framework for low-cost integrated navigation systems,” Journal of Control Engineering and Applied Informatics, vol. 17, no. 2, pp. 110–120, 2015.

[17] The DeepMIMO paper: A. Alkhateeb,"[DeepMIMO: A Generic Deep Learning Dataset for Millimeter Wave and Massive MIMO Applications](https://arxiv.org/pdf/1902.06435.pdf) ,"in Proc. of Information Theory and Applications Workshop (ITA), San Diego, CA, Feb. 2019.

[18] Torres-Sospedra, J.; Jiménez, A.R.; Knauth, S.; Moreira, A.; Beer, Y.; Fetzer, T.; Ta, V.C.; Montoliu, R.; Seco, F.; Mendoza-Silva, G.M.; et al. The Smartphone-Based Offline Indoor Location Competition at IPIN 2016: Analysis and FutureWork. Sensors 2017, 17, 557.

[19] IPIN 2017 Competition Datasets. Available online: http://www.ipin2017.org/callforcompetition.html
(accessed on 27 July 2019).

[20] Z. T´oth and J. Tam´as, “Miskolc iis hybrid ips: Dataset for hybrid indoor positioning,” in 2016 26th International Conference Radioelektronika (RADIOELEKTRONIKA). IEEE, 2016, pp. 408–412.

[21] P. Barsocchi, A. Crivello, D. La Rosa, and F. Palumbo, “A multisource and multivariate dataset for indoor localization methods based on WLAN and geo-magnetic field fingerprinting,” in Proc. IEEE IPIN, pp. 1–8, 2016.



