# CVPR 2018 Notes

Below are the links, notes and thoughts about the most interesting papers, challenges and workshops that I came across during the [CVPR 2018](http://cvpr2018.thecvf.com/) conference. Though, you probably may want to form your own notion of the progress in computer vision and pattern recognition by reviewing all 979 accepted papers and walking through the content of all 21 tutorials and 48 workshops:

* [CVPR 2018 Papers](http://openaccess.thecvf.com/CVPR2018.py)
* [CVPR 2018 Workshops Papers](http://openaccess.thecvf.com/CVPR2018_workshops/menu.py)
* [CVPR 2018 Tutorials](http://cvpr2018.thecvf.com/program/tutorials)
* [CVPR 2018 Workshops](http://cvpr2018.thecvf.com/program/workshops)

NOTE: The categories and tags of the papers are very soft and often one paper can be in autonomous driving, 3D vision and graph-based related categories but I select one that to my best knowledge suits better and will be easier for me to find later.

# Top Papers

Best Paper Award:
* __Taskonomy: Disentangling Task Transfer Learning.__ Amir R. Zamir, Alexander Sax, William Shen, Leonidas J. Guibas, Jitendra Malik, Silvio Savarese
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zamir_Taskonomy_Disentangling_Task_CVPR_2018_paper.pdf)
[[project page]](http://taskonomy.stanford.edu/)
[[code]](https://github.com/StanfordVL/taskonomy)

Honorable Mentions:
* __Deep Learning of Graph Matching__.
Andrei Zanfir, Cristian Sminchisescu
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zanfir_Deep_Learning_of_CVPR_2018_paper.pdf)

* __SPLATNet: Sparse Lattice Networks for Point Cloud Processing.__
Hang Su, Varun Jampani, Deqing Sun, Subhransu Maji, Evangelos Kalogerakis, Ming-Hsuan Yang, Jan Kautz
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Su_SPLATNet_Sparse_Lattice_CVPR_2018_paper.pdf)
[[code]](https://github.com/NVlabs/splatnet)

* __CodeSLAM — Learning a Compact, Optimisable Representation for Dense Visual SLAM.__
Michael Bloesch, Jan Czarnowski, Ronald Clark, Stefan Leutenegger, Andrew J. Davison
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Bloesch_CodeSLAM_--_Learning_CVPR_2018_paper.pdf)

* __Efficient Optimization for Rank-Based Loss Functions__
Pritish Mohapatra, Michal Rolínek, C.V. Jawahar, Vladimir Kolmogorov, M. Pawan Kumar
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mohapatra_Efficient_Optimization_for_CVPR_2018_paper.pdf)



# Autonomous Driving and related topics: Visual odometry, SLAM, Localization.

Self-driving cars were one of the most noticeable topics at the conference with huge booth's on the expo floor from nuTonomy, Aurora, Tesla, Waymo, Didi, Argo.ai, Baidu, Lyft, Uber, NVidia. There were several workshops and challenges. Also it's one that I'm personally most interested in though it get's the biggest chunk of my conference time.


## Autonomous Driving Challenges

Challenges related to the autonomous driving at CVPR 2018:

* [Autonomous Driving Challenge](http://wad.ai/challenge.html), CVPR 2018
* [Robust Vision Challenge](http://www.robustvision.net/), CVPR 2018

Future autonomous driving challenges:

* [Scene Understanding for Autonomous Navigation in Unstructured Environments](http://cvit.iiit.ac.in/autonue2018/), ECCV 2018
* [ApolloScape: Vision-based Navigation for Autonomous Driving](http://apolloscape.auto/ECCV/challenge.html), ECCV 2018


## Autonomous Driving Datasets

Most mentioned datasets related to the self-driving car space:
* [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/)
* [ApolloScape Dataset](http://apolloscape.auto/)
* [Berkeley DeepDrive (BDD100K)](https://deepdrive.berkeley.edu/)
* [Oxford RobotCar Dataset](http://robotcar-dataset.robots.ox.ac.uk/)
* [Cityscapes Dataset](https://www.cityscapes-dataset.com/)
* [HD1K Dataset](http://hci-benchmark.org/)
* [WildDash Dataset](http://www.wilddash.cc/)
* [DAVIS Driving Dataset](https://docs.google.com/document/d/1HM0CSmjO8nOpUeTvmPjopcBcVCk7KXvLUuiZFS6TWSg/pub), and other [datasets](http://sensors.ini.uzh.ch/databases.html) from INI Zurich
* [TorontoCity Dataset](https://arxiv.org/abs/1612.00423) (didn't find a link to the dataset page)


## Autonomous driving related workshops/tutorials

Mentioned workshops and tutorials cover the most frequent topics related to the self-driving car development space.

* [Workshop on Autonomous Driving](http://www.wad.ai/), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W14.py)
* [Robust Vision Challenge](http://www.robustvision.net/)
* [Embedded Vision Workshop](https://embeddedvisionworkshop.wordpress.com/), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W12.py)
* [Workshop on Visual Odometry and Computer Vision Applications Based on Location Clues](http://www.cis.rit.edu/~glpci/vocvalc2018/), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W30.py)
* [Beyond Supervised Learning](http://www.beyond-supervised.ai/)
* [Computational Imaging for Self-Driving Vehicles](http://imagingav.media.mit.edu/)
* [Computer Vision for Robotics and Driving](https://sites.google.com/view/visionroboticsdriving)
* [Deep Learning for Visual SLAM](http://visualslam.ai/), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W9.py)
* [Joint Detection, Tracking, and Prediction in the Wild](http://trajnet.stanford.edu/workshops/2018/), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W29.py)
* [DeepGlobe: A Challenge for Parsing the Earth through Satellite Images](	DeepGlobe: A Challenge for Parsing the Earth through Satellite Images), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W4.py)



## Autonomous Driving Papers

Here the papers that I've noticed during oral or spotlight sessions, or as a poster. Some of they directly related to the autonomous cars and from companies like Uber/Lyft, but some of them cover broader topic or direction that can be used for self-driving car development.

* __Semantic Binary Segmentation Using Convolutional Networks Without Decoders__. Shubhra Aich, William van der Kamp, Ian Stavness, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Aich_Semantic_Binary_Segmentation_CVPR_2018_paper.pdf) (_road extraction_)

* __D-LinkNet: LinkNet With Pretrained Encoder and Dilated Convolution for High Resolution Satellite Imagery Road Extraction__
Lichen Zhou, Chuang Zhang, Ming Wu, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Zhou_D-LinkNet_LinkNet_With_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Stacked U-Nets With Multi-Output for Road Extraction__
Tao Sun, Zehui Chen, Wenxiang Yang, Yin Wang,
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Sun_Stacked_U-Nets_With_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Fully Convolutional Network for Automatic Road Extraction From Satellite Imagery__. Alexander Buslaev, Selim Seferbekov, Vladimir Iglovikov, Alexey Shvets
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Buslaev_Fully_Convolutional_Network_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Road Detection With EOSResUNet and Post Vectorizing Algorithm__.
Oleksandr Filin, Anton Zapara, Serhii Panchenko, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Filin_Road_Detection_With_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Residual Inception Skip Network for Binary Segmentation__. Jigar Doshi, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Doshi_Residual_Inception_Skip_CVPR_2018_paper.pdf) (_road extraction_)

* __Roadmap Generation Using a Multi-Stage Ensemble of Deep Neural Networks With Smoothing-Based Optimization__. Dragos Costea, Alina Marcu, Emil Slusanschi, Marius Leordeanu, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Costea_Roadmap_Generation_Using_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Rotated Rectangles for Symbolized Building Footprint Extraction__. Matt Dickenson, Lionel Gueguen, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Dickenson_Rotated_Rectangles_for_CVPR_2018_paper.pdf) (_building detection_, _segmentation_, _Uber_)

* __Feature Pyramid Network for Multi-Class Land Segmentation__. Selim Seferbekov, Vladimir Iglovikov, Alexander Buslaev, Alexey Shvets, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Seferbekov_Feature_Pyramid_Network_CVPR_2018_paper.pdf) (_land segmentation_, _Lyft_)

* __The ApolloScape Dataset for Autonomous Driving__.
Xinyu Huang, Xinjing Cheng, Qichuan Geng, Binbin Cao, Dingfu Zhou, Peng Wang, Yuanqing Lin, Ruigang Yang, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Huang_The_ApolloScape_Dataset_CVPR_2018_paper.pdf) (_dataset_, _detection_, _segmentation_, _localization_, _Baidu_)

* __Scene Understanding Networks for Autonomous Driving Based on Around View Monitoring System__. Jeong Yeol Baek, Ioana Veronica Chelu, Livia Iordache, Vlad Paunescu, HyunJoo Ryu, Alexandru Ghiuta, Andrei Petreanu, YunSung Soh, Andrei Leica, ByeongMoon Jeon, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Baek_Scene_Understanding_Networks_CVPR_2018_paper.pdf) (_detection_)

* __Training Deep Networks With Synthetic Data: Bridging the Reality Gap by Domain Randomization__. Jonathan Tremblay, Aayush Prakash, David Acuna, Mark Brophy, Varun Jampani, Cem Anil, Thang To, Eric Cameracci, Shaad Boochoon, Stan Birchfield, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Tremblay_Training_Deep_Networks_CVPR_2018_paper.pdf) (_detection_, _NVidia_)

* __On the Iterative Refinement of Densely Connected Representation Levels for Semantic Segmentation__. Arantxa Casanova, Guillem Cucurull, Michal Drozdzal, Adriana Romero, Yoshua Bengio, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Casanova_On_the_Iterative_CVPR_2018_paper.pdf)

* __Minimizing Supervision for Free-Space Segmentation__. Satoshi Tsutsui, Tommi Kerola, Shunta Saito, David J. Crandall, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Tsutsui_Minimizing_Supervision_for_CVPR_2018_paper.pdf)

* __On the Importance of Stereo for Accurate Depth Estimation: An Efficient Semi-Supervised Deep Neural Network Approach__. Nikolai Smolyanskiy, Alexey Kamenev, Stan Birchfield, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Smolyanskiy_On_the_Importance_CVPR_2018_paper.pdf) (_depth estimation_, _NVidia_)

* __Accurate Deep Direct Geo-Localization From Ground Imagery and Phone-Grade GPS__. Shaohui Sun, Ramesh Sarukkai, Jack Kwok, Vinay Shet, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Sun_Accurate_Deep_Direct_CVPR_2018_paper.pdf) (_Lyft_)

* __Efficient and Safe Vehicle Navigation Based on Driver Behavior Classification__. Ernest Cheung, Aniket Bera, Dinesh Manocha, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Cheung_Efficient_and_Safe_CVPR_2018_paper.pdf)

* __Detection of Distracted Driver Using Convolutional Neural Network__. Bhakti Baheti, Suhas Gajre, Sanjay Talbar, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Baheti_Detection_of_Distracted_CVPR_2018_paper.pdf)

* __Classifying Group Emotions for Socially-Aware Autonomous Vehicle Navigation__. Aniket Bera, Tanmay Randhavane, Austin Wang, Dinesh Manocha, Emily Kubin, Kurt Gray, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Bera_Classifying_Group_Emotions_CVPR_2018_paper.pdf)

* __AutonoVi-Sim: Autonomous Vehicle Simulation Platform With Weather, Sensing, and Traffic Control__. Andrew Best, Sahil Narang, Lucas Pasqualin, Daniel Barber, Dinesh Manocha, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Best_AutonoVi-Sim_Autonomous_Vehicle_CVPR_2018_paper.pdf)

* __Subset Replay Based Continual Learning for Scalable Improvement of Autonomous Systems__. Pratik Prabhanjan Brahma, Adrienne Othon, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Brahma_Subset_Replay_Based_CVPR_2018_paper.pdf) (_Volkswagen_)

* __Deep Parametric Continuous Convolutional Neural Networks__. Shenlong Wang, Simon Suo, Wei-Chiu Ma, Andrei Pokrovsky, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Deep_Parametric_Continuous_CVPR_2018_paper.pdf) (_point cloud_, _segmentation_, _motion estimation_, _Uber_)

* __Hierarchical Recurrent Attention Networks for Structured Online Maps__. Namdar Homayounfar, Wei-Chiu Ma, Shrinidhi Kowshika Lakshmikanth, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Homayounfar_Hierarchical_Recurrent_Attention_CVPR_2018_paper.pdf) (_point cloud_, _road extraction_, _Uber_)

* __DeepVoting: A Robust and Explainable Deep Network for Semantic Part Detection Under Partial Occlusion__. Zhishuai Zhang, Cihang Xie, Jianyu Wang, Lingxi Xie, Alan L. Yuille, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_DeepVoting_A_Robust_CVPR_2018_paper.pdf) (_Baidu_)

* __ICE-BA: Incremental, Consistent and Efficient Bundle Adjustment for Visual-Inertial SLAM__. Haomin Liu, Mingyu Chen, Guofeng Zhang, Hujun Bao, Yingze Bao, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_ICE-BA_Incremental_Consistent_CVPR_2018_paper.pdf) [[source code]](https://github.com/baidu/ICE-BA) (_SLAM_, _Baidu_)

* __Social GAN: Socially Acceptable Trajectories With Generative Adversarial Networks__. Agrim Gupta, Justin Johnson, Li Fei-Fei, Silvio Savarese, Alexandre Alahi, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gupta_Social_GAN_Socially_CVPR_2018_paper.pdf) (_trajectory prediction_, _Stanford_)

* __Fast and Furious: Real Time End-to-End 3D Detection, Tracking and Motion Forecasting With a Single Convolutional Net__. Wenjie Luo, Bin Yang, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Luo_Fast_and_Furious_CVPR_2018_paper.pdf)
(_detection_, _tracking_, _prediction_, _Uber_)

* __DeLS-3D: Deep Localization and Segmentation With a 3D Semantic Map__. Peng Wang, Ruigang Yang, Binbin Cao, Wei Xu, Yuanqing Lin, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_DeLS-3D_Deep_Localization_CVPR_2018_paper.pdf)
(_Baidu_)

* __Multi-Task Learning Using Uncertainty to Weigh Losses for Scene Geometry and Semantics__. Alex Kendall, Yarin Gal, Roberto Cipolla, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kendall_Multi-Task_Learning_Using_CVPR_2018_paper.pdf)
(_depth estimation_)

