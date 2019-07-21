# Datasets for indoor localization

Indoor localization research has drawn much attention recently. However,  comparison of different methods cannot be comprehensively conducted owing to the lack of standardized datasets. For fair comparison, we find the following datasets, including WiFi, INS, UWB, Bluetooth, etc.    

## WiFi

|                             Name                             | Measurement |                #Samples                 | #APs |   #Environment Size   | Reference |
| :----------------------------------------------------------: | :---------: | :-------------------------------------: | :--: | :-------------------: | :-------: |
| [IPIN 2016 Tutorial](http://indoorlocplatform.uji.es/databases/get/2/) |     RSS     |                  1629                   | 168  |                       |    [1]    |
|                    IPIN 2016 Competition                     |     RSS     |                                         |      |                       |    [2]    |
|                    IPIN 2017 Competition                     |     RSS     |                                         |      |                       |           |
|   [TUT dataset](http://www.cs.tut.fi/tlt/pos/Software.htm)   |     RSS     | one fingerprint per Reference Point(RP) |      |                       |    [4]    |
|  [uiuc/uim dataset](http://crawdad.org/uiuc/uim/20120124/)   |     RSS     |                                         |  13  |       221 m$^2$       |    [5]    |
|              [kth/rss dataset](kth/rss dataset)              |     RSS     |                                         |      |                       |    [6]    |
| [Fingerprint tracest from mannheim/compass dataset](https://crawdad.org/mannheim/compass/20080411/fingerprint/) |     RSS     |           110 samples per RP            |      |       221 m$^2$       |    [7]    |
| [UJIIndoorLoc Database](https://archive.ics.uci.edu/ml/datasets/ujiindoorloc) |     RSS     |                  25948                  | 520  |       110 m$^2$       |    [8]    |
| [Indoor User Movement Prediction from RSSI dataset](https://archive.ics.uci.edu/ml/datasets/Indoor+User+Movement+Prediction+from+RSS+data) |     RSS     |                  13197                  |  4   |                       |    [9]    |
| [Geotec Database](http://indoorloc.uji.es/databases/geotecDatabaseWGS.zip) |     RSS     |            5 samples per RP             |      |                       |   [10]    |
| [Alcalá tutorial database](http://indoorlocplatform.uji.es/databases/get/4/) |     RSS     |                  1075                   | 152  |                       |   [11]    |
| [Crowdsourced WiFi fingerprinting database](https://zenodo.org/record/1001662#.XTQGbugzaUk) |     RSS     |                  4638                   | 991  | a five-story building |   [12]    |
| [Long-term fingerprint dataset](https://zenodo.org/record/1478083#.XTPcS-gzaUk) |     RSS     |                 103584                  | 576  |      308.4 m$^2$      |   [13]    |

## Bluetooth

## UWB

## INS

|                             Name                             |       Measurement       |      #Samples      |      |                          Code                           | Reference |
| :----------------------------------------------------------: | :---------------------: | :----------------: | ---- | :-----------------------------------------------------: | :-------: |
|                            KITTI                             |                         |  22 seqs, 39.2km   |      |                                                         |           |
|                          EuRoC MAV                           |                         |   11 seqs, 0.9km   |      |                                                         |           |
|                       Oxford RobotCar                        |                         |     1010.46km      |      |                                                         |           |
|                            TUM VI                            |                         |   28 seqs, 20km    |      |                                                         |           |
|                            ADVIO                             |                         |   23 seqs, 4.5km   |      |                                                         |           |
|             [OxIOD](http://deepio.cs.ox.ac.uk/)              | accelerometer, gyoscope | 158 seqs, 42.587km |      |                                                         |   [14]    |
| [IPIN 2018 Competition Track 4](https://zenodo.org/record/3228012#.XS7XTugzaUk) |                         |                    |      | [1st](https://github.com/rairyuu/PDR-with-Map-Matching) |           |



## Hybrid

|                      Name                      |    Measurement     |      |
| :--------------------------------------------: | :----------------: | ---- |
| WiFi RSSI, Bluetooth and magenetometer dataset | RSSI, magenetomter |      |
|      Geo-Magnetic field and WLAN  dataset      |                    |      |
|                                                |                    |      |
|                                                |                    |      |

[1] Montoliu, R.; Sansano, E.; Torres-Sospedra, J.; Belmonte, O. IndoorLoc Platform: A Public Repository for
Comparing and Evaluating Indoor Positioning Systems. In Proceedings of the 2017 International Conference
on Indoor Positioning and Indoor Navigation (IPIN), Sapporo, Japan, 18–21 September 2017.

[2] Torres-Sospedra, J.; Jiménez, A.R.; Knauth, S.; Moreira, A.; Beer, Y.; Fetzer, T.; Ta, V.C.; Montoliu, R.; Seco, F.; Mendoza-Silva, G.M.; et al. The Smartphone-Based Offline Indoor Location Competition at IPIN 2016: Analysis and FutureWork. Sensors 2017, 17, 557.

[4] Lohan, E.; Talvitie, J. TUT Datasets. Available online: http://www.cs.tut.fi/tlt/pos/Software.htm
(accessed on 21 July 2019).

[5] Nahrstedt, K.; Vu, L. CRAWDAD Dataset Uiuc/Uim (v. 2012-01-24). Available online: http://crawdad.org/uiuc/uim/20120124 (accessed on 21 July 2019).

[6] Parasuraman, R.; Caccamo, S.; Baberg, F.; Ogren, P. CRAWDAD Dataset Kth/Rss (v. 2016-01-05).
Available online: http://crawdad.org/kth/rss/20160105 (accessed on 21 July 2019).

[7] King, T.; Kopf, S.; Haenselmann, T.; Lubberger, C.; Effelsberg, W. CRAWDAD Dataset Mannheim/Compass
(v. 2008-04-11). Available online: https://crawdad.org/mannheim/compass/20080411/fingerprint  (accessed on 21 July 2019).

[8] J. Torres-Sospedra, R. Montoliu, A. M. Uso, J. P. Avariento, T. J. Arnau, ´ M. Benedito-Bordonau, and J. Huerta, “Ujiindoorloc: A new multibuilding and multi-floor database for WLAN fingerprint-based indoor localization problems,” in Proceedings of the 2014 International Conference on Indoor Positioning and Indoor Navigation (IPIN’14), 2014, pp. 261–270.

[9] Bacciu, D.; Barsocchi, P.; Chessa, S.; Gallicchio, C.; Micheli, A. Indoor User Movement Prediction from
RSS Data Data Set. Available online: https://archive.ics.uci.edu/ml/datasets/Indoor+User+Movement+
Prediction+from+RSS+data (accessed on 21 July 2019).

[10] Torres-Sospedra, J.; Montoliu, R.; Mendoza-Silva, G.M.; Belmonte, O.; Rambla, D.; Huerta, J. Geotec Database. Available online: http://indoorloc.uji.es/databases/geotecDatabaseWGS.zip (accessed on 21 July 2019).

[11] Montoliu, R.; Sansano, E.; Torres-Sospedra, J.; Belmonte, O. IndoorLoc Platform Databases. Available online: http://indoorlocplatform.uji.es/databases/get/4/ (accessed on 21 July 2019).

[12] Lohan, E.S.; Torres-Sospedra, J.; Leppäkoski, H.; Richter, P.; Peng, Z.; Huerta, J. Wi-Fi Crowdsourced
Fingerprinting Dataset for Indoor Positioning. Data 2017, 2, 32.

[13] G.M. Mendoza-Silva, P. Richter, J. Torres-Sospedra, E.S. Lohan, J. Huerta, "Long-Term Wi-Fi fingerprinting dataset and supporting material", Zenodo repository, DOI 10.5281/zenodo.1066041.

[14] Chen C, Zhao P, Lu C X, et al. OxIOD: The Dataset for Deep Inertial Odometry[J]. arXiv preprint arXiv:1809.07491, 2018.

