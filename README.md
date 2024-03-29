# ML-Application-on-Network
This repo is created mainly for updating recent researches about the AI on Network.

## Benchmark
You can find a popular wifi activity recognition dataset [[here](https://github.com/ermongroup/Wifi_Activity_Recognition)].

I will reproduce some famous algorithms and report their performance on this dataset if I am free.

## Conference
### MobiCom 2021
* Yongzhi Huang, Kaixin Chen, Yandao Huang, Lu Wang, Kaishun Wu.</br>
"Vi-Liquid: Unknown Liquid Identification with Your Smartphone Vibration".
[[paper](https://www.huangyongzhi.com.cn/data/Vi-Liquid.pdf)]
    - Liquid sensing iwth mobile phone.
    
* Xiulong Liu, Dongdong Liu, Jiuwu Zhang, Tao Gu, Keqiu Li. </br>
"RFID and Camera Fusion for Recognition of Human-object Interactions".
[[paper](https://dl.acm.org/doi/abs/10.1145/3447993.3483244)]
    - Incorporate RFID with vision.
    
* Shuangjiao Zhai, Zhanyong Tang, Petteri Nurmi, Dingyi Fang, Xiaojiang Chen, Zheng Wang. </br>
"RISE: robust wireless sensing using probabilistic and statistical assessments".
[[paper](https://helda.helsinki.fi/bitstream/handle/10138/338770/mobicom21_final474_1_.pdf?sequence=1)]
    - For robust wireless sensing.

* Tianyue Zheng, Zhe Chen, Jun Luo, Lin Ke, Chaoyang Zhao, Yaowen Yang. </br>
"SiWa: see into walls via deep UWB radar".
[[paper](https://arxiv.org/pdf/2110.14279.pdf)]

* Andrea Ferlini, Dong Ma, Robert Harle, Cecilia Mascolo. </br>
"EarGate: Gait-based User Identification with In-ear Microphones".
[[paper](https://arxiv.org/pdf/2108.12305.pdf)]

* Zhe Chen, Tianyue Zheng, Chao Cai, Jun Luo.</br>
"MoVi-Fi: Motion-robust Vital Signs Waveform Recovery via Deep Interpreted RF Sensing".
[[paper](https://tianyuez.github.io/pubs/movifi.pdf)]
    - Sensing vital signs with RF.
 
### MobiSys 2021
* Hongfei Xue, Yan Ju, et. al. </br>
"mmMesh: Towards 3D Real-Time Dynamic Human Mesh Construction Using Millimeter-Wave".
[[paper](https://engineering.purdue.edu/~lusu/papers/MobiSys2021.pdf)]
    - 3D skeleton using millimeter-wav.
    
* Belal Korany, Yasamin Mostofi. </br>
"Counting a stationary crowd using off-the-shelf wifi".
[[paper](https://dl.acm.org/doi/pdf/10.1145/3458864.3468012)]
    - Stationary crowd using WiFi.
    
* Dong Ma, Andrea Ferlini, Cecilia Mascolo. </br>
"OESense: Employing Occlusion Effect for In-ear Human Sensing".
[[paper](https://arxiv.org/pdf/2106.08607.pdf)]
    - HAR using smart earbuds.
    
* Xiaomin Ouyang, Zhiyuan Xie, Jiayu Zhou, Jianwei Huang, Guoliang Xing. </br>
"ClusterFL: A Similarity-Aware Federated Learning System for Human Activity Recognition".
[[paper](http://aiot.ie.cuhk.edu.hk/papers/ClusterFL.pdf)]

### SenSys 2021
* Linlin Tu, Xiaomin Ouyang, Jiayu Zhou, Yuze He, Guoliang Xing.</br>
"FedDL: Federated Learning via Dynamic Layer Sharing for Human Activity Recognition".
[[paper](https://dl.acm.org/doi/abs/10.1145/3485730.3485946)]
    - Employing federated learning into HAR.
    
* Tiantian Liu, Ming Gao, Feng Lin, Chao Wang, Zhongjie Ba, Jinsong Han, Wenyao Xu, Kui Ren. </br>
"Wavoice: A Noise-resistant Multi-modal Speech Recognition System Fusing mmWave and Audio Signals".
[[paper](https://cse.buffalo.edu/~wenyaoxu/papers/conference/xu-sensys2021.pdf)]
    - Multimodal system of RF and speech.
    
* Tianyue Zheng, Zhe Chen, Shujie Zhang, Chao Cai, Jun Luo.</br>
"MoRe-Fi: Motion-robust and Fine-grained Respiration Monitoring via Deep-Learning UWB Radar".
[[paper](https://arxiv.org/pdf/2111.08195.pdf)]
    - Fine-grained respiration detection with RF.
    
* Rui Xiao, Jianwei Liu, Jinsong Han, Kui Ren. </br>
"OneFi: One-Shot Recognition for Unseen Gesture via COTS WiFi".
[[paper](https://dl.acm.org/doi/10.1145/3485730.3485936)]
    - One-shot learning application on WiFi-based HAR.

### NSDI 2021
* Junyang Shi, Mo Sha, and Xi Peng. </br>
"Adapting Wireless Mesh Network Configuration from Simulation to Reality via Deep Learning based Domain Adaptation".
[[paper](http://www.cs.binghamton.edu/~msha/publications/nsdi21.pdf)]
    - Apply domain adaptation on mesh network configuration from simulation to reality.

### ICCV 2019
* Wang F, Zhou S, Panev S, et al. </br>
"Person-in-WiFi: Fine-grained Person Perception using WiFi".
[[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Person-in-WiFi_Fine-Grained_Person_Perception_Using_WiFi_ICCV_2019_paper.pdf)]
    - Feel surprised about the pose estimation performance in this paper, which just leverages 3 antennas WiFi transmitter and receiver. Doubt on its generalization ability.

### ECCV 2020
* Lijie Fan*, Tianhong Li*, Yuan Yuan, Dina Katabi. </br>
"In-Home Daily-Life Captioning Using Radio Signals."
[[paper](http://rf-diary.csail.mit.edu/papers/rfdiary_eccv.pdf)]
    - Feel interesting. Extract features of 3D skeletons and floormap to feed language generation mode. Leveraging paired video to align with RF signal. Also aligning unpaired video by domain adversarial adaptation to take advantage of current video caption dataset. Maybe developing floormap-free model is the next step.

### SenSys 2020
* Chenning Li, Zheng Liu, Yuguang Yao, Zhichao Cao, Mi Zhang, Yunhao Liu. </br>
"Wi-Fi See It All: Generative Adversarial network-augmented Versatile Wi-Fi Imaging."
[[paper](https://cse.msu.edu/~caozc/papers/sensys20-chen.pdf)]
    - Coarse segmentation by 2D-IFFT, fine-grained segmentation by cycle-GAN. Only working on limited occasions.

* Shuya Ding, Zhe Chen, Tianyue Zheng, Jun Luo. </br>
"RF-Net: A Unified Meta-Learning Framework for RF-enabled One-Shot Human Activity Recognition."
[[paper](https://arxiv.org/pdf/1906.00604.pdf)]
    - A novel few-shot learning mnethod applying on WiFi-based HAR. 

### SIGCOMM2020
* Zili Meng, Minhu Wang, Jiasong Bai, Mingwei Xu, Hongzi Mao, Hongxin Hu. </br>
"Interpreting Deep Learning-Based Networking Systems."
[[paper](https://dl.acm.org/doi/pdf/10.1145/3387514.3405859)]
    - Training decision tree and hyper-graph to replace deep learning model to enhance interpretability.

* Kuntai Du, Ahsan Pervaiz, Xin Yuan, Aakanksha Chowdhery, Qizheng Zhang, Henry Hoffmann, Junchen Jiang.</br>
"Server-Driven Video Streaming for Deep Learning Inference."
[[paper](https://dl.acm.org/doi/pdf/10.1145/3387514.3405887)]
    - A dnn-based video stream method towards to server-side high accuracy dnn inference. 

### AAAI2020
* Xiaodong Yang, Yiqiang Chen, Hanchao Yu, Yingwei Zhang, Wang Lu, Ruizhe Sun</br>
"Instance-wise Dynamic Sensor Selection for Human Activity Recognition."
[[paper](https://aaai.org/Papers/AAAI/2020GB/AAAI-YangX.7952.pdf)]

* Zhen Meng, Song Fu, Jie Yan, Hongyuan Liang, Anfu Zhou,Shilin Zhu, Huadong Ma, Jianhua Liu, Ning Yang</br>
"Gait Recognition for Co-existing Multiple People Using Millimeter Wave Sensing"
[[paper](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-MengZ.4055.pdf)]


### NSDI2020
* Kshiteej Mahajan,Arjun Balasubramanian,Arjun Singhvi,Shivaram Venkataraman.</br>
"Themis: Fair and Efficient GPU Cluster Scheduling"
[[paper](https://arxiv.org/pdf/1907.01484.pdf)]

* Francis Y. Yan, Hudson Ayers, Chenzhi Zhu, Sadjad Fouladi, James Hong, Keyi Zhang, Philip Levis, Keith Winstein.</br>
"Learning in situ: a randomized experiment in video streaming."
[[paper](https://arxiv.org/pdf/1906.01113.pdf)]
    - Evaluation on a collected large-scale video dataset.
    
* :star2::star2:Unsoo Ha, Junshan Leng, and Alaa Khaddaj, and Fadel Adib. </br>
"Food and Liquid Sensing in Practical Environments using RFIDs."
[[paper](https://www.usenix.org/system/files/nsdi20-paper-ha.pdf)]
    - Using VAE to generalize to other domains.

### INFOCOM2020
* Shukai Fan, Yongzhi Wu, Chong Han, and Xudong Wang. </br>
"A Structured Bidirectional LSTM Deep Learning Method For 3D Terahertz Indoor Localization".
[[paper](http://www.umji.sjtu.edu.cn/ji_upload/editor/file/20200117/20200117105241_19701.pdf)]

* Yang Li, Zhenhua Han, Quanlu Zhang, Zhenhua Li, Haisheng Tan. </br>
"Automating Cloud Deployment for Deep Learning Inference of Real-time Online Services".
[[paper](http://www.greenorbs.org/people/lzh/papers/[INFOCOM'20]%20AutoDeep.pdf)]

* Jielun Zhang, Fuhao Li, Feng Ye and Hongyu Wu. </br>
"Autonomous Unknown-Application Filtering and Labeling for DL-based Traffic Classifier Update".
[[paper](https://arxiv.org/pdf/2002.06359.pdf)]

* Shaohuai Shi, Qiang Wang, Xiaowen Chu, Bo Li, Yang Qin, Ruihao Liu, Xinxiao Zhao. </br>
"Communication-Efficient Distributed Deep Learning with Merged Gradient Sparsification on GPUs"
[[paper](https://www.comp.hkbu.edu.hk/~chxw/papers/infocom_2020_MGS.pdf)]

* Thaha Mohammed, Carlee Joe-Wong, Rohit Babbar, and Mario Di Francesco. </br>
"Distributed Inference Acceleration with Adaptive DNN Partitioning and Offloading".
[[paper](https://stormvirux.github.io/publication/mjbf-20/mjbf-20.pdf)]

* Xun Wang, Ke Sun, Ting Zhao, Wei Wang, and Qing Gu. </br>
"Dynamic Speed Warping: Similarity-Based One-shot Learning for Device-free Gesture Signals"
[[paper](https://samsonsjarkal.github.io/KeSun/files/infocom20_dsw.pdf)]

* Chunhui Duan, Wenlei Shi, Fan Dang and Xuan Ding. </br>
"Enabling RFID-Based Tracking for Multi-Objects with Visual Aids: A Calibration-Free Solution"
[[paper](https://dang.fan/publication/infocom20-visual-aids-rfid-tracking/infocom20-visual-aids-rfid-tracking.pdf)]

* Tianxiang Tan and Guohong Cao. </br>
"FastVA: Deep Learning Video Analytics Through Edge Processing and NPU in Mobile"
[[paper](https://arxiv.org/pdf/2001.04049.pdf)]

* Shibo Wang, Shusen Yang, Cong Zhao. </br>
"SurveilEdge: Real-time Video Query based on Collaborative Cloud-Edge Deep Learning"
[[paper](https://arxiv.org/pdf/2001.01043.pdf)]

* Yanwen Wang, Jiaxing Shen, Yuanqing Zheng. </br>
"Push the Limit of Acoustic Gesture Recognitio".
[[paper](https://www4.comp.polyu.edu.hk/~csyqzheng/papers/RobuCIR-INFOCOM20.pdf)]

* Francesco Devoti , Vincenzo Sciancalepore , Ilario Filippini , Xavier Costa-Perez.</br>
"PASID: Exploiting Indoor mmWave Deployments for Passive Intrusion Detection".
[[paper](http://www.sciancalepore.info/files/infocom2020_dsfc.pdf)]

* Shuang Jiang, Zhiyao Ma, Xiao ZengF, Chenren Xu, Mi ZhangF, Chen Zhang, Yunxin Liu. </br>
"SCYLLA: QoE-aware Continuous Mobile Vision with FPGA-based Dynamic Deep Neural Network Reconfiguration".
[[paper](http://soar.group/pubs/Scylla.INFOCOM20.pdf)]

* Xin Yang, Jian Liu, Yingying Chen, Xiaonan Guo, Yucheng Xie. </br>
"MU-ID: Multi-user Identification Through Gaits Using Millimeter Wave Radios"
[[paper](https://web.eecs.utk.edu/~jliu/publications/yang2020muid.pdf)]

* Chenshu Wu, Feng Zhang, Beibei Wang, and K. J. Ray Liu. </br>
"mmTrack: Passive Multi-Person Localization Using Commodity Millimeter Wave Radio"
[[paper](http://cswu.me/papers/infocom20_mmtrack_paper.pdf)]

* Xiaoxi Zhang, Jianyu Wang, Gauri Joshi, Carlee Joe-Wong. </br>
"Machine Learning on Volatile Instances"
[[paper](https://arxiv.org/pdf/2003.05649.pdf)]

* Yongyong Wei, Rong Zheng. </br>
"Informative Path Planning for Mobile Sensing with Reinforcement Learning".
[[paper](https://arxiv.org/pdf/2002.07890.pdf)]

### MobiCom2020
* :star2:**DLoc:**:star2: R. Ayyalasomayajula, A. Arun, C. Wu, S. Sharma, A. Sethi, D. Vasisht, D. Bharadia. </br>
"Deep Learning based Wireless Localization for Indoor Navigation".
[[paper](http://acsweb.ucsd.edu/~sayyalas/assets/files/DLoc_paper.pdf)]
    - Correct ToF via encoder-decoder network.

* W. Jiang, H. Xue, C. Miao, S. Wang, S. Lin, C. Tian, S. Murali, H. Hu, Z. Sun, L. Su. </br>
"3D Human Pose Construction Using WiFi".
[[paper](https://cse.buffalo.edu/~lusu/papers/MobiCom2020.pdf)]

* Jin Huang, Colin Samplawski, Deepak Ganesan, Benjamin Marlin, Heesung Kwon. </br>
"CLIO: enabling automatic compilation of deep learning pipelines across IoT and cloud."
[[paper](https://dl.acm.org/doi/10.1145/3372224.3419215)][[code](https://github.com/jinhuang01/CLIO)]
    - A novel model compilation framework that provides a continuum of options for deep learning models to be partitioned across a low-power IoT device and the cloud.
    
* Juheon Yi, Sunghyun Choi, Youngki Lee.</br>
"EagleEye: Wearable Camera-based Person Identification in Crowded Urban Spaces."
[[paper](https://juheonyi.github.io/files/EagleEye.pdf)]
    - Identify Low-Resolution (LR) faces and optimize complex multi-DNN face identification pipeline execution latency.
    
* Hanbin Zhang, Gabriel Guo, Chen Song, Chenhan Xu, Kevin Cheung, Jasleen Alexis.</br>
"PDLens: Smartphone Knows Drug Efectiveness among Parkinson’s via Daily-Life Activity Fusion."
[[paper](https://cse.buffalo.edu/~wenyaoxu/papers/conference/xu-mobicom2020a.pdf)]
    - A deep learning solution on monitor Parkinson.
    
* Wei Yang Bryan Lim, Nguyen Cong Luong, Dinh Thai Hoang, Yutao Jiao, Ying-Chang Liang, Qiang Yang, Dusit Niyato and Chunyan Miao. </br>
"Billion-Scale Federated Learning on Mobile Clients: A Submodel Design with Tunable Privacy."
[[paper](http://www.cs.sjtu.edu.cn/~fwu/res/Paper/NWTHJLWC20MobiCom.pdf)]
    - Design of submodel in federated learning.
    
* Unsoo Ha, Salah Assana, Fadel Adib. </br>
"Contactless Seismocardiography via Deep Learning Radars."
[[paper](http://www.mit.edu/~fadel/papers/RFSCG-paper.pdf)]
    - A deep learning solution of sensing seismocardiogram with mmwave.

### IJCAI2019
* **SparseSense:** Alireza Abedin, S. Hamid Rezatofighi, Qinfeng Shi, Damith C. Ranasinghe.</br>
"SparseSense: Human Activity Recognition from Highly Sparse Sensor Data-streams Using Set-based Neural Networks".
 [[paper](https://arxiv.org/pdf/1906.02399v1.pdf)]
    - A deep learning solution for wearable sensors missing data.
  
* **AttnSense:** Haojie Ma, Wenzhong Li, Xiao Zhang, Songcheng Gao and Sanglu Lu. </br>
"AttnSense: Multi-level Attention Mechanism For Multimodal Human Activity Recognition".
  [[paper](https://www.ijcai.org/proceedings/2019/0431.pdf)]
  
* Haoze Wu, Jiawei Liu, Zheng-Jun Zha, Zhenzhong Chen, Xiaoyan Sun.</br>
"Mutually Reinforced Spatio-Temporal Convolutional Tube for Human Action Recognition".
  [[paper](https://www.ijcai.org/proceedings/2019/0136.pdf)]
  
* Katia Bourahmoune ∗, Toshiyuki Amagasa</br>
"AI-powered Posture Training: Application of Machine Learning in Sitting Posture Recognition Using the LifeChair Smart Cushion".
[[paper](https://www.ijcai.org/proceedings/2019/0805.pdf)]

* Kazuhiko Shinoda , Masahiko Yoshii , Hayato Yamaguchi and Hirotaka Kaji</br>
"Daytime Sleepiness Level Prediction Using Respiratory Information".
[[paper](https://www.ijcai.org/proceedings/2019/0827.pdf)]
  
### AAAI2019
* Hangwei Qian, Sinno Jialin Pan, Chunyan Miao. </br>
"Distribution-based Semi-Supervised Learning for Activity Recognition".
[[paper](http://hangwei12358.github.io/Publications/AAAI-QianH.2680.pdf)]

* **LabelForest:** Yuchao Ma and Hassan Ghasemzadeh.</br>
"LabelForest: Non-Parametric Semi-Supervised Learning for Activity Recognition".
[[paper](http://epsl.eecs.wsu.edu/wp-content/uploads/2015/03/label-forest.pdf)]

* Karan Aggarwal, Shafiq Joty, Luis Fernandez-Luque, Jaideep Srivastava1.</br>
"Adversarial Unsupervised Representation Learning for Activity Time-Series".
[[paper](https://arxiv.org/pdf/1811.06847.pdf)]

* **PhoneMD:** Patrick Schwab , Walter Karlen.</br>
"PhoneMD: Learning to Diagnose Parkinson's Disease from Smartphone Data".
[[paper](https://arxiv.org/pdf/1810.01485.pdf)]

* Hao Wang, Chengzhi Mao, Hao He, Mingmin Zhao, Tommi S. Jaakkola, and Dina Katabi</br>
" Bidirectional Inference Networks with Application to Health Profiling"
[[paper](https://arxiv.org/pdf/1902.02037.pdf)]

### MobiCom2019
* Hanbin Zhang , Chenhan Xu , Huining Li , Aditya Singh Rathore , Chen Song , Zhisheng Yan , Dongmei Li , Feng Lin , Kun Wang , Wenyao Xu.</br>
"PDVocal: Towards Privacy-preserving Parkinson’s Disease Detection using Non-speech Body Sounds"
[[paper](https://dl.acm.org/citation.cfm?doid=3300061.3300125)]

* **IntuWition:** Diana Zhang, Jingxian Wang, Junsu Jang. </br>
"On the Feasibility of Wi-Fi Based Material Sensing"
[[paper](http://www.swarunkumar.com/papers/intuwition-mobicom2019.pdf)]
    - Localization and sensing.

* **vrAIn:** J. A. Ayala-Romero, A. Garcia-Saavedra, M. Gramaglia, X. Costa-Perez, A. Banchs, J. J. Alcaraz. </br>
"vrAIn: A Deep Learning Approach Tailoring Computing and Radio Resources in Virtualized RANs"
[[paper](https://agsaaved.github.io/files/papers/2019_ayala_mobicom_vrain.pdf)]

* 	Anfu Zhou, Huanhuan Zhang, Guangyuan Su, Leilei Wu, Ruoxuan Ma, Zhen Meng, Xinyu Zhang, Xiufeng Xie, Huadong Ma, Xiaojiang Chen</br>
"Optimizing Mobile Video Telephony Using Deep Imitation Learning" 

* 	Taegyeong Lee, Zhiqi Lin, Saumay Pushp, Caihua Li, Yunxin Liu, Youngki Lee, Fengyuan Xu, Chenren Xu, Lintao Zhang, Junehwa Song.</br>
"Occlumency: Privacy-preserving Remote Deep-learning Inference Using SGX"

* 	Wenguang Mao, Mei Wang, Wei Sun, Lili Qiu, Swadhin Pradhan, Yi-Chao Chen </br>
"RNN-Based Room Scale Hand Motion Tracking"
[[paper](http://www.cs.sjtu.edu.cn/~yichao/pmwiki/assets/publications/mobicom19_mao.pdf)]
    - Generating profile with MUSIC and leveaging RNN to do tracking.

* Luyang Liu, Hongyu Li, Marco Gruteser</br>
"Edge Assisted Real-time Object Detection for Mobile Augmented Reality"
[[paper](http://www.winlab.rutgers.edu/~gruteser/papers/mobicom19_augmented_reality.pdf)]

* Belal Korany, Chitra R. Karanam, Hong Cai, Yasamin Mostofi</br>
XModal-ID: Using WiFi for Through-Wall Person Identification from Candidate Video Footage
[[paper](https://www.ece.ucsb.edu/~ymostofi/papers/MobiCom19_KoranyKaranamCaiMostofi.pdf)]

* Arjun Bakshi, Yifan Mao, Kannan Srinivasan, Srinivasan Parthasarathy</br>
Fast and Efficient Cross Band Channel Prediction Using Machine Learning.

* **FLUID:** Sangeun Oh, Ahyeon Kim, Sunjae Lee, Kilho Lee, Dae R. Jeong, Steven Y. Ko, Insik Shin.</br>
"FLUID: Flexible User Interface Distribution for Ubiquitous Multi-device Interaction"
[[paper](https://cps.kaist.ac.kr/papers/mobicom19-fluid.pdf)]

* Xiufeng Xie, Kyu-Han Kim.</br>
"Source Compression with Bounded DNN Perception Loss for IoT Edge Computer Vision"

* **MobiSR** Royson Lee, Stylianos I. Venieris, Lukasz Dudziak, Sourav Bhattacharya, Nicholas D. Lane.</br>
"MobiSR: Efficient On-Device Super-Resolution through Heterogeneous Mobile Processors"
[[paper](https://steliosven10.github.io/papers/[2019]_mobicom_mobisr_efficient_on_device_super_resolution_through_heterogeneous_mobile_processors.pdf)]



### INFOCOM2019
* Jia Liu,Xingyu Chen,Shigang Chen,Xiulong Liu,Yanyan Wang,Lijun Chen.</br>
"TagSheet: Sleeping Posture Recognition with an Unobtrusive Passive Tag Matrix"
[[paper](https://ieeexplore.ieee.org/document/8737599)]

* Ran He ; Jin Cao ; Lisa Zhang ; Denny Lee. </br>
"Statistical Enrichment Models for Activity Inference from Imprecise Location Data"
[[paper](https://ieeexplore.ieee.org/document/8737535)]

* Chuyu Wang ; Lei Xie ; Keyan Zhang ; Wei Wang ; Yanling Bu ; Sanglu Lu</br>
"Spin-Antenna: 3D Motion Tracking for Tag Array Labeled Objects via Spinning Antenna"
[[paper](https://ieeexplore.ieee.org/document/8737372)]

* Shuochao Yao, Yiran Zhao, Huajie Shao, Dongxin Liu, Shengzhong Liu, Yifan Hao, Ailing Piao, Shaohan Hu, Lu Su, Tarek Abdelzaher.</br>
"SADeepSense: Self-Attention Deep Learning Framework for Heterogeneous On-Device Sensors in Internet of Things Applications"
[[paper](https://cse.buffalo.edu/~lusu/papers/INFOCOM2019Shuochao.pdf)]

* Pengfei Liu ; Panlong Yang ; Wen-Zhan Song ; Yubo Yan ; Xiang-Yang Li </br>
"Real-time Identification of Rogue WiFi Connections Using Environment-Independent Physical Features".
[[paper](https://ieeexplore_ieee.xilesou.top/abstract/document/8737455)]

### MobiSys2019
* Yang Liu, Zhenjiang Li,Zhidan Liu, Kaishun Wu </br>
"Real-time Arm Skeleton Tracking and Gesture Inference Tolerant to Missing Wearable Sensors".
[[paper](http://www.cs.cityu.edu.hk/~zhenjili/2019-MobiSys-ArmTroi.pdf)]

* Hua Huang, Hongkai Chen, Shan Lin <br>
"MagTrack: Enabling Safe Driving Monitoring with Wearable Magnetics"
[[paper](http://www.ece.sunysb.edu/~slin/Publications/mobisys.pdf)]

* Tai, Tzu-Chun, Kate Ching-Ju Lin, and Yu-Chee Tseng.</br>
"Toward Reliable Localization by Unequal AoA Tracking"
[[paper](https://dl.acm.org/citation.cfm?id=3326103)]

* Siddhant Prakash, Alireza Bahremand, Linda D. Nguyen, and Robert LiKamWa </br>
"GLEAM: An illumination estimation framework for real-time photorealistic augmented reality on mobile devices"
[[paper](https://meteor.ame.asu.edu/publications/mobisys19prakash-gleam.pdf)]

* Jian Liu; Cong Shi; Yingying Chen; Hongbo Liu; Marco Gruteser </br>
"CardioCam: Leveraging Camera on Mobile Devices to Verify Users While Their Heart is Pumping"
[[paper](http://winlab.rutgers.edu/~cs1421/paper/CardioCam.pdf)]

* Eric Whitmire, Farshid Salemi Parizi, and Shwetak Patel </br>
"Aura: Inside-out Electromagnetic Controller Tracking" 
[[paper](https://ubicomplab.cs.washington.edu/pdfs/aura.pdf)]

* Yue Zheng, Yi Zhang1, Kun Qian, Guidong Zhang, Yunhao Liu, Chenshu Wu, Zheng Yang </br>
"Zero-Effort Cross-Domain Gesture Recognition with Wi-Fi"
[[paper](https://www.kunqian.info/files/MobiSys19_Widar3.0_paper.pdf)]

### SenSys2019
* Huatao Xu, Dong Wang, Run  Zhao, Qian  Zhang. </br>
"FaHo: deep learning enhanced holographic localization for RFID tags"
[[paper](https://dl.acm.org/doi/abs/10.1145/3356250.3360035)]

* Yinggang Yu, Dong  Wang, Run  Zhao, Qian  Zhang. </br>
"RFID based real-time recognition of ongoing gesture with adversarial learning"
[[paper](https://dl.acm.org/doi/abs/10.1145/3356250.3360045)]
 
* Sinh HUYNH, Rajesh Krishna BALAN, JeongGil KO, Youngki LEE. </br>
"VitaMon: measuring heart rate variability using smartphone front camera"
[[paper](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=5936&context=sis_research)]

* Jeya Vikranth Jeyakumar, Liangzhen  Lai, Naveen  Suda, Mani B. Srivastava. </br>
"SenseHAR: a robust virtual activity sensor for smartphones and wearables"
[[paper](https://dl.acm.org/doi/abs/10.1145/3356250.3360032)]

* Taesik Gong, Yeonsu  Kim, Jinwoo  Shin, Sung-Ju  Lee. </br>
"MetaSense: few-shot adaptation to untrained conditions in deep mobile sensing"
[[paper](http://alinlab.kaist.ac.kr/resource/SenSys19_MetaSense.pdf)]
    - An application of MAML.


### CoNext2019
* Serkut Ayvaşık, H. Murat Gürsu, Wolfgang Kellerer. </br>
"Veni Vidi Dixi: reliable wireless communication with depth images".
[[paper](https://arxiv.org/pdf/1912.01879.pdf)]

### IWQoS2019
* Fangxin Wang, Jiangchuan Liu, Wei Gong. </br>
"WiCAR: wifi-based in-car activity recognition with multi-adversarial domain adaptation".
[[paper](https://dl.acm.org/citation.cfm?doid=3326285.3329054)]
    - An in-car environment application of DANN.

### SIGCOMM 2018
*	Mingmin Zhao, Yonglong Tian, Hang Zhao, Mohammad Abu Alsheikh, Tianhong Li, Rumen Hristov, Zachary Kabelac, Dina Katabi, Antonio Torralba. </br>
:star2::star2:"RF-Based 3D Skeletons".
[[paper](https://dl.acm.org/citation.cfm?doid=3230543.3230579)]
    - Video labeling and RF train.

* Li Chen, Justinas Lingys, Kai Chen, Feng Liu. </br>
"AuTO: Scaling Deep Reinforcement Learning for Datacenter-Scale Automatic Traffic Optimization"
[[paper](https://conferences.sigcomm.org/events/apnet2018/papers/auto.pdf)]

* Junchen Jiang, Ganesh Ananthanarayanan, Peter Bodik, Siddhartha Sen, Ion Stoica. </br>
"Chameleon: Scalable Adaptation of Video Analytics"
[[paper](https://people.cs.uchicago.edu/~junchenj/docs/Chameleon_SIGCOMM_CameraReady_faceblurred.pdf)]
    - A simple strategy of choose inference model size.

### MobiCom2018
* Wenjun Jiang, Chenglin Miao, Fenglong Ma, Shuochao Yao, Yaqing Wang, Ye Yuan, Hongfei Xue, Chen Song, Xin Ma, Dimitrios Koutsonikolas, Wenyao Xu, Lu Su. </br>
:star2::star2:"Towards Environment Independent Device Free Human Activity Recognition".
[[paper](https://dl.acm.org/citation.cfm?doid=3241539.3241548)]
    - An application of DANN on multiple scenes. Three extra constraints were proposed.

* Zhang J, Tang Z, Li M, et al.</br>
"CrossSense: Towards Cross-Site and Large-Scale WiFi Sensing".
[[paper](https://eprints.lancs.ac.uk/id/eprint/126425/7/paper.pdf)]
    - Multiple ML models ensemble learning.

### MobiSys2018
* Raghav H. Venkatnarayan, Griffin Page, Muhammad Shahzad. </br>
"Multi-User Activity Recognition Using WiFi".
[[paper](https://people.engr.ncsu.edu/mshahza/publications/Hampapur2018Multi.pdf)]

### SenSys2018
* Salma Elmalaki, Huey-Ru Tsai, Mani Srivastava. </br>
"Sentio: Driver-in-the-Loop Forward Collision Warning UsingMultisample Reinforcement Learning"
[[paper](https://dl.acm.org/doi/pdf/10.1145/3274783.3274843)]

* Z Jia, X Lyu, W Zhang, RP Martin, RE Howard. </br>
"Continuous Low-Power Ammonia Monitoring Using Long Short-Term Memory Neural Networks"
[[paper](http://www.winlab.rutgers.edu/~wuyang/papers/sensys2018.pdf)]

* Zicheng Chi , Yao Yao , Tiantian Xie , Xin Liu , Zhichuan Huang , Wei Wang , Ting Zhu. </br>
"EAR: Exploiting Uncontrollable Ambient RF Signals in Heterogeneous Networks for Gesture Recognition"
[[paper](https://www.csee.umbc.edu/~zt/Papers/EAR.pdf)]

### ICML2017
*	Mingmin Zhao, Shichao Yue, Dina Katabi, Tommi S. Jaakkola, Matt T. Bianchi. </br>
"Learning Sleep Stages from Radio Signals: A Conditional Adversarial Architecture".
[[paper](http://proceedings.mlr.press/v70/zhao17d/zhao17d.pdf)]

## Journal

* **Review** Henry Friday Nweke, Ying Wah Teh,∗, Mohammed Ali Al-garadi , Uzoma Rita Alo </br>
"Deep learning algorithms for human activity recognition using mobile and wearable sensor networks: State of the art and research
challenges"
[[paper](https://pdf.sciencedirectassets.com/271506/1-s2.0-S0957417418X00098/1-s2.0-S0957417418302136/main.pdf?X-Amz-Security-Token=AgoJb3JpZ2luX2VjEKP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQC19XJ%2BF3DVhCrICYby2LcRwUfZhI69aB9gM3HIovvPbAIhALs7rF1vZ6hoQtgTUxoZWEDeVS8gQKQBZmGmUkqZF09dKuMDCIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQAhoMMDU5MDAzNTQ2ODY1IgzMSDAtOs%2BMRtTmDAgqtwO4PW8dDErFI1i4uLLgkh1mPGiVdHgPMVmLKU3P0MOqQ8WnWdnmVY7EDU3zqIaEUHsi%2Fer9xLH8xDJmMLHkjMmGVK3vCOWHb0pNtlmiyt1la8NeFsorUCvHqinteUiQIPGxeSkO0Wwoy1vySBdA41%2F9vji6oJlN4PV0EZ3Oaaip2kmfLfJZrhLzAIBdJKwys53HV8IhqYWX771HovK4gJisoZ%2BWZeTJn2fwMLxVQiaJq2ok8s3HybZDdWexO1ltx9dFYSi%2FnFj6d%2BL4OJEw5uWGY%2BbmHiVpVSZN8N8TLkf%2FUSPChggzdcNvvFoLuNYxZjhWERqzn3EkDG4QUfzX3T%2BDTGtctMZkZe1KZATzUKVXyHDfK4wnbeKb98wEEnwx7GSVvrZaMkMrk%2FydL9wK7%2FAmnkFTFjnl7rdoZQJKhd4HxAupLzZJ94ZM9peroVL2DgBZs1oBXynnU3ipv%2Bh%2BFq0wOKEtix3RMv7Fe4h29lwPzCARWiJaDEkmwWObAB2WgC0qON6J0mxqbDxE17qSLqrFPscD4pJWNFRBZEeWYkTAb9%2BXFzVyfGA1wI0OIZiYKSu9h7cziDDjMPbL8ewFOrMBNs1jwGutZDEmoj%2B%2FRDpXzFsVfjNH4Q2m%2Fsq%2BIYu7F8H3Kf89EQ8Klesa5E9pj2GoZsq%2BdOitPCV2o0TjFPzglQWiFquKWbAiH8eSCgpTZlokqKhyXCUMx4didnGJOvrXPJ8%2BT3SRir7myu9V7ixl%2F08cbsw8Rfj5lwylDziQRvQiRULi3MFTFmTmM8zGgrv2YI6uyMGtGcw5HAVopcmURmd7XKtpRt1L10j31%2BG7Sk8Ep%2Fw%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20191008T120049Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYU56PWDML%2F20191008%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=848eaaf64dffdf9285d4cc12d383b9b0dc1d778fae2edc4f4925404e666b3c57&hash=e6baaef6dd8fbf2e2647b2bc42845c68f57a3a91d498a72dd26afd30a22a6759&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0957417418302136&tid=spdf-4f634a5e-4b8b-4788-acde-b4307ea8d81b&sid=59e2652033a776491038013882afbfe4f4cbgxrqa&type=client)]

## arxiv
