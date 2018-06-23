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
Lichen Zhou, Chuang Zhang, Ming Wu, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Zhou_D-LinkNet_LinkNet_With_CVPR_2018_paper.pdf) (_road extraction_)

* __Stacked U-Nets With Multi-Output for Road Extraction__
Tao Sun, Zehui Chen, Wenxiang Yang, Yin Wang,
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Sun_Stacked_U-Nets_With_CVPR_2018_paper.pdf) (_road extraction_)

* __Fully Convolutional Network for Automatic Road Extraction From Satellite Imagery__. Alexander Buslaev, Selim Seferbekov, Vladimir Iglovikov, Alexey Shvets
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Buslaev_Fully_Convolutional_Network_CVPR_2018_paper.pdf) (_road extraction_)

* __Road Detection With EOSResUNet and Post Vectorizing Algorithm__.
Oleksandr Filin, Anton Zapara, Serhii Panchenko, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Filin_Road_Detection_With_CVPR_2018_paper.pdf) (_road extraction_)

* __Residual Inception Skip Network for Binary Segmentation__. Jigar Doshi, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Doshi_Residual_Inception_Skip_CVPR_2018_paper.pdf) (_road extraction_)

* __Roadmap Generation Using a Multi-Stage Ensemble of Deep Neural Networks With Smoothing-Based Optimization__. Dragos Costea, Alina Marcu, Emil Slusanschi, Marius Leordeanu, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Costea_Roadmap_Generation_Using_CVPR_2018_paper.pdf) (_road extraction_)

* __Rotated Rectangles for Symbolized Building Footprint Extraction__. Matt Dickenson, Lionel Gueguen, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Dickenson_Rotated_Rectangles_for_CVPR_2018_paper.pdf) (_building detection_, _Uber_)

* __Feature Pyramid Network for Multi-Class Land Segmentation__. Selim Seferbekov, Vladimir Iglovikov, Alexander Buslaev, Alexey Shvets, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Seferbekov_Feature_Pyramid_Network_CVPR_2018_paper.pdf) (_land segmentation_, _Lyft_)

* __The ApolloScape Dataset for Autonomous Driving__.
Xinyu Huang, Xinjing Cheng, Qichuan Geng, Binbin Cao, Dingfu Zhou, Peng Wang, Yuanqing Lin, Ruigang Yang, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Huang_The_ApolloScape_Dataset_CVPR_2018_paper.pdf) (_dataset_)

* __Scene Understanding Networks for Autonomous Driving Based on Around View Monitoring System__. Jeong Yeol Baek, Ioana Veronica Chelu, Livia Iordache, Vlad Paunescu, HyunJoo Ryu, Alexandru Ghiuta, Andrei Petreanu, YunSung Soh, Andrei Leica, ByeongMoon Jeon, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Baek_Scene_Understanding_Networks_CVPR_2018_paper.pdf)

* __Training Deep Networks With Synthetic Data: Bridging the Reality Gap by Domain Randomization__. Jonathan Tremblay, Aayush Prakash, David Acuna, Mark Brophy, Varun Jampani, Cem Anil, Thang To, Eric Cameracci, Shaad Boochoon, Stan Birchfield, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Tremblay_Training_Deep_Networks_CVPR_2018_paper.pdf) (_NVidia_)

* __On the Iterative Refinement of Densely Connected Representation Levels for Semantic Segmentation__. Arantxa Casanova, Guillem Cucurull, Michal Drozdzal, Adriana Romero, Yoshua Bengio, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Casanova_On_the_Iterative_CVPR_2018_paper.pdf)

* __Minimizing Supervision for Free-Space Segmentation__. Satoshi Tsutsui, Tommi Kerola, Shunta Saito, David J. Crandall, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Tsutsui_Minimizing_Supervision_for_CVPR_2018_paper.pdf)

* __On the Importance of Stereo for Accurate Depth Estimation: An Efficient Semi-Supervised Deep Neural Network Approach__. Nikolai Smolyanskiy, Alexey Kamenev, Stan Birchfield, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Smolyanskiy_On_the_Importance_CVPR_2018_paper.pdf) (_NVidia_)

* __Accurate Deep Direct Geo-Localization From Ground Imagery and Phone-Grade GPS__. Shaohui Sun, Ramesh Sarukkai, Jack Kwok, Vinay Shet, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Sun_Accurate_Deep_Direct_CVPR_2018_paper.pdf) (_Lyft_)

* __Efficient and Safe Vehicle Navigation Based on Driver Behavior Classification__. Ernest Cheung, Aniket Bera, Dinesh Manocha, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Cheung_Efficient_and_Safe_CVPR_2018_paper.pdf)

* __Detection of Distracted Driver Using Convolutional Neural Network__. Bhakti Baheti, Suhas Gajre, Sanjay Talbar, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Baheti_Detection_of_Distracted_CVPR_2018_paper.pdf)

* __Classifying Group Emotions for Socially-Aware Autonomous Vehicle Navigation__. Aniket Bera, Tanmay Randhavane, Austin Wang, Dinesh Manocha, Emily Kubin, Kurt Gray, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Bera_Classifying_Group_Emotions_CVPR_2018_paper.pdf)

* __AutonoVi-Sim: Autonomous Vehicle Simulation Platform With Weather, Sensing, and Traffic Control__. Andrew Best, Sahil Narang, Lucas Pasqualin, Daniel Barber, Dinesh Manocha, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Best_AutonoVi-Sim_Autonomous_Vehicle_CVPR_2018_paper.pdf)

* __Learning Hierarchical Models for Class-Specific Reconstruction From Natural Data__. Arun CS Kumar, Suchendra M. Bhandarkar, Mukta Prasad, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Kumar_Learning_Hierarchical_Models_CVPR_2018_paper.pdf)

* __Subset Replay Based Continual Learning for Scalable Improvement of Autonomous Systems__. Pratik Prabhanjan Brahma, Adrienne Othon, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Brahma_Subset_Replay_Based_CVPR_2018_paper.pdf) (_Volkswagen_)


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
