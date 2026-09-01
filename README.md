# Open-Source Tools for Quantitative Face Perception

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

## Anatomical Standards

| Type | Name | Reference | Link |
|---|---|---|---|
| Face Morphology | Elements of morphology standards | Allanson et al., 2009 | [Website](https://elementsofmorphology.nih.gov) |
| Face Anthropometrics | 3DFN reference | Weinberg et al., 2016 | [Website](https://www.facebase.org/resources/human/facial_norms/notes/#landmarking_surfaces) |
| Face Surface Areas | Delphi standard | Beltrami et al., 2023 | [Website](https://anatomymapper.com/Maps/Delphi) |
| Face Action Units | FACS visual reference | Ekman & Friesen, 1975 | [Website](https://imotions.com/blog/learning/research-fundamentals/facial-action-coding-system/) |
| ARKit | ARKit to FACS correspondence guide | Oufqir et al., 2020 | [Website](https://melindaozel.com/arkit-to-facs-cheat-sheet/) |

## 3DMMs

| Type | Name | Reference | Link |
|---|---|---|---|
| Shape and texture | BFM | Paysan et al., 2009 | [Website](https://faces.dmi.unibas.ch/bfm/) |
| Shape and expression | FLAME | Li et al., 2017 | [Website](https://flame.is.tue.mpg.de) |
| Shape and expression | ICT FaceKit | Li et al., 2020 | [GitHub](https://github.com/ICT-VGL/ICT-FaceKit) |
| Shape and expression (high detail INR) | ImFace++ | Zheng et al., 2024 | [GitHub](https://github.com/MingwuZheng/ImFace) |
| Shape and expression (high detail INR) | NPHM | Giebenhain et al., 2024 | [GitHub](https://github.com/SimonGiebenhain/NPHM#learning-neural-parametric-head-models-nphm) |
| — | LSFM | Booth et al., 2017 | [GitHub](https://github.com/menpo/lsfm) |
| Shape and expression (part-based) | LAMM | Tarasiou et al. 2024 | [GitHub](https://github.com/michaeltrs/LAMM) |
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
| Shape and expression manipulation in MakeHuman | FaReT | Hays et al. 2020 | [GitHub](https://github.com/fsotoc/FaReT) |
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
| ARKit blendshapes | ARKit | Apple | [Website](https://developer.apple.com/documentation/arkit/arkit_in_ios/content_anchors/tracking_and_visualizing_faces) |
| MetaHuman expression parameters | MetaHuman | Unreal Engine | [Website](https://dev.epicgames.com/community/learning/tutorials/lEYe/unreal-engine-facial-capture-with-live-link) |

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
| 3D Shape, Texture | Stirling/ESRC | Feng et al., 2018 | [Website](https://pics.stir.ac.uk/ESRC/) |
| 3D Shape, Texture | Headspace | Dai et al., 2020 | [Website](https://www-users.york.ac.uk/~np7/research/Headspace/) |
| 3D Shape | FRGC | Phillips et al., 2005 | [Website](https://cvrl.nd.edu/projects/data/#face-recognition-grand-challenge-frgc-v20-data-collection) |
| 3D Shape, Texture | Florence | Bagdanov et al., 2011 | [Website](https://www.micc.unifi.it/resources/datasets/florence-3d-faces/) |
| High-definition texture | FFHQ-UV | Bai et al., 2023 | [GitHub](https://github.com/csbhr/FFHQ-UV) |
| Diffuse, specular, normal, and other maps. | FFHQ-UV-Instrinsics | Dib et al., 2024 | [GitHub](https://github.com/ubisoft/ubisoft-laforge-FFHQ-UV-Intrinsics) |
| Anthropometric Measurements | 3D Facial Norms | Marazita et al., 2017 | [Website](https://www.facebase.org/resources/human/facial_norms/) |

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
| Bayesian model selection in R (Stan models) | loo | Vehtari et al., 2016 | [GitHub](https://github.com/stan-dev/loo) |
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