* __Matching Adversarial Networks__. Gellért Máttyus, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mattyus_Matching_Adversarial_Networks_CVPR_2018_paper.pdf)
(_segmentation_, _Uber_)


### 3D Reconstruction & 3D Vision

* __Learning Hierarchical Models for Class-Specific Reconstruction From Natural Data__. Arun CS Kumar, Suchendra M. Bhandarkar, Mukta Prasad, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Kumar_Learning_Hierarchical_Models_CVPR_2018_paper.pdf)
(_detection_, _pose estimation_, _3d reconstruction_)

* __PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation__. Danfei Xu, Dragomir Anguelov, Ashesh Jain, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_PointFusion_Deep_Sensor_CVPR_2018_paper.pdf)
(_3d detection_, _Zoox_)

* __Frustum PointNets for 3D Object Detection From RGB-D Data__. Charles R. Qi, Wei Liu, Chenxia Wu, Hao Su, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Qi_Frustum_PointNets_for_CVPR_2018_paper.pdf)
(_3d detection_, _Nuro_)

* __3D-RCNN: Instance-Level 3D Object Reconstruction via Render-and-Compare__. Abhijit Kundu, Yin Li, James M. Rehg, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kundu_3D-RCNN_Instance-Level_3D_CVPR_2018_paper.pdf)
[[project page]](http://abhijitkundu.info/projects/3D-RCNN/)

* __LEGO: Learning Edge With Geometry All at Once by Watching Videos__. Zhenheng Yang, Peng Wang, Yang Wang, Wei Xu, Ram Nevatia, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_LEGO_Learning_Edge_CVPR_2018_paper.pdf)
(_3d reconstruction_, _Baidu_)

