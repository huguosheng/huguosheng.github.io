---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: markdown
    id: research
    content:
      title: Research
      text: |
        <div align="justify">


        Guosheng Hu's research mission focuses on reducing AI's carbon footprint via model acceleration techiques. He leads numerous publications and commercially successful products on adaptively accelerating various computer vision models on diverse hardwares (Nvidia’s A100, V100, Jetson Orin, Intel CPUs, Ambaralla Chips, etc).
        
        He has  broad and in-depth knowledge in numerous computer vision and machine learning tasks. His work has been published in prestigious journals and conferences [[Google Scholar](https://scholar.google.co.uk/citations?user=frCHDW4AAAAJ&hl=en)].


        Very recently, he is interested into accelerating the training and inference of foundation models including large language models, large multimodal models, etc.

        ---

        ###  Model Acceleration


        Neural Architecture Search and AutoML, Knowledge Distillation, Quantisation and Pruning

        <details style="border: none;">
        <summary>Click to expand paper list</summary>
        
          Li, Yonggang, Guosheng Hu, Yongtao Wang, Timothy Hospedales, Neil M. Robertson, and Yongxin Yang. "Differentiable automatic data augmentation." ECCV,  2020.  [[code]](https://github.com/VDIGPKU/DADA)

          Liang, Tingting, Yongtao Wang, Zhi Tang, Guosheng Hu, and Haibin Ling. "Opanas: One-shot path aggregation network architecture search for object detection." CVPR, 2021.  [[code]](https://github.com/VDIGPKU/OPANAS)

          Fan, Zhenkun, Guosheng Hu, Xin Sun, Gaige Wang, Junyu Dong, and Chi Su. "Self-attention neural architecture search for semantic image segmentation." Knowledge-Based Systems 239 (2022): 107968.

          Jin, Yufeng, Guosheng Hu, Haonan Chen, Duoqian Miao, Liang Hu, and Cairong Zhao. "Cross-modal distillation for speaker recognition." AAAI, 2023.

          Sun, Tianli, Haonan Chen, Guosheng Hu, and Cairong Zhao. "Explainability-Based Knowledge Distillation." Available at SSRN 4460609.

          Chen, Hao, Ran Tao, Han Zhang, Yidong Wang, Wei Ye, Jindong Wang, Guosheng Hu, and Marios Savvides. "Conv-adapter: Exploring parameter efficient transfer learning for convnets." CVPR Workshop Prompting in Vision, 2024. [code coming soon]
        </details>

        ###  Computer Vision

        (Video) Object Detection, Semantic Segmentation, Face Analysis (Recognition, Liveness/Deepfake, Expression), Skeleton- and RGB-based Action Recognition, Foundation Model Applications

        <details><summary>Click to expand paper list</summary>

          #### Detection, Classification and Segmentation


          Sun, Guanxiong, Yang Hua, Guosheng Hu, and Neil Robertson. "Efficient one-stage video object detection by exploiting temporal consistency." ECCV, 2022. [[slides]](https://docs.google.com/presentation/d/e/2PACX-1vRFKveZAUvAawzc985TUERJCuLpxC7GdHec5ZSHt9Tz2kNXdEMJqHzPpJVQ622Kuw/pub?start=false&loop=false&delayms=3000&slide=id.p1) [[code]](https://github.com/guanxiongsun/EOVOD)

          Sun, Guanxiong, Yang Hua, Guosheng Hu, and Neil Robertson. "Tdvit: Temporal dilated video transformer for dense video tasks." In European Conference on Computer Vision, pp. 285-301. Cham: Springer Nature Switzerland, 2022. [[slides]](https://docs.google.com/presentation/d/e/2PACX-1vR2KGWIsEuQTPglB9FgugW8e_OZHPbvkgZGVGqncRizO2YJ2R8NohEG_nLAdkTBHQ/pub?start=false&loop=false&delayms=3000&slide=id.p1) [[code]](https://github.com/guanxiongsun/vfe.pytorch)

          Sun, Guanxiong, Yang Hua, Guosheng Hu, and Neil Robertson. "Mamba: Multi-level aggregation via memory bank for video object detection." AAAI. 2021. [[slides]](https://docs.google.com/presentation/d/e/2PACX-1vS2u9aWhD3P2qCRoQ0oCMjO6Pz5ncwff9S8oQyhDsRvEjCotvKb6ffgFIoAFIP0wQ/pub?start=false&loop=false&delayms=3000&slide=id.p1) [[code]](https://github.com/guanxiongsun/vfe.pytorch)

          Liang, Tingting, Yongtao Wang, Zhi Tang, Guosheng Hu, and Haibin Ling. "Opanas: One-shot path aggregation network architecture search for object detection." CVPR, 2021.  [[code]](https://github.com/VDIGPKU/OPANAS)

          Chen, Zhiyang, Yousong Zhu, Chaoyang Zhao, Guosheng Hu, Wei Zeng, Jinqiao Wang, and Ming Tang. "Dpt: Deformable patch-based transformer for visual recognition." In Proceedings of the 29th ACM International Conference on Multimedia, pp. 2899-2907. 2021. [[code]](https://github.com/CASIA-IVA-Lab/DPT)

          Lu, Bingxu, Qinghua Hu, Yu Wang, and Guosheng Hu. "Rcanet: Row-column attention network for semantic segmentation." In ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 2604-2608. IEEE, 2022.

          Fan, Zhenkun, Guosheng Hu, Xin Sun, Gaige Wang, Junyu Dong, and Chi Su. "Self-attention neural architecture search for semantic image segmentation." Knowledge-Based Systems 239 (2022): 107968.


          #### Face 

          Hu, Guosheng, Yongxin Yang, Dong Yi, Josef Kittler, William Christmas, Stan Z. Li, and Timothy Hospedales. "When face recognition meets with deep learning: an evaluation of convolutional neural networks for face recognition." ICCV workshops, 2015. 

          Hu, Guosheng, Xiaojiang Peng, Yongxin Yang, Timothy M. Hospedales, and Jakob Verbeek. "Frankenstein: Learning deep face representations using small data." IEEE Transactions on Image Processing 27, no. 1 (2017): 293-303.

          Hu, Guosheng, Yang Hua, Yang Yuan, Zhihong Zhang, Zheng Lu, Sankha S. Mukherjee, Timothy M. Hospedales, Neil M. Robertson, and Yongxin Yang. "Attribute-enhanced face recognition with neural tensor fusion networks." ICCV, 2017.

          Mu, Guodong, Di Huang, Guosheng Hu, Jia Sun, and Yunhong Wang. "Led3d: A lightweight and efficient deep approach to recognizing low-quality 3d faces." CVPR, 2019.

          Hu, Guosheng, Fei Yan, Chi-Ho Chan, Weihong Deng, William Christmas, Josef Kittler, and Neil M. Robertson. "Face recognition using a unified 3D morphable model." ECCV, 2016.

          Liu, Zhiwei, Xiangyu Zhu, Guosheng Hu, Haiyun Guo, Ming Tang, Zhen Lei, Neil M. Robertson, and Jinqiao Wang. "Semantic alignment: Finding semantically consistent ground-truth for facial landmark detection." CVPR, 2019.

          Chen, Haonan, Guosheng Hu, Zhen Lei, Yaowu Chen, Neil M. Robertson, and Stan Z. Li. "Attention-based two-stream convolutional networks for face spoofing detection." IEEE Transactions on Information Forensics and Security 15 (2019): 578-593.

          Zhao, Cairong, Chutian Wang, Guosheng Hu, Haonan Chen, Chun Liu, and Jinhui Tang. "ISTVT: interpretable spatial-temporal video transformer for deepfake detection." IEEE Transactions on Information Forensics and Security 18 (2023): 1335-1348.

          Wen, Xin, Biying Li, Haiyun Guo, Zhiwei Liu, Guosheng Hu, Ming Tang, and Jinqiao Wang. "Adaptive variance based label distribution learning for facial age estimation." ECCV, 2020.

          Hu, Guosheng, Li Liu, Yang Yuan, Zehao Yu, Yang Hua, Zhihong Zhang, Fumin Shen et al. "Deep multi-task learning to recognise subtle facial expressions of mental states." ECCV, 2018.


          #### Foundation Model Applications
          
          Wang, Tianfu, Guosheng Hu, and Hongguang Wang. "Object Pose Estimation via the Aggregation of Diffusion Features." CVPR, 2024. [[code]](https://github.com/Tianfu18/diff-feats-pose)

          Li, Wen, Yuyang Yang, Shangshu Yu, Guosheng Hu, Chenglu Wen, Ming Cheng, Cheng Wang, "DiffLoc: Diffusion Model for Outdoor LiDAR Localization." CVPR, 2024.

          Song, Zifan, Guosheng Hu, and Cairong Zhao. "Diverse Person: Customize Your Own Dataset for Text-Based Person Search." AAAI, 2024.
          
        </details>

        ###  Machine Learning

        Multimodal Learning, Metric Learning, Domain Adaptation, Noisy Label, etc.

        <details>
        <summary>Click to expand paper list</summary>

          #### Multimodal Learning
          
          Jin, Yufeng, Guosheng Hu, Haonan Chen, Duoqian Miao, Liang Hu, and Cairong Zhao. "Cross-modal distillation for speaker recognition." AAAI, 2023.

          Wang, Hao, Shengda Luo, Guosheng Hu, and Jianguo Zhang. "Gradient-Guided Modality Decoupling for Missing-Modality Robustness." AAAI, 2024.

          #### Metric Learning
          
          Wang, Xinshao, Yang Hua, Elyor Kodirov, Guosheng Hu, Romain Garnier, and Neil M. Robertson. "Ranked list loss for deep metric learning." CVPR, 2019.

          Wang, Xinshao, Yang Hua, Elyor Kodirov, Guosheng Hu, and Neil M. Robertson. "Deep metric learning by online soft mining and class-aware attention." AAAI. 2019.

          Jiang, Xiruo, Sheng Liu, Xili Dai, Guosheng Hu, Xingguo Huang, Yazhou Yao, Guo-Sen Xie, and Ling Shao. "Deep metric learning based on meta-mining strategy with semiglobal information." IEEE Transactions on Neural Networks and Learning Systems (2022).

          #### Noisy Label
          
          Wang, Zhen, Guosheng Hu, and Qinghua Hu. "Training noise-robust deep neural networks via meta-learning." CVPR, 2020.

          Sun, Zeren, Xian-Sheng Hua, Yazhou Yao, Xiu-Shen Wei, Guosheng Hu, and Jian Zhang. "Crssc: salvage reusable samples from noisy data for robust learning." In Proceedings of the 28th ACM international conference on multimedia, pp. 92-101. 2020.


          #### Domain Adaptation

          Gao, Jian, Yang Hua, Guosheng Hu, Chi Wang, and Neil M. Robertson. "Discrepancy-guided domain-adaptive data augmentation." IEEE Transactions on Neural Networks and Learning Systems 34, no. 8 (2021): 5064-5075.

          Gao, Jian, Yang Hua, Guosheng Hu, Chi Wang, and Neil M. Robertson. "Reducing distributional uncertainty by mutual information maximisation and transferable feature learning." ECCV, 2020.

          #### Others

          Song, Zifan, Xiao Gong, Guosheng Hu, and Cairong Zhao. "Deep perturbation learning: enhancing the network performance via image perturbations." ICML, 2023.

          Wang, Tianyang, Xingjian Li, Pengkun Yang, Guosheng Hu, Xiangrui Zeng, Siyu Huang, Cheng-Zhong Xu, and Min Xu. "Boosting active learning via improving test performance." AAAI, 2022.

          Mai, Zhijun, Guosheng Hu, Dexiong Chen, Fumin Shen, and Heng Tao Shen. "Metamixup: Learning adaptive interpolation policy of mixup with metalearning." IEEE transactions on neural networks and learning systems 33, no. 7 (2021): 3050-3064.

          Gong, Xiao, Guosheng Hu, Timothy Hospedales, and Yongxin Yang. "Adversarial robustness of open-set recognition: face recognition and person re-identification." ECCV Workshop, 2020.

          Hu, Guosheng, Li Liu, Yang Yuan, Zehao Yu, Yang Hua, Zhihong Zhang, Fumin Shen et al. "Deep multi-task learning to recognise subtle facial expressions of mental states." ECCV, 2018.

          Hu, Guosheng, Yuxin Hu, Kai Yang, Zehao Yu, Flood Sung, Zhihong Zhang, Fei Xie et al. "Deep stock representation learning: From candlestick charts to investment decisions." In 2018 IEEE international conference on acoustics, speech and signal processing (ICASSP), pp. 2706-2710. IEEE, 2018.

          Sun, Tianli, Haonan Chen, Guosheng Hu, Lianghua He, and Cairong Zhao. "Explainability of Speech Recognition Transformers via Gradient-based Attention Visualization." IEEE Transactions on Multimedia (2023).

        </details>
        
        <script>
          window.onload = function() {
            var paperList = document.getElementById('paperList');
            paperList.style.border = 'none';
          };
        </script>
 

        </div>
    design:
      columns: '2'
      css_class: fullscreen

  - block: markdown
    id: supervision
    content:
      title: Supervision
      text: |-
        <div align="justify">


        "Education is not the filling of a pail, but the lighting of a fire." - William Butler Yeats
        
        &nbsp;

        I supervise Oosto sponsored PhD students: 

        [Hao Chen](https://scholar.google.com/citations?user=tktqkhwAAAAJ&hl=en), Carnegie Mellon University (2022 - ) 

        [Uzair Ahmed](https://scholar.google.com/citations?user=lw_3tBIAAAAJ&hl=en), Carnegie Mellon University (2022 -) 

        [Ran Tao](https://scholar.google.com/citations?user=7xW2y6EAAAAJ&hl=en), Carnegie Mellon University (2022 -) 

        [Guanxiong Sun](https://scholar.google.com/citations?user=vLk3IzoAAAAJ&hl=en), Queen's University Belfast (2019 - 2022) 

        [Jian Gao](https://scholar.google.com/citations?user=DCZRHikAAAAJ&hl=en), Queen's University Belfast (2018 - 2022) 

        [Xinshao Wang](https://scholar.google.co.uk/citations?user=yOBhB7UAAAAJ&hl=en), Queen's University Belfast (2017 - 2020) 
 

        </div>
    design:
      columns: '2'





  - block: markdown
    id: funding
    content:
      title: Funding and Grants
      text: |-
        <div align="justify">


        King’s College London NMES Enterprise Engagement Partnerships Fund, January - June 2024.

        Fellowship for entrepreneurs of University of Surrey, August 2024 - July 2025.


        </div>
    design:
      columns: '2'


  - block: markdown
    id: prof
    content:
      title: Professional Engagements
      text: |-
        <div align="justify">


        IEEE Senior Member (2022 - )

        Associate Editor, Neurocomputing (2024 -)

        Associate Editor, IET Image Processing (2021 - )

        Area Chair: BMVC 2022, 2023

        Programme Committee: CVPR, ICCV, ECCV, NIPS, ICML, AAAI, ICLR

        Tutorial and Workshop: FG 2018, 2019, 2023
 

        </div>
    design:
      columns: '2'


  - block: contact
    content:
      title: Contact
      text:
      email: huguosheng100@gmail.com
      address:
        street: 48-60 High St
        city: Belfast, BT1 2BE,
        region: United Kingdom
        country_code: UK
    design:
      columns: '2'


  - block: markdown
    content:
      title: 
      text: |-
        <div align="center">
        <a href='https://clustrmaps.com/site/1bz6t'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=400&t=tt&d=7s9qiSOu8yFZI6bJdeLVRp-fOK9Iq_3jl7A0dr2-kAI&co=ffffff&ct=808080'/></a>
        </div>
    design:
      columns: '1'


---
