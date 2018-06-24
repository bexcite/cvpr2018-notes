# CVPR 2018 Notes

Below are the links, notes and thoughts to the most interesting papers, challenges and workshops that came to me during the [CVPR 2018](http://cvpr2018.thecvf.com/) conference. Though, you probably may want to make your own notion of the progress in computer vision and pattern recognition by reviewing all 979 accepted papers and walk through the content of all 21 tutorials and 48 workshops:

* [CVPR 2018 Papers](http://openaccess.thecvf.com/CVPR2017.py)
* [CVPR 2018 Workshops Papers](http://openaccess.thecvf.com/CVPR2018_workshops/menu.py)
* [CVPR 2018 Tutorials](http://cvpr2018.thecvf.com/program/tutorials)
* [CVPR 2018 Workshops](http://cvpr2018.thecvf.com/program/workshops)

# Top Papers

Best Paper Award:
* __Taskonomy: Disentangling Task Transfer Learning.__ Amir R. Zamir, Alexander Sax, William Shen, Leonidas J. Guibas, Jitendra Malik, Silvio Savarese
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zamir_Taskonomy_Disentangling_Task_CVPR_2018_paper.pdf)

Honorable Mentions:
* __Deep Learning of Graph Matching__.
Andrei Zanfir, Cristian Sminchisescu
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zanfir_Deep_Learning_of_CVPR_2018_paper.pdf)

* __SPLATNet: Sparse Lattice Networks for Point Cloud Processing.__
Hang Su, Varun Jampani, Deqing Sun, Subhransu Maji, Evangelos Kalogerakis, Ming-Hsuan Yang, Jan Kautz
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Su_SPLATNet_Sparse_Lattice_CVPR_2018_paper.pdf)

* __CodeSLAM — Learning a Compact, Optimisable Representation for Dense Visual SLAM.__
Michael Bloesch, Jan Czarnowski, Ronald Clark, Stefan Leutenegger, Andrew J. Davison
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Bloesch_CodeSLAM_--_Learning_CVPR_2018_paper.pdf)

* __Efficient Optimization for Rank-Based Loss Functions__
Pritish Mohapatra, Michal Rolínek, C.V. Jawahar, Vladimir Kolmogorov, M. Pawan Kumar
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mohapatra_Efficient_Optimization_for_CVPR_2018_paper.pdf)

# Autonomous Driving and related topics: Visual odometry, SLAM, Localization.

Self driving cars was one of the most noticeable topic at the conference with huge booth's at the expo floor from nuTonomy, Aurora, Tesla, Waymo, Didi, Argo.ai, Baidu, Lyft, Uber, NVidia. Several workshops and challenges. Also it one that I'm personally most interested in though it get's the biggest chunk of my conference time.

## Challenges

Challenges related to the autonomous driving at CVPR 2018:

* [Autonomous Driving Challenge](http://wad.ai/challenge.html), CVPR 2018
* [Robust Vision Challenge](http://www.robustvision.net/), CVPR 2018

Future autonomous driving challenges:

* [Scene Understanding for Autonomous Navigation in Unstructured Environments](http://cvit.iiit.ac.in/autonue2018/), ECCV 2018
* [ApolloScape: Vision-based Navigation for Autonomous Driving](http://apolloscape.auto/ECCV/challenge.html), ECCV 2018


## Workshops/Tutorials

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

* __Learning Hierarchical Models for Class-Specific Reconstruction From Natural Data__. Arun CS Kumar, Suchendra M. Bhandarkar, Mukta Prasad, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Kumar_Learning_Hierarchical_Models_CVPR_2018_paper.pdf) (_detection_, _pose estimation_, _3D reconstruction_)

* __Subset Replay Based Continual Learning for Scalable Improvement of Autonomous Systems__. Pratik Prabhanjan Brahma, Adrienne Othon, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Brahma_Subset_Replay_Based_CVPR_2018_paper.pdf) (_Volkswagen_)

* __Deep Parametric Continuous Convolutional Neural Networks__. Shenlong Wang, Simon Suo, Wei-Chiu Ma, Andrei Pokrovsky, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Deep_Parametric_Continuous_CVPR_2018_paper.pdf) (_point cloud_, _segmentation_, _motion estimation_, _Uber_)

* __SurfConv: Bridging 3D and 2D Convolution for RGBD Images__. Hang Chu, Wei-Chiu Ma, Kaustav Kundu, Raquel Urtasun, Sanja Fidler, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chu_SurfConv_Bridging_3D_CVPR_2018_paper.pdf) (_3d segmentation_, _Uber_)

* __Hierarchical Recurrent Attention Networks for Structured Online Maps__. Namdar Homayounfar, Wei-Chiu Ma, Shrinidhi Kowshika Lakshmikanth, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Homayounfar_Hierarchical_Recurrent_Attention_CVPR_2018_paper.pdf) (_point cloud_, _road extraction_, _Uber_)

* __LEGO: Learning Edge With Geometry All at Once by Watching Videos__. Zhenheng Yang, Peng Wang, Yang Wang, Wei Xu, Ram Nevatia, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_LEGO_Learning_Edge_CVPR_2018_paper.pdf) (_3d reconstruction_, _Baidu_)

* __DeepVoting: A Robust and Explainable Deep Network for Semantic Part Detection Under Partial Occlusion__. Zhishuai Zhang, Cihang Xie, Jianyu Wang, Lingxi Xie, Alan L. Yuille, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_DeepVoting_A_Robust_CVPR_2018_paper.pdf) (_Baidu_)