* __SurfConv: Bridging 3D and 2D Convolution for RGBD Images__. Hang Chu, Wei-Chiu Ma, Kaustav Kundu, Raquel Urtasun, Sanja Fidler, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chu_SurfConv_Bridging_3D_CVPR_2018_paper.pdf)
(_3d segmentation_, _Uber_)

* __PIXOR: Real-Time 3D Object Detection From Point Clouds__. Bin Yang, Wenjie Luo, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_PIXOR_Real-Time_3D_CVPR_2018_paper.pdf)
(_Uber_)

Below are papers from other topics that are not always related to the autonomous driving.


# Context/Geometry Awareness

Context aware papers:
* __COCO-Stuff: Thing and Stuff Classes in Context__. Holger Caesar, Jasper Uijlings, Vittorio Ferrari, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Caesar_COCO-Stuff_Thing_and_CVPR_2018_paper.pdf) (_context_, _segmentation_, _Google_)

* __Finding "It": Weakly-Supervised Reference-Aware Visual Grounding in Instructional Videos__. De-An Huang, Shyamal Buch, Lucio Dery, Animesh Garg, Li Fei-Fei, Juan Carlos Niebles, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_Finding_It_Weakly-Supervised_CVPR_2018_paper.pdf)
(_Stanford_)

* __Context Encoding for Semantic Segmentation__. Hang Zhang, Kristin Dana, Jianping Shi, Zhongyue Zhang, Xiaogang Wang, Ambrish Tyagi, Amit Agrawal, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Context_Encoding_for_CVPR_2018_paper.pdf)
(_Amazon_)

