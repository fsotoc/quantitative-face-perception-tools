# Open-Source Tools for Quantitative Face Perception Research

This page is a living list of open-source software and publicly accessible resources for quantitative face-perception research. It was developed as a list of resources to accompany *Quantifying Face Perception: From Morphology to Predictive Models*, by Fabian A. Soto and Emily R. Martin, and is intended to remain useful as software, models, and research resources continue to evolve.

**Contributions are welcome.** If you know of a relevant tool or resource that should be added, or if an entry is outdated or incorrect, please open an issue or submit a pull request. See [CONTRIBUTING.md](CONTRIBUTING.md) for the inclusion criteria and requested information.

## Contents

- [Anatomical Standards](#anatomical-standards)
- [3DMMs](#3dmms)
- [Heuristic Models](#heuristic-models)
- [Physics-Based Models](#physics-based-models)
- [3D Face Reconstruction](#3d-face-reconstruction)
- [High-Quality Face Reconstruction](#high-quality-face-reconstruction)
- [3D Anthropometric Measurement](#3d-anthropometric-measurement)
- [Automatic FACS Labeling](#automatic-facs-labeling)
- [Face Motion Capture in 3D](#face-motion-capture-in-3d)
- [Skin Measurements from Images](#skin-measurements-from-images)
- [Face Databases](#face-databases)
- [Transformation Between Face Models](#transformation-between-face-models)
- [Model Fit and Selection](#model-fit-and-selection)
- [Model Interpretation](#model-interpretation)
- [References](#references)

## Anatomical Standards

| Type | Name | Reference | Link |
|---|---|---|---|
| Face Morphology | Elements of morphology standards | Allanson et al., 2009 | [Website](https://elementsofmorphology.nih.gov) |
| Face Anthropometrics | 3DFN reference | Weinberg et al., 2016 | [Website](https://www.facebase.org/resources/human/facial_norms/notes/#landmarking_surfaces) |
| Face Surface Areas | Delphi standard | Beltrami et al., 2023 | [Website](https://anatomymapper.com/Maps/Delphi) |
| Face Action Units | FACS visual reference | Ekman et al., 1978 | [Website](https://imotions.com/blog/learning/research-fundamentals/facial-action-coding-system/) |
| ARKit | ARKit to FACS correspondence guide | Oufqir et al., 2020 | [Website](https://melindaozel.com/arkit-to-facs-cheat-sheet/) |

## 3DMMs

| Type | Name | Reference | Link |
|---|---|---|---|
| Shape and texture | BFM | Paysan et al., 2009 | [Website](https://faces.dmi.unibas.ch/bfm/) |
| Shape and expression | FLAME | Li et al., 2017 | [Website](https://flame.is.tue.mpg.de) |
| Shape and expression | ICT FaceKit | Li et al., 2020 | [GitHub](https://github.com/ICT-VGL/ICT-FaceKit) |
| Shape and expression (high detail INR) | ImFace++ | Zheng et al., 2024 | [GitHub](https://github.com/MingwuZheng/ImFace) |
| Shape and expression (high detail INR) | NPHM | Giebenhain et al., 2023 | [GitHub](https://github.com/SimonGiebenhain/NPHM#learning-neural-parametric-head-models-nphm) |
| — | LSFM | Booth et al., 2018 | [GitHub](https://github.com/menpo/lsfm) |
| Shape and expression (part-based) | LAMM | Tarasiou et al., 2024 | [GitHub](https://github.com/michaeltrs/LAMM) |
| Shape, expression, and displacement | FaceScape | Yang et al., 2020 | [GitHub](https://github.com/yanght321/Detailed3DFace) |
| Shape, expression, and (editable) displacement | SEMM | Ling et al., 2022 | [GitHub](https://github.com/gerwang/facial-detail-manipulation) |
| Shape (FLAME), displacement, and diffuse | AlbedoGAN | Rai et al., 2024 | [GitHub](https://github.com/aashishrai3799/Towards-Realistic-Generative-3D-Face-Models) |
| Diffuse | AlbedoMM | Smith et al., 2020 | [GitHub](https://github.com/waps101/AlbedoMM) |
| Diffuse and specular | ReflectanceMM | Han et al., 2023 | [GitHub](https://github.com/yxuhan/ReflectanceMM) |

## Heuristic Models

| Type | Name | Reference | Link |
|---|---|---|---|
| Anatomy-inspired shape and expression (blendshapes). | MakeHuman | Bastioni et al., 2008 | [Website](http://makehumancommunity.org) |
| MakeHuman plus skin procedural model | MPFB (MakeHuman Plugin for Blender) | Makehuman community, 2024 | [Website](https://static.makehumancommunity.org/mpfb.html) |
| MakeHuman | AVATAR | Sanchez-Riera et al., 2021 | [GitHub](https://github.com/jsan3386/avatar) |
| Shape and expression manipulation in MakeHuman | FaReT | Hays et al., 2020 | [GitHub](https://github.com/fsotoc/FaReT) |
| Expression (FACS blendshapes) | FACSHuman | Gilbert et al., 2021 | [GitHub](https://github.com/montybot/FACSHuman) |
| Expression (ARKit blendshapes) in Blender | ARKit Blendshape Helper | Oufqir et al., 2020 | [GitHub](https://github.com/elijah-atkins/ARKitBlendshapeHelper) |

## Physics-Based Models

| Type | Name | Reference | Link |
|---|---|---|---|
| Physics-based face models | *No open-source releases currently listed* | — | — |

## 3D Face Reconstruction

| Type | Name | Reference | Link |
|---|---|---|---|
| Shape (FLAME) from one image | MICA | Zielonka et al., 2022 | [GitHub](https://github.com/Zielon/MICA) |
| Shape (BFM) , diffuse, specular, and roughness from one or multiple images | NextFace | Dib et al., 2021 | [GitHub](https://github.com/abdallahdib/NextFace) |
| Shape, displacement from one image | FaceScape | Yang et al., 2020 | [GitHub](https://github.com/yanght321/Detailed3DFace) |
| Shape, displacement from multiple images | MVFR | Xiao et al., 2022 | [GitHub](https://github.com/zhuhao-nju/mvfr) |
| Diffuse map | TRUST | Feng et al., 2022 | [GitHub](https://github.com/HavenFeng/TRUST) |
| Diffuse, specular, roughness, and normal maps | id2reflectance | Ren et al., 2024 | [Website](https://xingyuren.github.io/id2reflectance) |

## High-Quality Face Reconstruction

| Type | Name | Reference | Link |
|---|---|---|---|
| Shape, diffuse, specular, normal | NeuFace | Zheng et al., 2023 | [GitHub](https://github.com/aejion/NeuFace) |
| Shape, diffuse, specular, displacement | SunStage | Wang et al., 2023 | [GitHub](https://github.com/adobe-research/sunstage) |
| Shape, diffuse, specular, normal | CoRA | Han et al., 2024 | [GitHub](https://github.com/yxuhan/CoRA) |

## 3D Anthropometric Measurement

| Type | Name | Reference | Link |
|---|---|---|---|
| Landmarks | 3D Facial Landmark Detection | Topsakal et al., 2023 | [GitHub](https://github.com/research-digitized-rhinoplasty/3D-Facial-Landmark-Detection) |
| Landmarks, measurements, norms | CliniFace | Palmer et al., 2020 | [Website](https://cliniface.org) · [GitHub](https://github.com/frontiersi/Cliniface/releases) |
| Landmarks, measurements | Digitized Rhinoplasty | Topsakal et al., 2020 | [Website](https://digitized-rhinoplasty.com) |
| Norms | 3DFN Database | Weinberg et al., 2016 | [Website](https://www.facebase.org/resources/human/facial_norms/) |

## Automatic FACS Labeling

| Type | Name | Reference | Link |
|---|---|---|---|
| — | OpenFace | Baltrusaitis et al., 2016 | [Website](https://cmusatyalab.github.io/openface/) |
| — | Py-Feat | Cheong et al., 2023 | [Website](https://py-feat.org) |
| — | LibreFace | Chang et al., 2024 | [GitHub](https://github.com/ihp-lab/LibreFace) |
| — | Behaviour4all | Kollias et al., 2024 | Unreleased |
| — | OpenGraphAU | Luo et al., 2022 | [GitHub](https://github.com/lingjivoo/OpenGraphAU) |
| — | AU-Net | Yang et al., 2023 | [GitHub](https://github.com/jingyang2017/AU-Net) |
| — | AUNCE | Shang et al., 2025 | [GitHub](https://github.com/Ziqiao-Shang/AUNCE) |
| — | MDHR | Wang et al., 2024 | [GitHub](https://github.com/CVI-SZU/MDHR) |

## Face Motion Capture in 3D

| Type | Name | Reference | Link |
|---|---|---|---|
| ARKit blendshapes | ARKit | Oufqir et al., 2020 | [Website](https://developer.apple.com/documentation/arkit/arkit_in_ios/content_anchors/tracking_and_visualizing_faces) |
| MetaHuman expression parameters | MetaHuman | Franc et al., 2022 | [Website](https://dev.epicgames.com/community/learning/tutorials/lEYe/unreal-engine-facial-capture-with-live-link) |

## Skin Measurements from Images

| Type | Name | Reference | Link |
|---|---|---|---|
| Melanin, hemoglobin | BioFaceNet | Alotaibi and Smith, 2019 | [GitHub](https://github.com/bznick98/BioFaceNet) |
| Melanin, hemoglobin, blood oxygenation, eu/pheomelanin ratio, epidermis thickness | BioSkin | Aliaga et al., 2023 | [GitHub](https://github.com/facebookresearch/BioSkin) |

## Face Databases

| Type | Name | Reference | Link |
|---|---|---|---|
| 3D Shape | FaceScape | Yang et al., 2020 | [GitHub](https://github.com/zhuhao-nju/facescape) |
| 3D Shape, Expression | FaceWarehouse | Cao et al., 2014 | — |
| 3D Shape, Expression | 3DRFE | Stratou et al., 2011 | [Website](https://vgl.ict.usc.edu/Data/3DRFE/) |
| 3D Shape, Texture | Stirling/ESRC | Stirling PICS, n.d. | [Website](https://pics.stir.ac.uk/ESRC/) |
| 3D Shape, Texture | Headspace | Dai et al., 2020 | [Website](https://www-users.york.ac.uk/~np7/research/Headspace/) |
| 3D Shape | FRGC | Phillips et al., 2005 | [Website](https://cvrl.nd.edu/projects/data/#face-recognition-grand-challenge-frgc-v20-data-collection) |
| 3D Shape, Texture | Florence | Bagdanov et al., 2011 | [Website](https://www.micc.unifi.it/resources/datasets/florence-3d-faces/) |
| High-definition texture | FFHQ-UV | Bai et al., 2023 | [GitHub](https://github.com/csbhr/FFHQ-UV) |
| Diffuse, specular, normal, and other maps. | FFHQ-UV-Instrinsics | Dib et al., 2024 | [GitHub](https://github.com/ubisoft/ubisoft-laforge-FFHQ-UV-Intrinsics) |
| Anthropometric Measurements | 3D Facial Norms | Weinberg et al., 2016 | [Website](https://www.facebase.org/resources/human/facial_norms/) |

## Transformation Between Face Models

| Type | Name | Reference | Link |
|---|---|---|---|
| Registration to target mesh topology | 3D face dense registration | Fan et al., 2023 | [GitHub](https://github.com/NaughtyZZ/3D_face_dense_registration) |
| Mesh to FLAME | flame-fitting | Li et al., 2017 | [GitHub](https://github.com/Rubikplayer/flame-fitting) |
| Blendshapes to linear blend skinning | Dem Bones | Le and Deng, 2012 | [GitHub](https://github.com/electronicarts/dem-bones) |
| Blendshapes to linear blend skinning | Compskin | Kavan et al., 2024 | [GitHub](https://github.com/facebookresearch/compskin) |
| ARKit to FLAME expression | Part of EMAGE | Liu et al., 2024 | [GitHub](https://github.com/PantoMatrix/PantoMatrix) |
| Personalized blendshapes (ARKit) | Deformation transfer | Sumner & Popović, 2004 | [GitHub](https://github.com/vasiliskatr/deformation_transfer_ARkit_blendshapes) |
| Personalized blendshapes (ARKit) | Example based facial rigging | Li et al., 2010 | [GitHub](https://github.com/vasiliskatr/example_based_facial_rigging_ARkit_blendshapes?tab=readme-ov-file) |

## Model Fit and Selection

| Type | Name | Reference | Link |
|---|---|---|---|
| Probabilistic programming in R, python, and more | Stan | Carpenter et al., 2017 | [Website](https://mc-stan.org) |
| Probabilistic programming in python | pyro | Bingham et al., 2018 | [Website](https://pyro.ai) |
| Probabilistic programming in python | PyMC | Abril-Pla et al., 2023 | [Website](https://www.pymc.io) |
| MLE in R | maxLik | Henningsen and Toomet, 2011 | [CRAN](https://cran.r-project.org/web/packages/maxLik/index.html) |
| Bayesian model selection in python (Stan, pyro, and PyMC models) | ArviZ | Kumar et al., 2019 | [Website](https://python.arviz.org) |
| Bayesian model selection in R (Stan models) | loo | Vehtari et al., 2017 | [GitHub](https://github.com/stan-dev/loo) |
| Amortized inference | sbi | Tejero-Cantero et al., 2020 | [Website](https://sbi-dev.github.io/sbi) |
| Amortized inference | bayesflow | Radev et al., 2022 | [Website](https://bayesflow.org/index.html) |

## Model Interpretation

| Type | Name | Reference | Link |
|---|---|---|---|
| PLS analyses of face surfaces | python_shape_stats | Matthews et al., 2022 | [GitHub](https://github.com/harrymatthews50/python_shape_stats) |
| ML model interpretation | Alibi Explain | Klaise et al., 2021 | [GitHub](https://github.com/SeldonIO/alibi) |
| — | DIANNA | Ranguelova et al., 2022 | [GitHub](https://github.com/dianna-ai/dianna) |
| — | interpretML | Nori et al., 2019 | [GitHub](https://github.com/interpretml/interpret) |
| — | PiML | Sudjianto et al., 2023 | [GitHub](https://github.com/SelfExplainML/PiML-Toolbox) |
| — | scikit-explain | Flora et al., 2024 | [GitHub](https://github.com/monte-flora/scikit-explain) |

## References

Abril-Pla, O., Andreani, V., Carroll, C., Dong, L., Fonnesbeck, C. J., Kochurov, M., Kumar, R., Lao, J., Luhmann, C. C., Martin, O. A., Osthege, M., Vieira, R., Wiecki, T., & Zinkov, R. (2023). PyMC: A modern and comprehensive probabilistic programming framework in Python. *PeerJ Computer Science, 9*, e1516. [DOI](https://doi.org/10.7717/peerj-cs.1516)

Aliaga, C., Xia, M., Xie, X., Jarabo, A., Braun, G., & Hery, C.. (2023). A hyperspectral space of skin tones for inverse rendering of biophysical skin properties. *Computer Graphics Forum*, 42(4), e14887. [DOI](https://doi.org/10.1111/cgf.14887)

Allanson, J. E., Cunniff, C., Hoyme, H. E., McGaughran, J., Muenke, M., & Neri, G. (2009). Elements of morphology: Standard terminology for the head and face. *American Journal of Medical Genetics Part A, 149A*(1), 6–28. [DOI](https://doi.org/10.1002/ajmg.a.32612)

Alotaibi, S., & Smith, W. A. P.. (2019). BioFaceNet: Deep biophysical face image interpretation. *The British Machine Vision Conference (BMVC)*, 68. [Link](https://openreview.net/forum?id=Xf8LxTRlfg)

Bagdanov, A. D., Del Bimbo, A., & Masi, I. (2011). The Florence 2D/3D Hybrid Face Dataset. In *Proceedings of the 2011 Joint ACM Workshop on Human Gesture and Behavior Understanding* (pp. 79–80). [DOI](https://doi.org/10.1145/2072572.2072597)

Bai, H., Kang, D., Zhang, H., Pan, J., & Bao, L.. (2023). FFHQ-UV: Normalized facial UV-texture dataset for 3D face reconstruction. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 362--371. [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Bai_FFHQ-UV_Normalized_Facial_UV-Texture_Dataset_for_3D_Face_Reconstruction_CVPR_2023_paper.html)

Baltrusaitis, T., Robinson, P., & Morency, L. P.. (2016). OpenFace: An open source facial behavior analysis toolkit. *2016 IEEE Winter Conference on Applications of Computer Vision (WACV)*, 1--10. [DOI](https://doi.org/10.1109/WACV.2016.7477553)

Bastioni, M., Re, S., & Misra, S.. (2008). Ideas and methods for modeling 3D human figures: the principal algorithms used by MakeHuman and their implementation in a new approach to parametric modeling. *Proceedings of the 1st Bangalore Annual Compute Conference*, 10:1--10:6.

Beltrami, E. J., Gronbeck, C., Jain, N., Hargis, G., Feng, H., Grant-Kels, J. M., & Sloan, B.. (2024). Surface anatomy in dermatology: Part I—Clinical importance, diagnostic utility, and impact on medical management. *Journal of the American Academy of Dermatology*, 91(2), 207--220. [DOI](https://doi.org/10.1016/j.jaad.2023.07.001)

Bingham, E., Chen, J. P., Jankowiak, M., Obermeyer, F., Pradhan, N., Karaletsos, T., Singh, R., Szerlip, P., Horsfall, P., & Goodman, N. D. (2018). Pyro: Deep universal probabilistic programming. *arXiv*. [Link](https://arxiv.org/abs/1810.09538)

Booth, J., Roussos, A., Ponniah, A., Dunaway, D., & Zafeiriou, S.. (2018). Large scale 3D morphable models. *International Journal of Computer Vision*, 126(2), 233--254. [DOI](https://doi.org/10.1007/s11263-017-1009-7)

Cao, C., Weng, Y., Zhou, S., Tong, Y., & Zhou, K.. (2014). FaceWarehouse: A 3D facial expression database for visual computing. *IEEE Transactions on Visualization and Computer Graphics*, 20(3), 413--425. [DOI](https://doi.org/10.1109/TVCG.2013.249)

Carpenter, B., Gelman, A., Hoffman, M. D., Lee, D., Goodrich, B., Betancourt, M., Brubaker, M., Guo, J., Li, P., & Riddell, A.. (2017). Stan: A probabilistic programming language. *Journal of Statistical Software*, 76, 1--32. [DOI](https://doi.org/10.18637/jss.v076.i01)

Chang, D., Yin, Y., Li, Z., Tran, M., & Soleymani, M.. (2024). LibreFace: An open-source toolkit for deep facial expression analysis. *Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)*, 8205--8215. [Link](https://openaccess.thecvf.com/content/WACV2024/html/Chang_LibreFace_An_Open-Source_Toolkit_for_Deep_Facial_Expression_Analysis_WACV_2024_paper.html)

Cheong, J. H., Jolly, E., Xie, T., Byrne, S., Kenney, M., & Chang, L. J.. (2023). Py-Feat: Python facial expression analysis toolbox. *Affective Science*, 4(4), 781--796. [DOI](https://doi.org/10.1007/s42761-023-00191-4)

Dai, H., Pears, N., Smith, W., & Duncan, C. (2020). Statistical modeling of craniofacial shape and texture. *International Journal of Computer Vision, 128*, 547–571. [DOI](https://doi.org/10.1007/s11263-019-01260-7)

Dib, A., Bharaj, G., Ahn, J., Thébault, C., Gosselin, P.-H., Romeo, M., & Chevallier, L. (2021). Practical face reconstruction via differentiable ray tracing. *Computer Graphics Forum, 40*(2), 153–164. [DOI](https://doi.org/10.1111/cgf.142622)

Dib, A., Hafemann, L. G., Got, E., Anderson, T., Fadaeinejad, A., Cruz, R. M. O., & Carbonneau, M. A.. (2024). MoSAR: Monocular semi-supervised model for avatar reconstruction using differentiable shading. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 1770--1780. [Link](https://openaccess.thecvf.com/content/CVPR2024/html/Dib_MoSAR_Monocular_Semi-Supervised_Model_for_Avatar_Reconstruction_using_Differentiable_Shading_CVPR_2024_paper.html)

Ekman, P., Friesen, W. V., & Hager, J. (1978). *Manual for the Facial Action Coding System*. Consulting Psychologists Press.

Fan, Z., Peng, S., & Xia, S.. (2023). Towards fine-grained optimal 3D face dense registration: An iterative dividing and diffusing method. *International Journal of Computer Vision*, 131(9), 2356--2376. [DOI](https://doi.org/10.1007/s11263-023-01825-7)

Feng, H., Bolkart, T., Tesch, J., Black, M. J., & Abrevaya, Victoria. (2022). Towards racially unbiased skin tone estimation via scene disambiguation. *Computer Vision – ECCV 2022*, 72--90. [DOI](https://doi.org/10.1007/978-3-031-19778-9_5)

Flora, M. L., Potvin, C. K., McGovern, A., & Handler, S.. (2024). A machine learning explainability tutorial for atmospheric sciences. *Artificial Intelligence for the Earth Systems*, 3(1), e230018. [DOI](https://doi.org/10.1175/AIES-D-23-0018.1)

Franc, A., Kovac, P., Bousquet, M., & Kwak, J. (2022). *Rig Logic—Runtime evaluation of MetaHuman face rigs*. Epic Games. [Link](https://cdn2.unrealengine.com/rig-logic-whitepaper-v2-5c9f23f7e210.pdf)

Giebenhain, S., Kirschstein, T., Georgopoulos, M., Rünz, M., Agapito, L., & Nießner, M.. (2023). Learning neural parametric head models. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, 21003--21012. [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Giebenhain_Learning_Neural_Parametric_Head_Models_CVPR_2023_paper.html)

Gilbert, M., Demarchi, S., & Urdapilleta, I.. (2021). FACSHuman, a software program for creating experimental material by modeling 3D facial expressions. *Behavior Research Methods*, 53(5), 2252--2272. [DOI](https://doi.org/10.3758/s13428-021-01559-9)

Han, Y., Lyu, J., & Xu, F.. (2024). High-quality facial geometry and appearance capture at home. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 697--707. [Link](https://openaccess.thecvf.com/content/CVPR2024/html/Han_High-Quality_Facial_Geometry_and_Appearance_Capture_at_Home_CVPR_2024_paper.html)

Han, Y., Wang, Z., & Xu, F.. (2023). Learning a 3D morphable face reflectance model from low-cost data. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 8598--8608. [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Han_Learning_a_3D_Morphable_Face_Reflectance_Model_From_Low-Cost_Data_CVPR_2023_paper.html)

Hays, J. S., Wong, C., & Soto, F. A.. (2020). FaReT: A free and open-source toolkit of three-dimensional models and software to study face perception. *Behavior Research Methods*, 52(6), 2604--2622.

Henningsen, A., & Toomet, O.. (2011). maxLik: A package for maximum likelihood estimation in R. *Computational Statistics*, 26(3), 443--458. [DOI](https://doi.org/10.1007/s00180-010-0217-1)

Kavan, L., Doublestein, J., Prazak, M., Cioffi, M., & Roble, D.. (2024). Compressed skinning for facial blendshapes. *ACM SIGGRAPH 2024 Conference Papers*, 1--9. [DOI](https://doi.org/10.1145/3641519.3657477)

Klaise, J., Looveren, A. V., Vacanti, G., & Coca, A.. (2021). Alibi Explain: Algorithms for explaining machine learning models. *Journal of Machine Learning Research*, 22(181), 1--7. [Link](http://jmlr.org/papers/v22/21-0017.html)

Kollias, D., Shao, C., Kaloidas, O., & Patras, I.. (2024). Behaviour4All: in-the-wild facial behaviour analysis toolkit. arXiv. [DOI](https://doi.org/10.48550/arXiv.2409.17717)

Kumar, R., Carroll, C., Hartikainen, A., & Martin, O. (2019). ArviZ: A unified library for exploratory analysis of Bayesian models in Python. *Journal of Open Source Software, 4*(33), 1143. [DOI](https://doi.org/10.21105/joss.01143)

Le, B. H., & Deng, Z.. (2012). Smooth skinning decomposition with rigid bones. *ACM Transactions on Graphics*, 31(6), 199. [DOI](https://doi.org/10.1145/2366145.2366218)

Li, H., Weise, T., & Pauly, M.. (2010). Example-based facial rigging. *ACM Transactions on Graphics*, 29(4), 32:1--32:6. [DOI](https://doi.org/10.1145/1778765.1778769)

Ling, J., Wang, Z., Lu, M., Wang, Q., Qian, C., & Xu, F.. (2022). Structure-aware editable morphable model for 3D facial detail animation and manipulation. *Computer Vision – ECCV 2022*, 249--267. [DOI](https://doi.org/10.1007/978-3-031-20062-5_15)

Li, R., Bladin, K., Zhao, Y., Chinara, C., Ingraham, O., Xiang, P., Ren, X., Prasad, P., Kishore, B., Xing, J., & Li, H.. (2020). Learning formation of physically-based face attributes. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 3410--3419. [Link](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Learning_Formation_of_Physically-Based_Face_Attributes_CVPR_2020_paper.html)

Li, T., Bolkart, T., Black, M. J., Li, H., & Romero, J.. (2017). Learning a model of facial shape and expression from 4D scans. *ACM Transactions on Graphics*, 36(6), 194. [DOI](https://doi.org/10.1145/3130800.3130813)

Liu, H., Zhu, Z., Becherini, G., Peng, Y., Su, M., Zhou, Y., Zhe, X., Iwamoto, N., Zheng, B., & Black, M. J.. (2024). EMAGE: Towards unified holistic co-speech gesture generation via expressive masked audio gesture modeling. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 1144--1154. [Link](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_EMAGE_Towards_Unified_Holistic_Co-Speech_Gesture_Generation_via_Expressive_Masked_CVPR_2024_paper.html)

Luo, C., Song, S., Xie, W., Shen, L., & Gunes, H.. (2022). Learning multi-dimensional edge feature-based AU relation graph for facial action unit recognition. IJCAI. [DOI](https://doi.org/10.24963/ijcai.2022/173)

MakeHuman Community. (2024). *MPFB: MakeHuman Plugin for Blender*. [Link](https://static.makehumancommunity.org/mpfb.html)

Matthews, H., De Jong, G., Maal, T., & Claes, P.. (2022). Static and motion facial analysis for craniofacial assessment and diagnosing diseases. *Annual Review of Biomedical Data Science*, 5(Volume 5, 2022), 19--42. [DOI](https://doi.org/10.1146/annurev-biodatasci-122120-111413)

Nori, H., Jenkins, S., Koch, P., & Caruana, R. (2019). InterpretML: A unified framework for machine learning interpretability. *arXiv*. [Link](https://arxiv.org/abs/1909.09223)

Oufqir, Z., El Abderrahmani, A., & Satori, K.. (2020). ARKit and ARCore in serve to augmented reality. *2020 International Conference on Intelligent Systems and Computer Vision (ISCV)*, 1--7. [DOI](https://doi.org/10.1109/ISCV49265.2020.9204243)

Palmer, R. L., Helmholz, P., & Baynam, G.. (2020). Cliniface: Phenotypic visualization and analysis using non-rigid registration of 3D facial images. *The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences*, XLIII-B2-2020, 301--308. [DOI](https://doi.org/10.5194/isprs-archives-XLIII-B2-2020-301-2020)

Paysan, P., Knothe, R., Amberg, B., Romdhani, S., & Vetter, T.. (2009). A 3D face model for pose and illumination invariant face recognition. *Proceedings of the 2009 Sixth IEEE International Conference on Advanced Video and Signal Based Surveillance*, 296--301. [DOI](https://doi.org/10.1109/AVSS.2009.58)

Phillips, P.J., Flynn, P.J., Scruggs, T., Bowyer, K.W., Chang, J., Hoffman, K., Marques, J., Min, Jaesik, & Worek, W.. (2005). Overview of the face recognition grand challenge. *2005 IEEE Computer Society Conference on Computer Vision and Pattern Recognition (CVPR'05)*, 1, 947--954 vol. 1. [DOI](https://doi.org/10.1109/CVPR.2005.268)

Radev, S. T., Mertens, U. K., Voss, A., Ardizzone, L., & Köthe, U.. (2022). BayesFlow: Learning complex stochastic models with invertible neural networks. *IEEE Transactions on Neural Networks and Learning Systems*, 33(4), 1452--1466. [DOI](https://doi.org/10.1109/TNNLS.2020.3042395)

Rai, A., Gupta, H., Pandey, A., Carrasco, F. V., Takagi, S. J., Aubel, A., Kim, D., Prakash, A., & De la Torre, F.. (2024). Towards realistic generative 3D face models. *Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision*, 3738--3748. [Link](https://openaccess.thecvf.com/content/WACV2024/html/Rai_Towards_Realistic_Generative_3D_Face_Models_WACV_2024_paper.html)

Ranguelova, E., Meijer, C., Oostrum, L., Liu, Y., Bos, P., Crocioni, G., Laneuville, M., Guevara, B. C., Bakhshi, R., & Podareanu, D. (2022). DIANNA: Deep Insight And Neural Network Analysis. *Journal of Open Source Software, 7*(80), 4493. [DOI](https://doi.org/10.21105/joss.04493)

Ren, X., Deng, J., Cheng, Y., Guo, J., Ma, C., Yan, Y., Zhu, W., & Yang, X.. (2024). Monocular identity-conditioned facial reflectance reconstruction. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 885--895. [Link](https://openaccess.thecvf.com/content/CVPR2024/html/Ren_Monocular_Identity-Conditioned_Facial_Reflectance_Reconstruction_CVPR_2024_paper.html)

Sanchez-Riera, J., Civit, A., Altarriba, M., & Moreno-Noguer, F.. (2021). AVATAR: Blender add-on for fast creation of 3D human models. arXiv. [DOI](https://doi.org/10.48550/arXiv.2103.14507)

Shang, Z., Liu, B., Lv, F., Teng, F., Li, T., & Guo, L. Z.. (2025). Learning contrastive feature representations for facial action unit detection. arXiv. [DOI](https://doi.org/10.48550/arXiv.2402.06165)

Smith, W. A. P., Seck, A., Dee, H., Tiddeman, B., Tenenbaum, J. B., & Egger, B.. (2020). A morphable face albedo model. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 5011--5020. [Link](https://openaccess.thecvf.com/content_CVPR_2020/html/Smith_A_Morphable_Face_Albedo_Model_CVPR_2020_paper.html)

Stirling PICS. (n.d.). *Stirling ESRC 3D Face Database*. Psychological Image Collection at Stirling. [Link](https://pics.stir.ac.uk/ESRC/)

Stratou, G., Ghosh, A., Debevec, P., & Morency, L. P.. (2011). Effect of illumination on automatic expression recognition: A novel 3D relightable facial database. *2011 IEEE International Conference on Automatic Face \& Gesture Recognition (FG)*, 611--618. [DOI](https://doi.org/10.1109/FG.2011.5771467)

Sudjianto, A., Zhang, A., Yang, Z., Su, Y., & Zeng, N.. (2023). PiML toolbox for interpretable machine learning model development and diagnostics. arXiv. [DOI](https://doi.org/10.48550/arXiv.2305.04214)

Sumner, R. W., & Popović, J.. (2004). Deformation transfer for triangle meshes. *ACM Transactions on Graphics*, 23(3), 399--405. [DOI](https://doi.org/10.1145/1015706.1015736)

Tarasiou, M., Potamias, R. A., O'Sullivan, E., Ploumpis, S., & Zafeiriou, S.. (2024). Locally adaptive neural 3D morphable models. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 1867--1876. [Link](https://openaccess.thecvf.com/content/CVPR2024/html/Tarasiou_Locally_Adaptive_Neural_3D_Morphable_Models_CVPR_2024_paper.html)

Tejero-Cantero, A., Boelts, J., Deistler, M., Lueckmann, J. M., Durkan, C., Gonçalves, P. J., Greenberg, D. S., & Macke, J. H.. (2020). sbi: A toolkit for simulation-based inference. *Journal of Open Source Software*, 5(52), 2505. [DOI](https://doi.org/10.21105/joss.02505)

Topsakal, O., Akbaş, M. I., Demirel, D., Nunez, R., Smith, B. S., Perez, M. F., & Celikoyar, M. M.. (2020). Digitizing rhinoplasty: a web application with three-dimensional preoperative evaluation to assist rhinoplasty surgeons with surgical planning. *International Journal of Computer Assisted Radiology and Surgery*, 15(11), 1941--1950. [DOI](https://doi.org/10.1007/s11548-020-02251-7)

Topsakal, O., Akinci, T. C., Murphy, J., Preston, T. L. J., & Celikoyar, M. M.. (2023). Detecting facial landmarks on 3D models based on geometric properties—A review of algorithms, enhancements, additions and open-source implementations. *IEEE Access*, 11, 25593--25603. [DOI](https://doi.org/10.1109/ACCESS.2023.3255099)

Vehtari, A., Gelman, A., & Gabry, J. (2017). Practical Bayesian model evaluation using leave-one-out cross-validation and WAIC. *Statistics and Computing, 27*, 1413–1432. [DOI](https://doi.org/10.1007/s11222-016-9696-4)

Wang, Y., Holynski, A., Zhang, X., & Zhang, X.. (2023). SunStage: Portrait reconstruction and relighting using the sun as a light stage. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 20792--20802. [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_SunStage_Portrait_Reconstruction_and_Relighting_Using_the_Sun_as_a_CVPR_2023_paper.html)

Wang, Z., Song, S., Luo, C., Deng, S., Xie, W., & Shen, L. (2024). Multi-scale dynamic and hierarchical relationship modeling for facial action units recognition. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition* (pp. 1270–1280). [DOI](https://doi.org/10.1109/CVPR52733.2024.00127)

Weinberg, S. M., Raffensperger, Z. D., Kesterke, M. J., Heike, C. L., Cunningham, M. L., Hecht, J. T., Kau, C. H., Murray, J. C., Wehby, G. L., Moreno, L. M., & Marazita, M. L.. (2016). The 3d facial norms database: Part 1. A web-based craniofacial anthropometric and image repository for the clinical and research community. *The Cleft Palate Craniofacial Journal*, 53(6), 185--197. [DOI](https://doi.org/10.1597/15-199)

Xiao, Y., Zhu, H., Yang, H., Diao, Z., Lu, X., & Cao, X. (2022). Detailed facial geometry recovery from multi-view images by learning an implicit function. *Proceedings of the AAAI Conference on Artificial Intelligence, 36*(3), 2839–2847. [DOI](https://doi.org/10.1609/aaai.v36i3.20188)

Yang, H., Zhu, H., Wang, Y., Huang, M., Shen, Q., Yang, R., & Cao, X.. (2020). FaceScape: A large-scale high quality 3D face dataset and detailed riggable 3D face prediction. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 601--610. [Link](https://openaccess.thecvf.com/content_CVPR_2020/html/Yang_FaceScape_A_Large-Scale_High_Quality_3D_Face_Dataset_and_Detailed_CVPR_2020_paper.html)

Yang, J., Hristov, Y., Shen, J., Lin, Y., & Pantic, M.. (2023). Toward robust facial action units’ detection. *Proceedings of the IEEE*, 111(10), 1198--1214. [DOI](https://doi.org/10.1109/JPROC.2023.3257542)

Zheng, M., Zhang, H., Yang, H., Chen, L., & Huang, D.. (2025). ImFace++: A sophisticated nonlinear 3D morphable face model with implicit neural representations. *IEEE Transactions on Pattern Analysis and Machine Intelligence*, 47(2), 994--1012. [DOI](https://doi.org/10.1109/TPAMI.2024.3480151)

Zheng, M., Zhang, H., Yang, H., & Huang, D.. (2023). NeuFace: Realistic 3D neural face rendering from multi-view images. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 16868--16877. [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_NeuFace_Realistic_3D_Neural_Face_Rendering_From_Multi-View_Images_CVPR_2023_paper.html)

Zielonka, W., Bolkart, T., & Thies, J. (2022). Towards metrical reconstruction of human faces. In *Computer Vision—ECCV 2022*. [Link](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730249.pdf)