* __ICE-BA: Incremental, Consistent and Efficient Bundle Adjustment for Visual-Inertial SLAM__. Haomin Liu, Mingyu Chen, Guofeng Zhang, Hujun Bao, Yingze Bao, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_ICE-BA_Incremental_Consistent_CVPR_2018_paper.pdf) [[source code]](https://github.com/baidu/ICE-BA) (_SLAM_, _Baidu_)

* __PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation__. Danfei Xu, Dragomir Anguelov, Ashesh Jain, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_PointFusion_Deep_Sensor_CVPR_2018_paper.pdf) (_3d detection_, _Zoox_)

* __Frustum PointNets for 3D Object Detection From RGB-D Data__. Charles R. Qi, Wei Liu, Chenxia Wu, Hao Su, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Qi_Frustum_PointNets_for_CVPR_2018_paper.pdf) (_3d detection_, _Nuro_)

* __Social GAN: Socially Acceptable Trajectories With Generative Adversarial Networks__. Agrim Gupta, Justin Johnson, Li Fei-Fei, Silvio Savarese, Alexandre Alahi, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gupta_Social_GAN_Socially_CVPR_2018_paper.pdf) (_trajectory prediction_, _Stanford_)

*


> _TBD_ (work in progress)

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


# Context Awareness

Context aware papers:
* __COCO-Stuff: Thing and Stuff Classes in Context__. Holger Caesar, Jasper Uijlings, Vittorio Ferrari, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Caesar_COCO-Stuff_Thing_and_CVPR_2018_paper.pdf) (_context_, _segmentation_, _Google_)


# Graph Based, Structure discovery

* __Image Generation From Scene Graphs__. Justin Johnson, Agrim Gupta, Li Fei-Fei, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Johnson_Image_Generation_From_CVPR_2018_paper.pdf)

* __Unsupervised Discovery of Object Landmarks as Structural Representations__. Yuting Zhang, Yijie Guo, Yixin Jin, Yijun Luo, Zhiyuan He, Honglak Lee [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Unsupervised_Discovery_of_CVPR_2018_paper.pdf) (_unsupervised_, _GAN_, _Google_)

* __Distributable Consistent Multi-Object Matching__. Nan Hu, Qixing Huang, Boris Thibert, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Distributable_Consistent_Multi-Object_CVPR_2018_paper.pdf) (_matching_, _Stanford_)



# Networks Optimization, Learning, Inference

* __MorphNet: Fast & Simple Resource-Constrained Structure Learning of Deep Networks__. Ariel Gordon, Elad Eban, Ofir Nachum, Bo Chen, Hao Wu, Tien-Ju Yang, Edward Choi, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gordon_MorphNet_Fast__CVPR_2018_paper.pdf)

* __Quantization and Training of Neural Networks for Efficient Integer-Arithmetic-Only Inference__. Benoit Jacob, Skirmantas Kligys, Bo Chen, Menglong Zhu, Matthew Tang, Andrew Howard, Hartwig Adam, Dmitry Kalenichenko, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Jacob_Quantization_and_Training_CVPR_2018_paper.pdf) (_Google_)



# Computational Imaging

* __Burst Denoising With Kernel Prediction Networks__. Ben Mildenhall, Jonathan T. Barron, Jiawen Chen, Dillon Sharlet, Ren Ng, Robert Carroll, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mildenhall_Burst_Denoising_With_CVPR_2018_paper.pdf) (_Google_)



# 3D Reconstruction

* __Pix3D: Dataset and Methods for Single-Image 3D Shape Modeling__. Xingyuan Sun, Jiajun Wu, Xiuming Zhang, Zhoutong Zhang, Chengkai Zhang, Tianfan Xue, Joshua B. Tenenbaum, William T. Freeman, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_Pix3D_Dataset_and_CVPR_2018_paper.pdf) (_3d reconstruction_, _dataset_, _Google_)

* __Factoring Shape, Pose, and Layout From the 2D Image of a 3D Scene__. Shubham Tulsiani, Saurabh Gupta, David F. Fouhey, Alexei A. Efros, Jitendra Malik, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tulsiani_Factoring_Shape_Pose_CVPR_2018_paper.pdf) (_3d reconstruction_, _Berkeley_)

* __Multi-View Consistency as Supervisory Signal for Learning Shape and Pose Prediction__. Shubham Tulsiani, Alexei A. Efros, Jitendra Malik, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tulsiani_Multi-View_Consistency_as_CVPR_2018_paper.pdf) (_Berkeley_)



# Other Papers

* __The Unreasonable Effectiveness of Deep Features as a Perceptual Metric__. Richard Zhang, Phillip Isola, Alexei A. Efros, Eli Shechtman, Oliver Wang, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_The_Unreasonable_Effectiveness_CVPR_2018_paper.pdf) (_Berkeley_, _OpenAI_, _Adobe_)

* __Learning to Look Around: Intelligently Exploring Unseen Environments for Unknown Tasks__. Dinesh Jayaraman, Kristen Grauman, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Jayaraman_Learning_to_Look_CVPR_2018_paper.pdf)

* __Deep Layer Aggregation__. Fisher Yu, Dequan Wang, Evan Shelhamer, Trevor Darrell, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_Deep_Layer_Aggregation_CVPR_2018_paper.pdf) (_Berkeley_)

* __Partial Transfer Learning With Selective Adversarial Networks__. Zhangjie Cao, Mingsheng Long, Jianmin Wang, Michael I. Jordan, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Cao_Partial_Transfer_Learning_CVPR_2018_paper.pdf)