Geometry awareness:
* __Geometry-Aware Learning of Maps for Camera Localization__. Samarth Brahmbhatt, Jinwei Gu, Kihwan Kim, James Hays, Jan Kautz, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Brahmbhatt_Geometry-Aware_Learning_of_CVPR_2018_paper.pdf) [[project page]](http://research.nvidia.com/publication/2018-06_Geometry-Aware-Learning-of)
[[code]](https://github.com/NVlabs/geomapnet)
(_localization_, _SLAM_, _NVidia_)

* __Geometry Guided Convolutional Neural Networks for Self-Supervised Video Representation Learning__. Chuang Gan, Boqing Gong, Kun Liu, Hao Su, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gan_Geometry_Guided_Convolutional_CVPR_2018_paper.pdf)
(_Stanford_, _MIT_)

* __Unsupervised Learning of Depth and Ego-Motion From Monocular Video Using 3D Geometric Constraints__. Reza Mahjourian, Martin Wicke, Anelia Angelova, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mahjourian_Unsupervised_Learning_of_CVPR_2018_paper.pdf)
(_Google_)



# Graph Based, Structure discovery

* __Image Generation From Scene Graphs__. Justin Johnson, Agrim Gupta, Li Fei-Fei, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Johnson_Image_Generation_From_CVPR_2018_paper.pdf)

* __Unsupervised Discovery of Object Landmarks as Structural Representations__. Yuting Zhang, Yijie Guo, Yixin Jin, Yijun Luo, Zhiyuan He, Honglak Lee [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Unsupervised_Discovery_of_CVPR_2018_paper.pdf) (_unsupervised_, _GAN_, _Google_)

* __Distributable Consistent Multi-Object Matching__. Nan Hu, Qixing Huang, Boris Thibert, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Distributable_Consistent_Multi-Object_CVPR_2018_paper.pdf) (_matching_, _Stanford_)

* __Referring Relationships__. Ranjay Krishna, Ines Chami, Michael Bernstein, Li Fei-Fei, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Krishna_Referring_Relationships_CVPR_2018_paper.pdf)
(_detection_, _Stanford_)

