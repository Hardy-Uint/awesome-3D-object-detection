> 作者：Tom Hardy
>
> 公众号：[3D视觉工坊](https://mp.weixin.qq.com/s?__biz=MzU1MjY4MTA1MQ==&mid=2247484684&idx=1&sn=e812540aee03a4fc54e44d5555ccb843&chksm=fbff2e38cc88a72e180f0f6b0f7b906dd616e7d71fffb9205d529f1238e8ef0f0c5554c27dd7&token=691734513&lang=zh_CN#rd)

主要针对3D object相关算法进行了汇总，分为基于RGB图像、立体视觉、点云、融合四种方式，欢迎补充~ 



# 基于单目图像的3D检测



![image-20200223231758890](https://github.com/Tom-Hardy-3D-Vision-Workshop/awesome-3D-object-detection/blob/master/image-20200223231758890.png)

1. [Task-Aware Monocular Depth Estimation for 3D Object Detection](https://arxiv.org/abs/1909.07701)
2. [M3D-RPN: Monocular 3D Region Proposal Network for Object Detection](https://arxiv.org/abs/1907.06038v1)
3. [Monocular 3D Object Detection and Box Fitting Trained End-to-End Using Intersection-over-Union Loss](https://arxiv.org/pdf/1906.08070.pdf)
4. [Disentangling Monocular 3D Object Detection](https://arxiv.org/pdf/1905.12365v1.pdf)
5. [Shift R-CNN: Deep Monocular 3D Object Detection with Closed-Form Geometric Constraints](https://arxiv.org/pdf/1905.09970.pdf)
6. [Monocular 3D Object Detection via Geometric Reasoning on Keypoints](https://arxiv.org/abs/1905.05618?context=cs.CV)
7. [Monocular 3D Object Detection Leveraging Accurate Proposals and Shape Reconstruction](https://arxiv.org/abs/1904.01690)
8. [GS3D: An Efficient 3D Object Detection Framework for Autonomous Driving](https://arxiv.org/abs/1903.10955)
9. [Accurate Monocular Object Detection via Color-Embedded 3D Reconstruction for Autonomous Driving](https://arxiv.org/abs/1903.11444?context=cs.CV)
10. [Task-Aware Monocular Depth Estimation for 3D Object Detection](https://arxiv.org/abs/1909.07701)
11. [M3D-RPN: Monocular 3D Region Proposal Network for Object Detection](https://arxiv.org/abs/1907.06038v1)
12. [Deconvolutional Networks for Point-Cloud Vehicle Detection and Tracking in Driving Scenarios](https://arxiv.org/abs/1808.07935)
# 基于立体视觉的3D检测

![image-20200223231827080](https://github.com/Tom-Hardy-3D-Vision-Workshop/awesome-3D-object-detection/blob/master/image-20200223231827080.png)



1. [Object-Centric Stereo Matching for 3D Object Detection](https://arxiv.org/pdf/1909.07566.pdf)
2. [Triangulation Learning Network: from Monocular to Stereo 3D Object Detection](https://arxiv.org/pdf/1906.01193.pdf)
3. [Pseudo-LiDAR from Visual Depth Estimation: Bridging the Gap in 3D Object Detection for Autonomous Driving](http://www.cs.cornell.edu/~yanwang/project/plidar/)
4. [Stereo R-CNN based 3D Object Detection for Autonomous Driving](https://arxiv.org/pdf/1902.09738.pdf)
5. [IDA-3D: Instance-Depth-Aware 3D Object Detection from Stereo Vision for Autonomous Driving（CVPR2020）](http://openaccess.thecvf.com/content_CVPR_2020/papers/Peng_IDA-3D_Instance-Depth-Aware_3D_Object_Detection_From_Stereo_Vision_for_Autonomous_CVPR_2020_paper.pdf) [源代码](https://github.com/swords123/IDA-3D)
6. [Disp R-CNN: Stereo 3D Object Detection via Shape Prior Guided Instance Disparity Estimation（CVPR2020)](https://arxiv.org/abs/2004.03572) [源代码](https://github.com/zju3dv/disprcn)
7. [DSGN: Deep Stereo Geometry Network for 3D Object Detection(CVPR2020)](https://arxiv.org/abs/2001.03398) [源代码](https://github.com/chenyilun95/DSGN)

# 基于激光雷达点云的3D检测

![image-20200223231856518](https://github.com/Tom-Hardy-3D-Vision-Workshop/awesome-3D-object-detection/blob/master/image-20200223231856518.png)


1. [End-to-End Multi-View Fusion for 3D Object Detection in LiDAR Point Clouds]()
2. [Vehicle Detection from 3D Lidar Using Fully Convolutional Network(百度早期工作)](https://arxiv.org/abs/1608.07916)
3. [VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection](https://arxiv.org/pdf/1711.06396.pdf)
4. [Object Detection and Classification in Occupancy Grid Maps using Deep Convolutional Networks](https://arxiv.org/pdf/1805.08689.pdf)
5. [RT3D: Real-Time 3-D Vehicle Detection in LiDAR Point Cloud for Autonomous Driving](https://www.onacademic.com/detail/journal_1000040467923610_4dfe.html)
6. [BirdNet: a 3D Object Detection Framework from LiDAR information](https://arxiv.org/pdf/1805.01195.pdf)
7. [LMNet: Real-time Multiclass Object Detection on CPU using 3D LiDAR](https://arxiv.org/pdf/1805.04902.pdf)
8. [HDNET: Exploit HD Maps for 3D Object Detection](https://link.zhihu.com/?target=http%3A//proceedings.mlr.press/v87/yang18b/yang18b.pdf)
9. [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://arxiv.org/pdf/1612.00593.pdf)
10. [PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space](https://arxiv.org/abs/1706.02413)
11. [IPOD: Intensive Point-based Object Detector for Point Cloud](https://arxiv.org/abs/1812.05276v1)
12. [PIXOR: Real-time 3D Object Detection from Point Clouds](http://www.cs.toronto.edu/~wenjie/papers/cvpr18/pixor.pdf)
13. [DepthCN: Vehicle Detection Using 3D-LIDAR and ConvNet](https://www.baidu.com/link?url=EaE2zYjHkWvF33nsET2eNvbFGFu8-D3wWPia04uyKm95jMetHsSv3Zk-tODPGm5clsgCUgtVULsZ6IQqv0EYS_Z8El7Zzh57XzlJroSkaOuC8yv7r1XXL4bUrM2tWrTgjwqzfMV2tMTnFNbMOmHLTkUobgMg7HKoS6WW6PfQzkG&wd=&eqid=8f320cfa0005b878000000055e528b6d)
14. [YOLO3D: End-to-end real-time 3D Oriented Object Bounding Box Detection from LiDAR Point Cloud](https://arxiv.org/abs/1808.02350)
15. [Voxel-FPN: multi-scale voxel feature aggregation in 3D object detection from point clouds](https://arxiv.org/ftp/arxiv/papers/1907/1907.05286.pdf)
16. [STD: Sparse-to-Dense 3D Object Detector for Point Cloud](https://arxiv.org/abs/1907.10471)
17. [Fast Point R-CNN](https://arxiv.org/abs/1908.02990)
18. [StarNet: Targeted Computation for Object Detection in Point Clouds](https://arxiv.org/abs/1908.11069)
19. [Class-balanced Grouping and Sampling for Point Cloud 3D Object Detection](https://arxiv.org/abs/1908.09492v1)
20. [LaserNet: An Efficient Probabilistic 3D Object Detector for Autonomous Driving](https://arxiv.org/abs/1903.08701v1)
21. [FVNet: 3D Front-View Proposal Generation for Real-Time Object Detection from Point Clouds](https://arxiv.org/abs/1903.10750v1)
22. [Part-A^2 Net: 3D Part-Aware and Aggregation Neural Network for Object Detection from Point Cloud](https://arxiv.org/abs/1907.03670v1)
23. [PointRCNN: 3D Object Proposal Generation and Detection from Point Cloud](https://arxiv.org/abs/1812.04244)
24. [Complex-YOLO: Real-time 3D Object Detection on Point Clouds](https://arxiv.org/abs/1803.06199)
25. [YOLO4D: A ST Approach for RT Multi-object Detection and Classification from LiDAR Point Clouds]()
26. [YOLO3D: End-to-end real-time 3D Oriented Object Bounding Box Detection from LiDAR Point Cloud](https://arxiv.org/abs/1808.02350)
27. [Monocular 3D Object Detection with Pseudo-LiDAR Point Cloud](https://arxiv.org/pdf/1903.09847.pdf)
28. [Structure Aware Single-stage 3D Object Detection from Point Cloud（CVPR2020)](http://openaccess.thecvf.com/content_CVPR_2020/html/He_Structure_Aware_Single-Stage_3D_Object_Detection_From_Point_Cloud_CVPR_2020_paper.html) [源代码](https://github.com/skyhehe123/SA-SSD)
29. [MLCVNet: Multi-Level Context VoteNet for 3D Object Detection（CVPR2020)](https://arxiv.org/abs/2004.05679) [源代码](https://github.com/NUAAXQ/MLCVNet)
30. [3DSSD: Point-based 3D Single Stage Object Detector（CVPR2020）](https://arxiv.org/abs/2002.10187) [源代码](https://github.com/tomztyang/3DSSD)
31. [LiDAR-based Online 3D Video Object Detection with Graph-based Message Passing and Spatiotemporal Transformer Attention（CVPR2020）](https://arxiv.org/abs/2004.01389) [源代码](https://github.com/yinjunbo/3DVID)
32. [PV-RCNN: Point-Voxel Feature Set Abstraction for 3D Object Detection(CVPR2020)](https://arxiv.org/abs/1912.13192) [源代码](https://github.com/sshaoshuai/PV-RCNN)
33. [Point-GNN: Graph Neural Network for 3D Object Detection in a Point Cloud（CVPR2020）](https://arxiv.org/abs/2003.01251) [源代码](https://github.com/WeijingShi/Point-GNN)



# 基于摄像头和激光雷达融合的3D目标检测

![image-20200223231920757](https://github.com/Tom-Hardy-3D-Vision-Workshop/awesome-3D-object-detection/blob/master/image-20200223231920757.png)



1. [MLOD: A multi-view 3D object detection based on robust feature fusion method](https://arxiv.org/abs/1909.04163v1)
2. [Multi-Sensor 3D Object Box Refinement for Autonomous Driving](https://arxiv.org/abs/1909.04942?context=cs)
3. [Pseudo-LiDAR++: Accurate Depth for 3D Object Detection in Autonomous Driving](https://arxiv.org/abs/1906.06310v1)
4. [Improving 3D Object Detection for Pedestrians with Virtual Multi-View Synthesis Orientation Estimation](https://arxiv.org/abs/1907.06777)
5. [Class-specific Anchoring Proposal for 3D Object Recognition in LIDAR and RGB Images](https://arxiv.org/abs/1907.09081)
6. [MVX-Net: Multimodal VoxelNet for 3D Object Detection](https://arxiv.org/pdf/1904.01649.pdf)
7. [Sensor Fusion for Joint 3D Object Detection and Semantic Segmentation](https://arxiv.org/abs/1904.11466v1)
8. [3D Object Detection Using Scale Invariant and Feature Reweighting Networks](https://arxiv.org/abs/1901.02237v1)
9. [End-to-End Pseudo-LiDAR for Image-Based 3D Object Detection（CVPR2020）](https://arxiv.org/abs/2004.03080) [源代码](https://github.com/mileyan/pseudo-LiDAR_e2e)

