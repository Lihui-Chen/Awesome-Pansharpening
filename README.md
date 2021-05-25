# Awesome-Pansharpening
This repository collects pan-sharpening methods (focus on deep learning based methods), codes, and datasets. 

## Contents

1. [Survey](#Survey)
2. [Performance Assessment](#Performance-Assessment)
3. [CS-based Methods](#3.-Component-Substitute-(CS)-Based-Pansharpening)
4. [MRA-based Methods](#4.-Multi-Resolution-Analysis-(MRA)-Based-Pansharpening)
5. [MO-based Methods](#5. Model Optimization Based Pansharpening)
6. [DL-based Methods](#6. Deep Learning Based Pansharpening)
7. [Challenges](#7. Challenges In Pansharpening)



## Survey

1. F. Laporterie-Déjean, H. de Boissezon, G. Flouzat, and M.-J. Lefèvre-Fonollosa, “Thematic and statistical evaluations of five panchromatic/multispectral fusion methods on simulated PLEIADES-HR images,” *Information Fusion*, vol. 6, no. 3, pp. 193–212, Sep. 2005, doi: [10.1016/j.inffus.2004.06.006](https://doi.org/10.1016/j.inffus.2004.06.006).
2. C. Thomas, T. Ranchin, L. Wald, and J. Chanussot, “Synthesis of Multispectral Images to High Spatial Resolution: A Critical Review of Fusion Methods Based on Remote Sensing Physics,” *IEEE Transactions on Geoscience and Remote Sensing*, vol. 46, no. 5, pp. 1301–1312, May 2008, doi: [10.1109/TGRS.2007.912448](https://doi.org/10.1109/TGRS.2007.912448).
3. J. Marcello, A. Medina, and F. Eugenio, “Evaluation of Spatial and Spectral Effectiveness of Pixel-Level Fusion Techniques,” *IEEE Geoscience and Remote Sensing Letters*, vol. 10, no. 3, pp. 432–436, May 2013, doi: [10.1109/LGRS.2012.2207944](https://doi.org/10.1109/LGRS.2012.2207944).
4. K. Kpalma, M. C. El-Mezouar, and N. Taleb, “Recent Trends in Satellite Image Pan-sharpening techniques,”  1st International Conference on Electrical, Electronic and Computing Engineering, Jun 2014, Vrniacka Banja, Serbia. ffhal-01075703
5. G. Vivone *et al.*, “A Critical Comparison Among Pansharpening Algorithms,” *IEEE Trans. Geosci. Remote Sensing*, vol. 53, no. 5, pp. 2565–2586, May 2015, doi: [10.1109/TGRS.2014.2361734](https://doi.org/10.1109/TGRS.2014.2361734). [[codes](https://openremotesensing.net/knowledgebase/a-critical-comparison-among-pansharpening-algorithms/)]
6. L. Loncan *et al.*, “Hyperspectral Pansharpening: A Review,” *IEEE Geosci. Remote Sens. Mag.*, vol. 3, no. 3, pp. 27–46, Sep. 2015, doi: [10.1109/MGRS.2015.2440094](https://doi.org/10.1109/MGRS.2015.2440094).
7. X. Meng, H. Shen, H. Li, L. Zhang, and R. Fu, “Review of the pansharpening methods for remote sensing images based on the idea of meta-analysis: Practical discussion and challenges,” *Information Fusion*, vol. 46, pp. 102–113, Mar. 2019, doi: [10.1016/j.inffus.2018.05.006](https://doi.org/10.1016/j.inffus.2018.05.006). 
8. G. Vivone *et al.*, “A New Benchmark Based on Recent Advances in Multispectral Pansharpening: Revisiting Pansharpening With Classical and Emerging Pansharpening Methods,” *IEEE Geosci. Remote Sens. Mag.*, vol. 9, no. 1, pp. 53–81, Mar. 2021, doi: [10.1109/MGRS.2020.3019315](https://doi.org/10.1109/MGRS.2020.3019315). 
9. X. Meng *et al.*, “A Large-Scale Benchmark Data Set for Evaluating Pansharpening Performance: Overview and Implementation,” *IEEE Geosci. Remote Sens. Mag.*, vol. 9, no. 1, pp. 18–52, Mar. 2021, doi: [10.1109/MGRS.2020.2976696](https://doi.org/10.1109/MGRS.2020.2976696).

## Performance-Assessment

1. L. Wald, T. Ranchin, and M. Mangolini, “Fusion of satellite images of different spatial resolutions: Assessing the quality of resulting images,” *Photogrammetric engineering and remote sensing*, vol. 63, no. 6, pp. 691–699, 1997.

2. L. Alparone, S. Baronti, A. Garzelli, and F. Nencini, “A global quality measurement of pan-sharpened multispectral imagery,” *IEEE Geoscience and Remote Sensing Letters*, vol. 1, no. 4, pp. 313–317, Oct. 2004, doi: [10.1109/LGRS.2004.836784](https://doi.org/10.1109/LGRS.2004.836784).

3. C. Thomas and L. Wald, “Analysis of Changes in Quality Assessment with Scale,” in *2006 9th International Conference on Information Fusion*, Jul. 2006, pp. 1–5. doi: [10.1109/ICIF.2006.301595](https://doi.org/10.1109/ICIF.2006.301595).

4. Q. Du, N. H. Younan, R. King, and V. P. Shah, “On the Performance Evaluation of Pan-Sharpening Techniques,” *IEEE Geoscience and Remote Sensing Letters*, vol. 4, no. 4, pp. 518–522, Oct. 2007, doi: [10.1109/LGRS.2007.896328](https://doi.org/10.1109/LGRS.2007.896328).

5. L. Alparone, B. Aiazzi, S. Baronti, A. Garzelli, F. Nencini, and M. Selva, “Multispectral and Panchromatic Data Fusion Assessment Without Reference,” *PHOTOGRAMMETRIC ENGINEERING*, Vol. 74, No. 2, February 2008, pp. 193–200.

6. M. M. Khan, L. Alparone, and J. Chanussot, “Pansharpening Quality Assessment Using the Modulation Transfer Functions of Instruments,” *IEEE Transactions on Geoscience and Remote Sensing*, vol. 47, no. 11, pp. 3880–3891, Nov. 2009, doi: [10.1109/TGRS.2009.2029094](https://doi.org/10.1109/TGRS.2009.2029094).

7. B. Aiazzi, L. Alparone, S. Baronti, R. Carlà, A. Garzelli, and L. Santurri, “Full-scale assessment of pansharpening methods and data products,” in *Image and Signal Processing for Remote Sensing XX*, Oct. 2014, vol. 9244, p. 924402. doi: [10.1117/12.2067770](https://doi.org/10.1117/12.2067770).

8. R. Carla, L. Santurri, B. Aiazzi, and S. Baronti, “Full-Scale Assessment of Pansharpening Through Polynomial Fitting of Multiscale Measurements,” *IEEE Trans. Geosci. Remote Sensing*, vol. 53, no. 12, pp. 6344–6355, Dec. 2015, doi: [10.1109/TGRS.2015.2436699](https://doi.org/10.1109/TGRS.2015.2436699).

9. W. Dou, “Image Degradation for Quality Assessment of Pan-Sharpening Methods,” *Remote Sensing*, vol. 10, no. 2, p. 154, Jan. 2018, doi: [10.3390/rs10010154](https://doi.org/10.3390/rs10010154).

10. M. Selva, L. Santurri, and S. Baronti, “On the Use of the Expanded Image in Quality Assessment of Pansharpened Images,” *IEEE Geosci. Remote Sensing Lett.*, vol. 15, no. 3, pp. 320–324, Mar. 2018, doi: [10.1109/LGRS.2017.2777916](https://doi.org/10.1109/LGRS.2017.2777916).

11. G. Vivone, R. Restaino, and J. Chanussot, “A Bayesian Procedure for Full-Resolution Quality Assessment of Pansharpened Products,” *IEEE Trans. Geosci. Remote Sensing*, vol. 56, no. 8, pp. 4820–4834, Aug. 2018, doi: [10.1109/TGRS.2018.2839564](https://doi.org/10.1109/TGRS.2018.2839564).

12. O. A. Agudelo-Medina, H. D. Benitez-Restrepo, G. Vivone, and A. Bovik, “Perceptual Quality Assessment of Pan-Sharpened Images,” *Remote Sensing*, vol. 11, no. 7, p. 877, Apr. 2019, doi: [10.3390/rs11070877](https://doi.org/10.3390/rs11070877).

    

## 3. Component Substitute (CS)-Based Pansharpening

## 4. Multi Resolution Analysis (MRA)-Based Pansharpening

## 

## 5. Model Optimization Based Pansharpening

## 6. Deep Learning Based Pansharpening

### 6.1 Supervised Methods

1. Wei Huang, Liang Xiao, Zhihui Wei, Hongyi Liu, and Songze Tang, “A New Pan-Sharpening Method With Deep Neural Networks,” *IEEE Geosci. Remote Sensing Lett.*, vol. 12, no. 5, pp. 1037–1041, May 2015, doi: [10.1109/LGRS.2014.2376034](https://doi.org/10.1109/LGRS.2014.2376034).
2. G. Masi, D. Cozzolino, L. Verdoliva, and G. Scarpa, “Pansharpening by Convolutional Neural Networks,” *Remote Sensing*, vol. 8, no. 7, Art. no. 7, Jul. 2016, doi: [10.3390/rs8070594](https://doi.org/10.3390/rs8070594).
3. A. Azarang and H. Ghassemian, “A new pansharpening method using multi resolution analysis framework and deep neural networks,” in *2017 3rd International Conference on Pattern Recognition and Image Analysis (IPRIA)*, Shahrekord, Iran, Apr. 2017, pp. 1–6. doi: [10.1109/PRIA.2017.7983017](https://doi.org/10.1109/PRIA.2017.7983017).
4. N. Li, N. Huang, and L. Xiao, “PAN-Sharpening via residual deep learning,” in *2017 IEEE International Geoscience and Remote Sensing Symposium (IGARSS)*, Jul. 2017, pp. 5133–5136. doi: [10.1109/IGARSS.2017.8128158](https://doi.org/10.1109/IGARSS.2017.8128158).
5. G. Masi, D. Cozzolino, L. Verdoliva, and G. Scarpa, “CNN-based pansharpening of multi-resolution remote-sensing images,” in *2017 Joint Urban Remote Sensing Event (JURSE)*, Dubai, United Arab Emirates, Mar. 2017, pp. 1–4. doi: [10.1109/JURSE.2017.7924534](https://doi.org/10.1109/JURSE.2017.7924534).
6. Y. Wei and Q. Yuan, “Deep residual learning for remote sensed imagery pansharpening,” in *2017 International Workshop on Remote Sensing with Intelligent Processing (RSIP)*, Shanghai, China, May 2017, pp. 1–4. doi: [10.1109/RSIP.2017.7958794](https://doi.org/10.1109/RSIP.2017.7958794).
7. Y. Wei, Q. Yuan, H. Shen, and L. Zhang, “Boosting the Accuracy of Multispectral Image Pansharpening by Learning a Deep Residual Network,” *IEEE Geosci. Remote Sensing Lett.*, vol. 14, no. 10, pp. 1795–1799, Oct. 2017, doi: [10.1109/LGRS.2017.2736020](https://doi.org/10.1109/LGRS.2017.2736020).
8. J. Yang, X. Fu, Y. Hu, Y. Huang, X. Ding, and J. Paisley, “PanNet: A Deep Network Architecture for Pan-Sharpening,”  ICCV2017, https://openaccess.thecvf.com/content_iccv_2017/html/Yang_PanNet_A_Deep_ICCV_2017_paper.html
9. X. Liu, Y. Wang, and Q. Liu, “Psgan: A Generative Adversarial Network for Remote Sensing Image Pan-Sharpening,” in *2018 25th IEEE International Conference on Image Processing (ICIP)*, Oct. 2018, pp. 873–877. doi: [10.1109/ICIP.2018.8451049](https://doi.org/10.1109/ICIP.2018.8451049).
10. G. Scarpa, S. Vitale, and D. Cozzolino, “Target-Adaptive CNN-Based Pansharpening,” *IEEE Trans. Geosci. Remote Sensing*, vol. 56, no. 9, pp. 5443–5457, Sep. 2018, doi: [10.1109/TGRS.2018.2817393](https://doi.org/10.1109/TGRS.2018.2817393).
11. S. Vitale, G. Ferraioli, and G. Scarpa, “A CNN-Based Model for Pansharpening of WorldView-3 Images,” in *IGARSS 2018 - 2018 IEEE International Geoscience and Remote Sensing Symposium*, Valencia, Jul. 2018, pp. 5108–5111. doi: [10.1109/IGARSS.2018.8519202](https://doi.org/10.1109/IGARSS.2018.8519202).
12. Q. Yuan, Y. Wei, X. Meng, H. Shen, and L. Zhang, “A Multiscale and Multidepth Convolutional Neural Network for Remote Sensing Imagery Pan-Sharpening,” *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, vol. 11, no. 3, pp. 978–989, Mar. 2018, doi: [10.1109/JSTARS.2018.2794888](https://doi.org/10.1109/JSTARS.2018.2794888).
13. K. Doi and A. Iwasaki, “SSCNET: Spectral-Spatial Consistency Optimization of CNN for Pansharpening,” in *IGARSS 2019 - 2019 IEEE International Geoscience and Remote Sensing Symposium*, Jul. 2019, pp. 3141–3144. doi: [10.1109/IGARSS.2019.8897928](https://doi.org/10.1109/IGARSS.2019.8897928).
14. F. Palsson, J. R. Sveinsson, and M. O. Ulfarsson, “Optimal Component Substitution and Multi-Resolution Analysis Pansharpening Methods Using a Convolutional Neural Network,” in *IGARSS 2019 - 2019 IEEE International Geoscience and Remote Sensing Symposium*, Yokohama, Japan, Jul. 2019, pp. 3177–3180. doi: [10.1109/IGARSS.2019.8899299](https://doi.org/10.1109/IGARSS.2019.8899299).
15. S. Vitale, “A CNN-Based Pansharpening Method with Perceptual Loss,” in *IGARSS 2019 - 2019 IEEE International Geoscience and Remote Sensing Symposium*, Yokohama, Japan, Jul. 2019, pp. 3105–3108. doi: [10.1109/IGARSS.2019.8900390](https://doi.org/10.1109/IGARSS.2019.8900390).
16. Z. Xiang, L. Xiao, P. Liu, and Y. Zhang, “A Multi-Scale Densely Deep Learning Method for Pansharpening,” in *IGARSS 2019 - 2019 IEEE International Geoscience and Remote Sensing Symposium*, Yokohama, Japan, Jul. 2019, pp. 2786–2789. doi: [10.1109/IGARSS.2019.8898095](https://doi.org/10.1109/IGARSS.2019.8898095).
17. L. Zhang, J. Zhang, X. Lyu, and J. Ma, “A New Pansharpening Method Using Objectness Based Saliency Analysis and Saliency Guided Deep Residual Network,” in *2019 IEEE International Conference on Image Processing (ICIP)*, Taipei, Taiwan, Sep. 2019, pp. 4529–4533. doi: [10.1109/ICIP.2019.8803477](https://doi.org/10.1109/ICIP.2019.8803477).
18. Y. Zhang, C. Liu, M. Sun, and Y. Ou, “Pan-Sharpening Using an Efficient Bidirectional Pyramid Network,” *IEEE Transactions on Geoscience and Remote Sensing*, vol. 57, no. 8, pp. 5549–5563, Aug. 2019, doi: [10.1109/TGRS.2019.2900419](https://doi.org/10.1109/TGRS.2019.2900419).
19. Y. Zheng, J. Li, and Y. Li, “Hyperspectral Pansharpening Based on Guided Filter and Deep Residual Learning,” in *IGARSS 2019 - 2019 IEEE International Geoscience and Remote Sensing Symposium*, Yokohama, Japan, Jul. 2019, pp. 616–619. doi: [10.1109/IGARSS.2019.8899015](https://doi.org/10.1109/IGARSS.2019.8899015).
20. J. Cai and B. Huang, “Super-Resolution-Guided Progressive Pansharpening Based on a Deep Convolutional Neural Network,” *IEEE Trans. Geosci. Remote Sensing*, pp. 1–15, 2020, doi: [10.1109/TGRS.2020.3015878](https://doi.org/10.1109/TGRS.2020.3015878).
21. J.-S. Choi, Y. Kim, and M. Kim, “S3: A Spectral-Spatial Structure Loss for Pan-Sharpening Networks,” *IEEE Geoscience and Remote Sensing Letters*, vol. 17, no. 5, pp. 829–833, May 2020, doi: [10.1109/LGRS.2019.2934493](https://doi.org/10.1109/LGRS.2019.2934493).
22. L.-J. Deng, G. Vivone, C. Jin, and J. Chanussot, “Detail Injection-Based Deep Convolutional Neural Networks for Pansharpening,” *IEEE Trans. Geosci. Remote Sensing*, pp. 1–16, 2020, doi: [10.1109/TGRS.2020.3031366](https://doi.org/10.1109/TGRS.2020.3031366).
23. S. Fu, W. Meng, G. Jeon, A. Chehri, R. Zhang, and X. Yang, “Two-Path Network with Feedback Connections for Pan-Sharpening in Remote Sensing,” *Remote Sensing*, vol. 12, no. 10, p. 1674, May 2020, doi: [10.3390/rs12101674](https://doi.org/10.3390/rs12101674).
24. A. Gastineau, J.-F. Aujol, Y. Berthoumieu, and C. Germain, “A Residual Dense Generative Adversarial Network For Pansharpening With Geometrical Constraints,” in *2020 IEEE International Conference on Image Processing (ICIP)*, Abu Dhabi, United Arab Emirates, Oct. 2020, pp. 493–497. doi: [10.1109/ICIP40778.2020.9191230](https://doi.org/10.1109/ICIP40778.2020.9191230).
25. P. Guo, P. Zhuang, and Y. Guo, “Bayesian Pan-Sharpening With Multiorder Gradient-Based Deep Network Constraints,” *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, vol. 13, pp. 950–962, 2020, doi: [10.1109/JSTARS.2020.2975000](https://doi.org/10.1109/JSTARS.2020.2975000).
26. J. Hu, P. Hu, X. Kang, H. Zhang, and S. Fan, “Pan-Sharpening via Multiscale Dynamic Convolutional Neural Network,” *IEEE Transactions on Geoscience and Remote Sensing*, pp. 1–14, 2020, doi: [10.1109/TGRS.2020.3007884](https://doi.org/10.1109/TGRS.2020.3007884).
27. C. Liu *et al.*, “Band-Independent Encoder–Decoder Network for Pan-Sharpening of Remote Sensing Images,” *IEEE Transactions on Geoscience and Remote Sensing*, vol. 58, no. 7, pp. 5208–5223, Jul. 2020, doi: [10.1109/TGRS.2020.2975230](https://doi.org/10.1109/TGRS.2020.2975230).
28. J. Liu, Y. Feng, C. Zhou, and C. Zhang, “PWNet: An Adaptive Weight Network for the Fusion of Panchromatic and Multispectral Images,” *Remote Sensing*, vol. 12, no. 17, p. 2804, Aug. 2020, doi: [10.3390/rs12172804](https://doi.org/10.3390/rs12172804).
29. L. Liu *et al.*, “Shallow–Deep Convolutional Network and Spectral-Discrimination-Based Detail Injection for Multispectral Imagery Pan-Sharpening,” *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, vol. 13, pp. 1772–1783, 2020, doi: [10.1109/JSTARS.2020.2981695](https://doi.org/10.1109/JSTARS.2020.2981695).
30. X. Liu, Q. Liu, and Y. Wang, “Remote sensing image fusion based on two-stream fusion network,” *Information Fusion*, vol. 55, pp. 1–15, Mar. 2020, doi: [10.1016/j.inffus.2019.07.010](https://doi.org/10.1016/j.inffus.2019.07.010).
31. F. Ozcelik, U. Alganci, E. Sertel, and G. Unal, “Rethinking CNN-Based Pansharpening: Guided Colorization of Panchromatic Images via GANs,” *IEEE Trans. Geosci. Remote Sensing*, pp. 1–16, 2020, doi: [10.1109/TGRS.2020.3010441](https://doi.org/10.1109/TGRS.2020.3010441).
32. Z. Shao, Z. Lu, M. Ran, L. Fang, J. Zhou, and Y. Zhang, “Residual Encoder–Decoder Conditional Generative Adversarial Network for Pansharpening,” *IEEE Geosci. Remote Sensing Lett.*, vol. 17, no. 9, pp. 1573–1577, Sep. 2020, doi: [10.1109/LGRS.2019.2949745](https://doi.org/10.1109/LGRS.2019.2949745).
37. S. Vitale and G. Scarpa, “A Detail-Preserving Cross-Scale Learning Strategy for CNN-Based Pansharpening,” *Remote Sensing*, vol. 12, no. 3, p. 348, Jan. 2020, doi: [10.3390/rs12030348](https://doi.org/10.3390/rs12030348).
38. W. Wei and Y. Zhang, “Deep Recursive Network for Hyperspectral Image Super-Resolution,” *IEEE TRANSACTIONS ON COMPUTATIONAL IMAGING*, vol. 6, p. 12, 2020.
39. Y. Yang, W. Tu, S. Huang, and H. Lu, “PCDRN: Progressive Cascade Deep Residual Network for Pansharpening,” *Remote Sensing*, vol. 12, no. 4, p. 676, Feb. 2020, doi: [10.3390/rs12040676](https://doi.org/10.3390/rs12040676).
40. Y. Zheng, J. Li, Y. Li, K. Cao, and K. Wang, “Deep Residual Learning for Boosting the Accuracy of Hyperspectral Pansharpening,” *IEEE Geosci. Remote Sensing Lett.*, vol. 17, no. 8, pp. 1435–1439, Aug. 2020, doi: [10.1109/LGRS.2019.2945424](https://doi.org/10.1109/LGRS.2019.2945424).
41. Y. Zheng, J. Li, Y. Li, J. Guo, X. Wu, and J. Chanussot, “Hyperspectral Pansharpening Using Deep Prior and Dual Attention Residual Network,” *IEEE Trans. Geosci. Remote Sensing*, vol. 58, no. 11, pp. 8059–8076, Nov. 2020, doi: [10.1109/TGRS.2020.2986313](https://doi.org/10.1109/TGRS.2020.2986313).
42. 
43. D. Lei, H. Chen, L. Zhang, and W. Li, “NLRNet: An Efficient Nonlocal Attention ResNet for Pansharpening,” *IEEE Transactions on Geoscience and Remote Sensing*, pp. 1–13, 2021, doi: [10.1109/TGRS.2021.3067097](https://doi.org/10.1109/TGRS.2021.3067097).
44. S. Xu, J. Zhang, Z. Zhao, K. Sun, J. Liu, and C. Zhang, “Deep Gradient Projection Networks for Pan-sharpening,” *CVPR2021*, Mar. 2021,



### 6.2 Unsupervised Methods

1. S. Luo, S. Zhou, Y. Feng, and J. Xie, “Pansharpening via Unsupervised Convolutional Neural Networks,” *IEEE JOURNAL OF SELECTED TOPICS IN APPLIED EARTH OBSERVATIONS AND REMOTE SENSING*, vol. 13, p. 16, 2020.
2. J. Ma, W. Yu, C. Chen, P. Liang, X. Guo, and J. Jiang, “Pan-GAN: An unsupervised pan-sharpening method for remote sensing image fusion,” *Information Fusion*, vol. 62, pp. 110–120, Oct. 2020, doi: [10.1016/j.inffus.2020.04.006](https://doi.org/10.1016/j.inffus.2020.04.006).
3. Y. Qu, R. K. Baghbaderani, H. Qi, and C. Kwan, “Unsupervised Pansharpening Based on Self-Attention Mechanism,” *IEEE Trans. Geosci. Remote Sensing*, pp. 1–17, 2020, doi: [10.1109/TGRS.2020.3009207](https://doi.org/10.1109/TGRS.2020.3009207).
4. T. Uezato, D. Hong, N. Yokoya, and W. He, “Guided Deep Decoder: Unsupervised Image Pair Fusion,” in *Computer Vision – ECCV 2020*, vol. 12351, A. Vedaldi, H. Bischof, T. Brox, and J.-M. Frahm, Eds. Cham: Springer International Publishing, 2020, pp. 87–102. doi: [10.1007/978-3-030-58539-6_6](https://doi.org/10.1007/978-3-030-58539-6_6).
5. C. Zhou, J. Zhang, J. Liu, C. Zhang, R. Fei, and S. Xu, “PercepPan: Towards Unsupervised Pan-Sharpening Based on Perceptual Loss,” p. 22, 2020.



## 7. Challenges In Pansharpening

 