* __Beyond Holistic Object Recognition: Enriching Image Understanding With Part States__. Cewu Lu, Hao Su, Yonglu Li, Yongyi Lu, Li Yi, Chi-Keung Tang, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lu_Beyond_Holistic_Object_CVPR_2018_paper.pdf)

* __Iterative Visual Reasoning Beyond Convolutions__. Xinlei Chen, Li-Jia Li, Li Fei-Fei, Abhinav Gupta, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Iterative_Visual_Reasoning_CVPR_2018_paper.pdf)
[[code]](https://github.com/endernewton/iter-reason)
(_Stanford_)



# Networks Optimization, Learning, Inference

* __MorphNet: Fast & Simple Resource-Constrained Structure Learning of Deep Networks__. Ariel Gordon, Elad Eban, Ofir Nachum, Bo Chen, Hao Wu, Tien-Ju Yang, Edward Choi, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gordon_MorphNet_Fast__CVPR_2018_paper.pdf)

* __Quantization and Training of Neural Networks for Efficient Integer-Arithmetic-Only Inference__. Benoit Jacob, Skirmantas Kligys, Bo Chen, Menglong Zhu, Matthew Tang, Andrew Howard, Hartwig Adam, Dmitry Kalenichenko, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Jacob_Quantization_and_Training_CVPR_2018_paper.pdf) (_Google_)

* __Low-Latency Video Semantic Segmentation__. Yule Li, Jianping Shi, Dahua Lin, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Low-Latency_Video_Semantic_CVPR_2018_paper.pdf)
(_optimization_)

* __Shift: A Zero FLOP, Zero Parameter Alternative to Spatial Convolutions__. Bichen Wu, Alvin Wan, Xiangyu Yue, Peter Jin, Sicheng Zhao, Noah Golmant, Amir Gholaminejad, Joseph Gonzalez, Kurt Keutzer, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wu_Shift_A_Zero_CVPR_2018_paper.pdf)
(_Berkeley_)

* __NISP: Pruning Networks Using Neuron Importance Score Propagation__. Ruichi Yu, Ang Li, Chun-Fu Chen, Jui-Hsin Lai, Vlad I. Morariu, Xintong Han, Mingfei Gao, Ching-Yung Lin, Larry S. Davis, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_NISP_Pruning_Networks_CVPR_2018_paper.pdf)
(_DeepMind_, _Adobe_)

* __SBNet: Sparse Blocks Network for Fast Inference__. Mengye Ren, Andrei Pokrovsky, Bin Yang, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Ren_SBNet_Sparse_Blocks_CVPR_2018_paper.pdf)
(_Uber_)

* __HydraNets: Specialized Dynamic Architectures for Efficient Inference__. Ravi Teja Mullapudi, William R. Mark, Noam Shazeer, Kayvon Fatahalian, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mullapudi_HydraNets_Specialized_Dynamic_CVPR_2018_paper.pdf)
(_CMU_, _Google_, _Stanford_)

* __A PID Controller Approach for Stochastic Optimization of Deep Networks__. Wangpeng An, Haoqian Wang, Qingyun Sun, Jun Xu, Qionghai Dai, Lei Zhang, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/An_A_PID_Controller_CVPR_2018_paper.pdf)

* __Deep Spatio-Temporal Random Fields for Efficient Video Segmentation__. Siddhartha Chandra, Camille Couprie, Iasonas Kokkinos, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chandra_Deep_Spatio-Temporal_Random_CVPR_2018_paper.pdf)
(_Facebook_)


* __MobileNetV2: Inverted Residuals and Linear Bottlenecks__. Mark Sandler, Andrew Howard, Menglong Zhu, Andrey Zhmoginov, Liang-Chieh Chen, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sandler_MobileNetV2_Inverted_Residuals_CVPR_2018_paper.pdf)
(_Google_)


* __Latent RANSAC__. Simon Korman, Roee Litman, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Korman_Latent_RANSAC_CVPR_2018_paper.pdf)

# Computational Imaging

* __Burst Denoising With Kernel Prediction Networks__. Ben Mildenhall, Jonathan T. Barron, Jiawen Chen, Dillon Sharlet, Ren Ng, Robert Carroll, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mildenhall_Burst_Denoising_With_CVPR_2018_paper.pdf) (_Google_)



# 3D Reconstruction | Depth Estimation

* __Pix3D: Dataset and Methods for Single-Image 3D Shape Modeling__. Xingyuan Sun, Jiajun Wu, Xiuming Zhang, Zhoutong Zhang, Chengkai Zhang, Tianfan Xue, Joshua B. Tenenbaum, William T. Freeman, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_Pix3D_Dataset_and_CVPR_2018_paper.pdf) (_3d reconstruction_, _dataset_, _Google_)

* __Factoring Shape, Pose, and Layout From the 2D Image of a 3D Scene__. Shubham Tulsiani, Saurabh Gupta, David F. Fouhey, Alexei A. Efros, Jitendra Malik, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tulsiani_Factoring_Shape_Pose_CVPR_2018_paper.pdf) (_3d reconstruction_, _Berkeley_)

