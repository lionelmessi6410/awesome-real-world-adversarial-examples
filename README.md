# Awesome Real-world Adversarial Examples [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome real-world adversarial examples resources. 

It is worth noticing that this repository only lists the attack which can be realized in real-world, in other word, physical attack. For the digital one, please refer to another awesome repository [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning#blogs).

## Table of Contents
 - [Attack](#attack)
 - [Defense](#defense)
 - [Detection](#detection)
 - [ToolBox](#toolbox)

## Attack
**Classification**
- [Adversarial Patch](https://arxiv.org/pdf/1712.09665.pdf), T. B. Brown, D. Mané et al., NIPS 2017.
- [Adversarial Examples in the Physical World](https://arxiv.org/pdf/1607.02533.pdf), A. Kurakin et al., ICLR workshop 2017. [[video](https://www.youtube.com/watch?v=zQ_uMenoBCk&feature=youtu.be)]
- [Robust Physical-World Attacks on Machine Learning Models](https://s3.observador.pt/wp-content/uploads/2017/08/08133934/1707-08945.pdf), I. Evtimov, K. Eykholt, E. Fernandes, T. Kohno, B. Li, A. Prakash, A. Rahmati, D. Song, arXiv 2017.
- [Robust Physical-World Attacks on Deep Learning Visual Classification](https://openaccess.thecvf.com/content_cvpr_2018/papers/Eykholt_Robust_Physical-World_Attacks_CVPR_2018_paper.pdf), K. Eykholt, I. Evtimov et al., CVPR 2018. [[code](https://github.com/evtimovi/robust_physical_perturbations)]
- [LaVAN: Localized and Visible Adversarial Noise](http://proceedings.mlr.press/v80/karmon18a/karmon18a.pdf), D. Karmon et al., ICML 2018.
- [Synthesizing Robust Adversarial Examples](http://proceedings.mlr.press/v80/athalye18b/athalye18b.pdf), A. Athalye, L. Engstrom, A. Ilyas et al., ICML 2018. [[video](https://www.youtube.com/watch?v=YXy6oX1iNoA&feature=youtu.be)]
- [DARTS: Deceiving Autonomous Cars with Toxic Signs](https://arxiv.org/pdf/1802.06430.pdf), C. Sitawarin, A. N. Bhagoji et al. arXiv 2018.
- [Adversarial camera stickers: A physical camera-based attack on deep learning systems](https://arxiv.org/pdf/1904.00759.pdf), J. B. Li et al., ICML 2019.
- [Adversarial Attacks Beyond the Image Space](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zeng_Adversarial_Attacks_Beyond_the_Image_Space_CVPR_2019_paper.pdf), X. Zeng et al., CVPR 2019.
- [Simple Physical Adversarial Examples against End-to-End Autonomous Driving Models](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8782514), A. Boloor et al., ICESS 2019.
- [Perceptual-Sensitive GAN for Generating Adversarial Patches](https://pdfs.semanticscholar.org/fea9/09742eeb8d6140220b069ebc4607f9a329ca.pdf?_ga=2.198718639.167863768.1593878874-1184421833.1593878874), A. Liu et al., AAAI 2019.
- [Adversarial Camouflage: Hiding Physical-World Attacks with Natural Styles](https://openaccess.thecvf.com/content_CVPR_2020/papers/Duan_Adversarial_Camouflage_Hiding_Physical-World_Attacks_With_Natural_Styles_CVPR_2020_paper.pdf), R. Duan et al., CVPR 2020.

**Face Recognition**
- [Accessorize to a Crime: Real and Stealthy Attacks on State-of-the-Art Face Recognition](https://dl.acm.org/doi/pdf/10.1145/2976749.2978392), M. Sharif et al., CCS 2016. [[code](https://github.com/mahmoods01/accessorize-to-a-crime), [talk](https://www.youtube.com/watch?v=6Xh1vuwnVhU&list=PLDJxfCuZwWGBpmLhReNGUn-Sl1vuaumKZ&index=8)]
- [A General Framework for Adversarial Examples with Objectives](https://dl.acm.org/doi/pdf/10.1145/3317611), M. Sharif et al., ACM TOPS 2019. [[code](https://github.com/mahmoods01/agns), [talk](https://www.youtube.com/watch?v=1ea0QQ8UgDA)]
- [AdvHat: Real-world adversarial attack on ArcFace Face ID system](https://arxiv.org/pdf/1908.08705.pdf), S. Komkov et al. arXiv 2019. [[code](https://github.com/papermsucode/advhat), [video](https://www.youtube.com/watch?v=a4iNg0wWBsQ&feature=youtu.be)]

**Object Detection**
- [ShapeShifter: Robust Physical Adversarial Attack on Faster R-CNN Object Detector](https://link.springer.com/content/pdf/10.1007%2F978-3-030-10925-7_4.pdf), S. T. Chen et al., ECML-PKDD 2018. [[code](https://github.com/shangtse/robust-physical-attack)]
- [Physical Adversarial Examples for Object Detectors](https://www.usenix.org/system/files/conference/woot18/woot18-paper-eykholt.pdf), K. Eykholt et al., WOOT 2018.
- [Fooling automated surveillance cameras: adversarial patches to attack person detection](https://openaccess.thecvf.com/content_CVPRW_2019/papers/CV-COPS/Thys_Fooling_Automated_Surveillance_Cameras_Adversarial_Patches_to_Attack_Person_Detection_CVPRW_2019_paper.pdf), S. Thys, W. V. Ranst et al., CVPR workshop 2019. [[video](https://www.youtube.com/watch?v=MIbFvK2S9g8)]
- [DPATCH: An Adversarial Patch Attack on Object Detectors](https://arxiv.org/pdf/1806.02299.pdf), X Liu et al., AAAI workshop 2019.
- [On Physical Adversarial Patches for Object Detection](https://arxiv.org/pdf/1906.11897.pdf), M. Lee et al., ICML workshop 2019. [[video](https://www.youtube.com/watch?v=WXnQjbZ1e7Y)]
- [CAMOU: Learning Physical Vehicle Camouflages to Adversarially Attack Detectors in the Wild](https://openreview.net/pdf?id=SJgEl3A5tm), Y. Zhang et al., ICLR 2019.
- [Making an Invisibility Cloak: Real World Adversarial Attacks on Object Detectors](https://arxiv.org/pdf/1910.14667.pdf), Z. Wu et al, arXiv 2019. [[blog](https://www.cs.umd.edu/~tomg/projects/invisible/)]
- [Adversarial T-shirt! Evading Person Detectors in A Physical World](https://arxiv.org/pdf/1910.11099.pdf), K. Xu et al, arXiv 2019. [[blog](https://medium.com/@ODSC/evading-real-time-person-detectors-by-adversarial-t-shirt-8e0149e97e5a)]
- [Design and Interpretation of Universal Adversarial Patches in Face Detection](https://arxiv.org/pdf/1912.05021.pdf), X. Yang, F. Wei, H. Zhang et al., arXiv 2019.

**Visual Tracking**
- [Physical Adversarial Textures That Fool Visual Object Tracking](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wiyatno_Physical_Adversarial_Textures_That_Fool_Visual_Object_Tracking_ICCV_2019_paper.pdf), R. R. Wiyatno et al., ICCV 2019.

## Defense
**Classification**
- [On Visible Adversarial Perturbations & Digital Watermarking](https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w32/Hayes_On_Visible_Adversarial_CVPR_2018_paper.pdf), J. Hayes, CVPR workshop 2018.
- [Local Gradients Smoothing: Defense against localized adversarial attacks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8658401), M. Naseer et al., WACV 2019.
- [DoPa: A Comprehensive CNN Detection Methodology against Physical Adversarial Attacks](https://arxiv.org/pdf/1905.08790.pdf), Z. Xu et al., arXiv 2019.
- [Connecting the Digital and Physical World: Improving the Robustness of Adversarial Attacks](https://gangw.cs.illinois.edu/AAAI19.pdf), S. T.K. Jan et al., AAAI 2019. [[code](https://github.com/stevetkjan/Digital2Physical)]
- [Certified Defenses for Adversarial Patches](https://openreview.net/pdf?id=HyeaSkrYPH), P. Chiang, R. Ni et al., ICLR 2020. [[code](https://github.com/Ping-C/certifiedpatchdefense)]
- [(De)Randomized Smoothing for Certifiable Defense against Patch Attacks](https://arxiv.org/pdf/2002.10733.pdf), A. Levine et al., arXiv 2020.
- [LanCe: A Comprehensive and Lightweight CNN Defense Methodology against
Physical Adversarial Attacks on Embedded Multimedia Applications](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9045584), Z. Xu et al., ASP-DAC 2020.
- [Universal Adversarial Training](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-ShafahiA.4630.pdf), A. Shafahi, M. Najibi, Z. Xu et al., AAAI 2020.
- [Minority Reports Defense: Defending Against Adversarial Patches](https://arxiv.org/pdf/2004.13799.pdf), M. McCoyd et al., arXiv 2020.
- [PatchGuard: Provable Defense against Adversarial Patches Using Masks on Small Receptive Fields](https://arxiv.org/pdf/2005.10884.pdf), C. Xiang et al., arXiv 2020. [[code](https://github.com/inspire-group/PatchGuard)]
- [Adversarial Training against Location-Optimized Adversarial Patches](https://arxiv.org/pdf/2005.02313.pdf), S. Rao et al., arXiv 2020.

**Object Detection**
- [Information Distribution Based Defense Against Physical Attacks on Object Detection](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9105983), G. Zhou et al., ICMEW 2020.

## Detection
**Classification**
- [SentiNet: Detecting Localized Universal Attacks Against Deep Learning Systems](https://arxiv.org/pdf/1812.00292.pdf), E. Chou et al., arXiv 2020.

## ToolBox
- [CleverHans](https://github.com/tensorflow/cleverhans)
- [AdverTorch](https://github.com/BorealisAI/advertorch)
- [AdvBox](https://github.com/advboxes/AdvBox)
- [Adversarial Robustness Toolbox](https://github.com/IBM/adversarial-robustness-toolbox)
- [Adversarial-Face-Attack](https://github.com/ppwwyyxx/Adversarial-Face-Attack)

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Chia-Hung Yuan has waived all copyright and related or neighboring rights to this work.
