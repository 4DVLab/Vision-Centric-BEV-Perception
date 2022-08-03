# Vision-Centric-BEV-Perception
Vision-Centric BEV Perception: A Survey

[comment]: <> (<p align="center"> <img src="./taxonomy_bev.png" width="95%"> </p>)
![](BEV_Survey/taxonomy_bev.png)

## Introduction



### (1) Datasets
![](BEV_Survey/Datasets_bev.png)

[comment]: <> (<p align="center"> <img src="./Datasets_bev.png" width="95%"> </p>)
### (2) GEOMETRY BASED PV2BEV
#### Homograph based PV2BEV
Public Papers:
- BridgeGAN (3DV'18) [[paper]](https://arxiv.org/pdf/1808.00327.pdf)[[project page]](https://github.com/xinge008/BridgeGAN)
- 3D-LaneNet (ICCV'19) [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Garnett_3D-LaneNet_End-to-End_3D_Multiple_Lane_Detection_ICCV_2019_paper.pdf)
- TrafCam3D (IROS'21) [[paper]](http://export.arxiv.org/pdf/2103.15293.pdf)
- PartNet (WACV'21) [[paper]](https://openaccess.thecvf.com/content/WACV2021/papers/Loukkal_Driving_Among_Flatmobiles_Bird-Eye-View_Occupancy_Grids_From_a_Monocular_Camera_WACV_2021_paper.pdf) 
- ScanObjectNN (ICCV'21) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Song_Stacked_Homography_Transformations_for_Multi-View_Pedestrian_Detection_ICCV_2021_paper.pdf) 

Chronological Overview:

![](BEV_Survey/homo-based-overview.PNG)

[comment]: <> (<p align="center"> <img src="./homo-based-overview.PNG" width="95%"> </p>)
#### Depth based PV2BEV
Public Papers:
- LSS (ECCV'20) [[paper]](https://arxiv.org/pdf/2008.05711.pdf) [[project page]](https://nv-tlabs.github.io/lift-splat-shoot/)
- CaDDN (CVPR'21) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Reading_Categorical_Depth_Distribution_Network_for_Monocular_3D_Object_Detection_CVPR_2021_paper.pdf) [[project page]](https://github.com/TRAILab/CaDDN)
- FIERY (ICCV'21) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Hu_FIERY_Future_Instance_Prediction_in_Birds-Eye_View_From_Surround_Monocular_ICCV_2021_paper.pdf) [[project page]](https://github.com/wayveai/fiery)
- Dfm (ECCV'22) [[paper]](https://arxiv.org/abs/2207.12988.pdf) [[project page]](https://github.com/Tai-Wang/Depth-from-Motion)
- ImvoxelNet (WACV'22) [[paper]](https://arxiv.org/pdf/2106.01178.pdf) [[project page]](https://github.com/saic-vul/imvoxelnet)

Chronological Overview:

[comment]: <> (<p align="center"> <img src="./depth-based-overview.png" width="95%"> </p>)
![](BEV_Survey/depth-based-overview.png)

Benchmark Results:

[comment]: <> (<p align="center"> <img src="./depth-based%20results.png" width="95%"> </p>)
![](BEV_Survey/depth-based%20results.png)

### (3) NETWORK BASED PV2BEV
#### MLP based PV2BEV
Public Papers:
- VED: Monocular Semantic Occupancy Grid Mapping with Convolutional Variational Encoder-Decoder Networks (RA-L'19) [[paper]](https://arxiv.org/pdf/1804.02176.pdf) [[project page]](https://github.com/Chenyang-Lu/mono-semantic-occupancy)
- VPN: Cross-view Semantic Segmentation for Sensing Surroundings (IROS'20) [[paper]](https://arxiv.org/pdf/1906.03560.pdf) [[project page]](https://view-parsing-network.github.io/)
- FishingNet: Future Inference of Semantic Heatmaps In Grids (Arxiv'20) [[paper]](https://arxiv.org/pdf/2006.09917)
- PON Predicting Semantic Map Representations from Images using Pyramid Occupancy Networks (CVPR'20) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Roddick_Predicting_Semantic_Map_Representations_From_Images_Using_Pyramid_Occupancy_Networks_CVPR_2020_paper.pdf) [[project page]](https://github.com/tom-roddick/mono-semantic-maps)
- STA-ST: Enabling spatio-temporal aggregation in Birds-Eye-View Vehicle Estimation (ICRA'21) [[paper]](https://cvssp.org/Personal/OscarMendez/papers/pdf/SahaICRA2021.pdf) 
- HDMapNet: An Online HD Map Construction and Evaluation Framework (ICRA'22) [[paper]](https://arxiv.org/pdf/2107.06307) [[project page]](https://tsinghua-mars-lab.github.io/HDMapNet/)
- Projecting Your View Attentively: Monocular Road Scene Layout Estimation via Cross-view Transformation (CVPR'21) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Projecting_Your_View_Attentively_Monocular_Road_Scene_Layout_Estimation_via_CVPR_2021_paper.pdf) [[project page]](https://github.com/JonDoe-297/cross-view)
- HFT: Lifting Perspective Representations via Hybrid Feature Transformation (Arxiv'22) [[paper]](https://arxiv.org/pdf/2204.05068) [[project page]](https://github.com/JiayuZou2020/HFT)

Chronological Overview:

[comment]: <> (<p align="center"> <img src="./MLP-based-overview.png" width="95%"> </p>)
![](BEV_Survey/MLP-based-overview1.png)

Benchmark Results:

[comment]: <> (<p align="center"> <img src="./MLP-based-result.png" width="95%"> </p>)
![](BEV_Survey/MLP-based-result.png)

#### Transformer based PV2BEV
Public Papers:
- STSU: Structured Bird’s-Eye-View Traffic Scene Understanding from Onboard Images (ICCV'21) [[paper]](https://arxiv.org/pdf/2110.01997) [[project page]](https://github.com/ybarancan/STSU)
- Image2Map: Translating Images into Maps (ICRA'22) [[paper]](https://arxiv.org/pdf/2110.00966.pdf) [[project page]](https://github.com/avishkarsaha/translating-images-into-maps)
- DETR3D: 3D Object Detection from Multi-view Images via 3D-to-2D Queries (CoRL'21) [[paper]](https://arxiv.org/pdf/2110.06922.pdf) [[project page]](https://github.com/WangYueFt/detr3d)
- TopologyPL: Topology Preserving Local Road Network Estimation from Single Onboard Camera Image (CVPR'22) [[paper]](https://arxiv.org/pdf/2112.10155.pdf) [[project page]](https://github.com/ybarancan/TopologicalLaneGraph)
- PETR: Position Embedding Transformation for Multi-View 3D Object Detection (ECCV'22) [[paper]](https://arxiv.org/pdf/2203.05625) [[project page]](https://github.com/megvii-research/PETR)
- BEVSegFormer: Bird's Eye View Semantic Segmentation From Arbitrary Camera Rigs (Arxiv'22) [[paper]](https://arxiv.org/pdf/2203.04050) 
- PersFormer: a New Baseline for 3D Laneline Detection (ECCV'22) [[paper]](https://arxiv.org/pdf/2203.11089) [[project page]](https://github.com/OpenPerceptionX/PersFormer_3DLane)
- MonoDTR: Monocular 3D Object Detection with Depth-Aware Transformer (CVPR'22) [[page]](https://arxiv.org/pdf/2203.10981) [[project page]](https://github.com/kuanchihhuang/MonoDTR)
- MonoDETR: Depth-guided Transformer for Monocular 3D Object Detection (Arxiv'22) [[paper]](https://arxiv.org/pdf/2203.13310.pdf) [[project page]](https://github.com/ZrrSkywalker/MonoDETR)
- BEVFormer: Learning Bird's-Eye-View Representation from Multi-Camera Images via Spatiotemporal Transformers (ECCV'22) [[paper]](https://arxiv.org/pdf/2203.17270v1.pdf) [[project page]](https://github.com/zhiqi-li/BEVFormer)
- GitNet: Geometric Prior-based Transformation for Birds-Eye-View Segmentation (ECCV'22) [[paper]](https://arxiv.org/pdf/2204.07733) 
- Graph-DETR3D: Rethinking Overlapping Regions for Multi-View 3D Object Detection (MM'22) [[paper]](https://arxiv.org/pdf/2204.11582) 
- CVT: Cross-view Transformers for real-time Map-view Semantic Segmentation (CVPR'22) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Cross-View_Transformers_for_Real-Time_Map-View_Semantic_Segmentation_CVPR_2022_paper.pdf) [[project page]](https://github.com/bradyz/)
- PETRv2: A Unified Framework for 3D Perception from Multi-Camera Images (Arxiv'22) [[paper]](https://arxiv.org/pdf/2206.01256) [[project page]](https://github.com/megvii-research/PETR)
- Ego3RT: Learning Ego 3D Representation as Ray Tracing (ECCV'22) [[paper]](https://arxiv.org/pdf/2206.04042.pdf) [[project page]](https://github.com/fudan-zvg/Ego3RT)
- GKT: Efficient and Robust 2D-to-BEV Representation Learning via Geometry-guided Kernel Transformer (Arxiv'22) [[paper]](https://arxiv.org/pdf/2206.04584.pdf) [[project page]](https://github.com/hustvl/GKT)
- PolarDETR: Polar Parametrization for Vision-based Surround-View 3D Detection (Arxiv'22) [[paper]](https://arxiv.org/pdf/2206.10965) [[project page]](https://github.com/hustvl/PolarDETR)
- LaRa: Latents and Rays for Multi-Camera Bird’s-Eye-View Semantic Segmentation (Arxiv'22) [[paper]](https://arxiv.org/pdf/2206.13294)
- SRCN3D: Sparse R-CNN 3D Surround-View Cameras 3D Object Detection and Tracking for Autonomous Driving (Arxiv'22) [[paper]](https://arxiv.org/pdf/2206.14451) [[project page]](https://github.com/synsin0/SRCN3D)
- PolarFormer: Multi-camera 3D Object Detection with Polar Transformers (Arxiv'22)[[paper]](https://arxiv.org/pdf/2206.15398) [[project page]](https://github.com/fudan-zvg/PolarFormer)
- ORA3D: ORA3D: Overlap Region Aware Multi-view 3D Object Detection (Arxiv'22) [[paper]](https://arxiv.org/pdf/2207.00865)
- CoBEVT: Cooperative Bird's Eye View Semantic Segmentation with Sparse Transformers (Arxiv'22)  [[paper]](https://arxiv.org/pdf/2207.02202.pdf)
 
Chronological Overview:

[comment]: <> (<p align="center"> <img src="./transformer-based-overview.png" width="95%"> </p>)
![](BEV_Survey/transformer-based-overview.png)

Benchmark Results:

![](BEV_Survey/transformer-based-results.png)
![](BEV_Survey/transformer-based-results1.png)

[comment]: <> (<p align="center"> <img src="./transformer-based-results.png" width="95%"> </p>)
[comment]: <> (<p align="center"> <img src="./transformer-based-results1.png" width="95%"> </p>)


### (4)  EXTENSION
#### Multi-Task Learning under BEV

[comment]: <> (<p align="center"> <img src="./multi-task-results.png" width="95%"> </p>)
![](BEV_Survey/multi-task-results.png)

#### Fusion under BEV
Multi-Modality Fusion:
- PointPainting: Sequential Fusion for 3D Object Detection (CVPR'19) [[paper]](https://arxiv.org/pdf/1911.10150.pdf) [[project page]](https://github.com/AmrElsersy/PointPainting)
- 3D-CVF: Generating Joint Camera and LiDAR Features Using Cross-View Spatial Feature Fusion for 3D Object Detection (ECCV'20) [[paper]](https://arxiv.org/pdf/2004.12636.pdf) [[project page]](https://github.com/rasd3/3D-CVF)
- FUTR3D: A Unified Sensor Fusion Framework for 3D Detection (Arxiv'22) [[paper]](https://arxiv.org/pdf/2203.10642) [[project page]](https://github.com/Tsinghua-MARS-Lab/futr3d)
- MVP: Multimodal Virtual Point 3D Detection (NIPS'21) [[paper]](https://arxiv.org/pdf/2111.06881.pdf) [[project page]](https://tianweiy.github.io/mvp/)
- PointAugmenting: Cross-Modal Augmentation for 3D Object Detection (CVPR'21) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_PointAugmenting_Cross-Modal_Augmentation_for_3D_Object_Detection_CVPR_2021_paper.html) [[project page]](https://github.com/VISION-SJTU/PointAugmenting)
- FusionPainting: Multimodal Fusion with Adaptive Attention for 3D Object Detection  (ITSC'21) [[paper]](https://arxiv.org/pdf/2106.12449) [[project page]](https://github.com/Shaoqing26/FusionPainting)
- Unifying Voxel-based Representation with Transformer for 3D Object Detection (Arxiv'21) [[paper]](https://arxiv.org/pdf/2206.00630) [[project page]](https://github.com/dvlab-research/UVTR)
- TransFusion: Robust LiDAR-Camera Fusion for 3D Object Detection with Transformers (CVPR'22) [[paper]](https://arxiv.org/pdf/2203.11496) [[project page]](https://github.com/XuyangBai/TransFusion)
- AutoAlign: Pixel-Instance Feature Aggregation for Multi-Modal 3D Object Detection (IJCAI'22) [[paper]](https://arxiv.org/pdf/2201.06493) [[project page]](https://github.com/zehuichen123/AutoAlignV2)
- AutoAlignV2: Deformable Feature Aggregation for Dynamic Multi-Modal 3D Object Detection (ECCV'22) [[paper]](https://arxiv.org/pdf/2207.10316v1.pdf) [[project page]](https://github.com/zehuichen123/AutoAlignV2)
- CenterFusion: Center-based Radar and Camera Fusion for 3D Object Detection  (WACV'21) [[paper]](https://arxiv.org/pdf]/2011.04841) [[project page]](https://github.com/mrnabati/CenterFusion)

[comment]: <> (<p align="center"> <img src="./multi-modal-results.png" width="95%"> </p>)
![](BEV_Survey/multi-modal-results.png)

Temporal Fusion:

[comment]: <> (<p align="center"> <img src="./temporal-results.png" width="95%"> </p>)
![](BEV_Survey/temporal-results.png)

Multi-agent Fusion:
- CoBEVT: Cooperative Bird's Eye View Semantic Segmentation with Sparse Transformers (Arxiv'22)  [[paper]](https://arxiv.org/pdf/2207.02202.pdf)


#### Empirical Know-Hows

### Citation

If you find our work useful in your research, please consider citing:


## Updates



## Related Repos