* __Multi-View Consistency as Supervisory Signal for Learning Shape and Pose Prediction__. Shubham Tulsiani, Alexei A. Efros, Jitendra Malik, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tulsiani_Multi-View_Consistency_as_CVPR_2018_paper.pdf) (_Berkeley_)

* __Aperture Supervision for Monocular Depth Estimation__. Pratul P. Srinivasan, Rahul Garg, Neal Wadhwa, Ren Ng, Jonathan T. Barron, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Srinivasan_Aperture_Supervision_for_CVPR_2018_paper.pdf)
(_Berkeley_, _Google_)

* __Gibson Env: Real-World Perception for Embodied Agents__. Fei Xia, Amir R. Zamir, Zhiyang He, Alexander Sax, Jitendra Malik, Silvio Savarese, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xia_Gibson_Env_Real-World_CVPR_2018_paper.pdf)
[[project page]](http://gibsonenv.stanford.edu/)
(_depth estimation_, _multi task_, _Berkeley_, _Stanford_)

* __Unsupervised Learning of Monocular Depth Estimation and Visual Odometry With Deep Feature Reconstruction__. Huangying Zhan, Ravi Garg, Chamara Saroj Weerasekera, Kejie Li, Harsh Agarwal, Ian Reid, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhan_Unsupervised_Learning_of_CVPR_2018_paper.pdf)
[[code]](https://github.com/Huangying-Zhan/Depth-VO-Feat)
(_localization_)


# Human pose detection, tracking, re-identification

Humans detection, segmentation, tracking, 3d reconstruction, re-localization and other topics around our body parts was a huge part of the CVPR 2018. Here I just mention a few references because I was more on autonomous, localization, SLAM ans robotics topics.

* __Person Transfer GAN to Bridge Domain Gap for Person Re-Identification__. Longhui Wei, Shiliang Zhang, Wen Gao, Qi Tian, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wei_Person_Transfer_GAN_CVPR_2018_paper.pdf)

* __Depth-Based 3D Hand Pose Estimation: From Current Achievements to Future Goals__. Shanxin Yuan et al., [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yuan_Depth-Based_3D_Hand_CVPR_2018_paper.pdf)

* __PoseTrack: A Benchmark for Human Pose Estimation and Tracking__. Mykhaylo Andriluka, Umar Iqbal, Eldar Insafutdinov, Leonid Pishchulin, Anton Milan, Juergen Gall, Bernt Schiele, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Andriluka_PoseTrack_A_Benchmark_CVPR_2018_paper.pdf) [[project page]](https://posetrack.net/)
(_Google_, _Amazon_)

* __DensePose: Dense Human Pose Estimation in the Wild__. Rıza Alp Güler, Natalia Neverova, Iasonas Kokkinos, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Guler_DensePose_Dense_Human_CVPR_2018_paper.pdf)
(_Facebook_)


# 3D Vision

* __Recurrent Slice Networks for 3D Segmentation of Point Clouds__. Qiangui Huang, Weiyue Wang, Ulrich Neumann, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_Recurrent_Slice_Networks_CVPR_2018_paper.pdf) [[source code]](https://github.com/qianguih/RSNet)

* __Consensus Maximization for Semantic Region Correspondences__. Pablo Speciale, Danda P. Paudel, Martin R. Oswald, Hayko Riemenschneider, Luc Van Gool, Marc Pollefeys, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Speciale_Consensus_Maximization_for_CVPR_2018_paper.pdf)
(_ETH_)

* __Manifold Learning in Quotient Spaces__. Éloi Mehr, André Lieutier, Fernando Sanchez Bermudez, Vincent Guitteny, Nicolas Thome, Matthieu Cord, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mehr_Manifold_Learning_in_CVPR_2018_paper.pdf)

* __ScanComplete: Large-Scale Scene Completion and Semantic Segmentation for 3D Scans__. Angela Dai, Daniel Ritchie, Martin Bokeloh, Scott Reed, Jürgen Sturm, Matthias Nießner, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Dai_ScanComplete_Large-Scale_Scene_CVPR_2018_paper.pdf)
(_Stanford_, _Google_)

* __3D Semantic Segmentation With Submanifold Sparse Convolutional Networks__. Benjamin Graham, Martin Engelcke, Laurens van der Maaten, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Graham_3D_Semantic_Segmentation_CVPR_2018_paper.pdf)
(_Facebook_)

* __Real-Time Seamless Single Shot 6D Object Pose Prediction__. Bugra Tekin, Sudipta N. Sinha, Pascal Fua, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tekin_Real-Time_Seamless_Single_CVPR_2018_paper.pdf)
(_Microsoft_)

* __3D Pose Estimation and 3D Model Retrieval for Objects in the Wild__. Alexander Grabner, Peter M. Roth, Vincent Lepetit, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Grabner_3D_Pose_Estimation_CVPR_2018_paper.pdf)


* __VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection__. Yin Zhou, Oncel Tuzel, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_VoxelNet_End-to-End_Learning_CVPR_2018_paper.pdf)
(_Apple_)

# Localization, SLAM

* __CVM-Net: Cross-View Matching Network for Image-Based Ground-to-Aerial Geo-Localization__. Sixing Hu, Mengdan Feng, Rang M. H. Nguyen, Gim Hee Lee, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_CVM-Net_Cross-View_Matching_CVPR_2018_paper.pdf)

* __Benchmarking 6DOF Outdoor Visual Localization in Changing Conditions__. Torsten Sattler, Will Maddern, Carl Toft, Akihiko Torii, Lars Hammarstrand, Erik Stenborg, Daniel Safari, Masatoshi Okutomi, Marc Pollefeys, Josef Sivic, Fredrik Kahl, Tomas Pajdla, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sattler_Benchmarking_6DOF_Outdoor_CVPR_2018_paper.pdf)
[[project page]](http://visuallocalization.net/)

* __Semantic Visual Localization__. Johannes L. Schönberger, Marc Pollefeys, Andreas Geiger, Torsten Sattler, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Schonberger_Semantic_Visual_Localization_CVPR_2018_paper.pdf)
(_ETH_)


# Domain adaptation

* __Domain Adaptive Faster R-CNN for Object Detection in the Wild__. Yuhua Chen, Wen Li, Christos Sakaridis, Dengxin Dai, Luc Van Gool, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Domain_Adaptive_Faster_CVPR_2018_paper.pdf)
(_ETH_)



# Other Papers

* __The Unreasonable Effectiveness of Deep Features as a Perceptual Metric__. Richard Zhang, Phillip Isola, Alexei A. Efros, Eli Shechtman, Oliver Wang, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_The_Unreasonable_Effectiveness_CVPR_2018_paper.pdf) (_Berkeley_, _OpenAI_, _Adobe_)

* __Learning to Look Around: Intelligently Exploring Unseen Environments for Unknown Tasks__. Dinesh Jayaraman, Kristen Grauman, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Jayaraman_Learning_to_Look_CVPR_2018_paper.pdf)

* __Deep Layer Aggregation__. Fisher Yu, Dequan Wang, Evan Shelhamer, Trevor Darrell, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_Deep_Layer_Aggregation_CVPR_2018_paper.pdf)
(_Berkeley_)

* __Partial Transfer Learning With Selective Adversarial Networks__. Zhangjie Cao, Mingsheng Long, Jianmin Wang, Michael I. Jordan, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Cao_Partial_Transfer_Learning_CVPR_2018_paper.pdf)

* __Hybrid Camera Pose Estimation__. Federico Camposeco, Andrea Cohen, Marc Pollefeys, Torsten Sattler, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Camposeco_Hybrid_Camera_Pose_CVPR_2018_paper.pdf)
(_3d vision_, _ETH_)

* __Five-point Fundamental Matrix Estimation for Uncalibrated Cameras__. Five-Point Fundamental Matrix Estimation for Uncalibrated Cameras, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Barath_Five-Point_Fundamental_Matrix_CVPR_2018_paper.pdf)

* __PlaneNet: Piece-Wise Planar Reconstruction From a Single RGB Image__. Chen Liu, Jimei Yang, Duygu Ceylan, Ersin Yumer, Yasutaka Furukawa, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_PlaneNet_Piece-Wise_Planar_CVPR_2018_paper.pdf)
(_3d reconstruction_, _Argo.ai_)

* __Egocentric Activity Recognition on a Budget__. Rafael Possas, Sheila Pinto Caceres, Fabio Ramos, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Possas_Egocentric_Activity_Recognition_CVPR_2018_paper.pdf)
(_AR optimized_)

* __CNN in MRF: Video Object Segmentation via Inference in A CNN-Based Higher-Order Spatio-Temporal MRF__. Linchao Bao, Baoyuan Wu, Wei Liu, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Bao_CNN_in_MRF_CVPR_2018_paper.pdf)

* __Features for Multi-Target Multi-Camera Tracking and Re-Identification__. Ergys Ristani, Carlo Tomasi, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Ristani_Features_for_Multi-Target_CVPR_2018_paper.pdf)

* __Occlusion Aware Unsupervised Learning of Optical Flow__. Yang Wang, Yi Yang, Zhenheng Yang, Liang Zhao, Peng Wang, Wei Xu, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Occlusion_Aware_Unsupervised_CVPR_2018_paper.pdf)


* __Adversarial Feature Augmentation for Unsupervised Domain Adaptation__. Riccardo Volpi, Pietro Morerio, Silvio Savarese, Vittorio Murino, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Volpi_Adversarial_Feature_Augmentation_CVPR_2018_paper.pdf)
(_GAN_)

* __LIME: Live Intrinsic Material Estimation__. Abhimitra Meka, Maxim Maximov, Michael Zollhöfer, Avishek Chatterjee, Hans-Peter Seidel, Christian Richardt, Christian Theobalt, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Meka_LIME_Live_Intrinsic_CVPR_2018_paper.pdf)

* __Learning to Segment Every Thing__. Ronghang Hu, Piotr Dollár, Kaiming He, Trevor Darrell, Ross Girshick, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Learning_to_Segment_CVPR_2018_paper.pdf)
(_Berkeley_, _BAIR_, _Facebook_)

* __Efficient Video Object Segmentation via Network Modulation__. Linjie Yang, Yanran Wang, Xuehan Xiong, Jianchao Yang, Aggelos K. Katsaggelos, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_Efficient_Video_Object_CVPR_2018_paper.pdf)
(_Snap_, _Google_)

* __Mobile Video Object Detection With Temporally-Aware Feature Maps__. Mason Liu, Menglong Zhu, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Mobile_Video_Object_CVPR_2018_paper.pdf)
(_Google_)

* __MaskLab: Instance Segmentation by Refining Object Detection With Semantic and Direction Features__. Liang-Chieh Chen, Alexander Hermans, George Papandreou, Florian Schroff, Peng Wang, Hartwig Adam, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_MaskLab_Instance_Segmentation_CVPR_2018_paper.pdf)

* __Squeeze-and-Excitation Networks__. Jie Hu, Li Shen, Gang Sun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Squeeze-and-Excitation_Networks_CVPR_2018_paper.pdf)
[[code]](https://github.com/hujie-frank/SENet)
(_Momenta.ai_)

* __InLoc: Indoor Visual Localization With Dense Matching and View Synthesis__. Hajime Taira, Masatoshi Okutomi, Torsten Sattler, Mircea Cimpoi, Marc Pollefeys, Josef Sivic, Tomas Pajdla, Akihiko Torii, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Taira_InLoc_Indoor_Visual_CVPR_2018_paper.pdf)
(_ETH_, _Microsoft_)

* __Low-Shot Learning From Imaginary Data__, Yu-Xiong Wang, Ross Girshick, Martial Hebert, Bharath Hariharan, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Low-Shot_Learning_From_CVPR_2018_paper.pdf)
(_Facebook_)

* __Discriminative Learning of Latent Features for Zero-Shot Recognition__. Yan Li, Junge Zhang, Jianguo Zhang, Kaiqi Huang, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Discriminative_Learning_of_CVPR_2018_paper.pdf)

* __PWC-Net: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume__. Deqing Sun, Xiaodong Yang, Ming-Yu Liu, Jan Kautz, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_PWC-Net_CNNs_for_CVPR_2018_paper.pdf)
(_robust vision winner_, _NVidia_)

* __Feature Space Transfer for Data Augmentation__. Bo Liu, Xudong Wang, Mandar Dixit, Roland Kwitt, Nuno Vasconcelos, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Feature_Space_Transfer_CVPR_2018_paper.pdf)
(_Microsoft_)

* __Detail-Preserving Pooling in Deep Networks__. Faraz Saeedan, Nicolas Weber, Michael Goesele, Stefan Roth, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Saeedan_Detail-Preserving_Pooling_in_CVPR_2018_paper.pdf)
(_Oculus_)

* __ST-GAN: Spatial Transformer Generative Adversarial Networks for Image Compositing__. Chen-Hsuan Lin, Ersin Yumer, Oliver Wang, Eli Shechtman, Simon Lucey, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lin_ST-GAN_Spatial_Transformer_CVPR_2018_paper.pdf)
(_Adobe_, _Argo.ai_)

* __Revisiting Deep Intrinsic Image Decompositions__. Qingnan Fan, Jiaolong Yang, Gang Hua, Baoquan Chen, David Wipf, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Fan_Revisiting_Deep_Intrinsic_CVPR_2018_paper.pdf)
(_Microsoft_)

* __Accurate and Diverse Sampling of Sequences Based on a “Best of Many” Sample Objective__. Apratim Bhattacharyya, Bernt Schiele, Mario Fritz, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Bhattacharyya_Accurate_and_Diverse_CVPR_2018_paper.pdf)

* __ROAD: Reality Oriented Adaptation for Semantic Segmentation of Urban Scenes__, Yuhua Chen, Wen Li, Luc Van Gool, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_ROAD_Reality_Oriented_CVPR_2018_paper.pdf)
(_augmentation_, _ETH_)

* __DeblurGAN: Blind Motion Deblurring Using Conditional Adversarial Networks__. Orest Kupyn, Volodymyr Budzan, Mykola Mykhailych, Dmytro Mishkin, Jiří Matas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kupyn_DeblurGAN_Blind_Motion_CVPR_2018_paper.pdf) [[code]](https://github.com/KupynOrest/DeblurGAN)

* __A Perceptual Measure for Deep Single Image Camera Calibration__. Yannick Hold-Geoffroy, Kalyan Sunkavalli, Jonathan Eisenmann, Matthew Fisher, Emiliano Gambaretto, Sunil Hadap, Jean-François Lalonde, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hold-Geoffroy_A_Perceptual_Measure_CVPR_2018_paper.pdf)
(_360 imaging_)
