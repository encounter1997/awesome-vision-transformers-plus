# awesome-vision-transformers-plus
> A curated list of  papers linked to research based on self-attention for computer vision tasks, 
> built on [awesome-transformer-for-vision](https://github.com/lijiaman/awesome-transformer-for-vision)

## Contents

- [Papers and Resources](#papers-and-resources)
	- [Transformer](#papers-transformer)
	- [Self-attention Augmented CNNs](#self-attention-augmented-cnns)
	- [Early Attempts](#papers-early)
	- [2D Vision Tasks](#papers-2d)
		- [Classification](#papers-classification)
		- [Detection](#papers-detection)
		- [Segmentation](#papers-segmentation)
		- [Tracking](#papers-tracking)
		- [Image Synthesis](#papers-image-generation)
		- [Image Processing](#papers-image-processing)
		- [Action Understanding](#papers-action)
	- [3D Vision Tasks](#papers-3d)
		- [Point Cloud Processing](#papers-point-cloud)
		- [Motion Modeling](#papers-motion)
		- [Human Body Modeling](#papers-body)
	- [Theory](#papers-theory)
	- [Survey](#papers-survey)
	- [Others](#papers-others)


<a name="papers-and-resources"></a>

# Papers and Resources

<a name="papers-transformer"></a>

## Transformer

[Attention Is All You Need](https://papers.nips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf). Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, Illia Polosukhin. NeurIPS 2017.

[The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html)

[The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)


<a name="self-attention-augmented-cnns"></a>
## Self-attention Augmented CNNs
[Non-local Neural Networks](https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Non-Local_Neural_Networks_CVPR_2018_paper.pdf). Xiaolong Wang, Ross Girshick, Abhinav Gupta, Kaiming He. CVPR 2018.

[GCNet: Non-local Networks Meet Squeeze-Excitation Networks and Beyond](https://openaccess.thecvf.com/content_ICCVW_2019/papers/NeurArch/Cao_GCNet_Non-Local_Networks_Meet_Squeeze-Excitation_Networks_and_Beyond_ICCVW_2019_paper.pdf). Yue Cao, Jiarui Xu, Stephen Lin, Fangyun Wei, Han Hu. ICCVW 2019.

[CCNet: Criss-Cross Attention for Semantic Segmentation](https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_CCNet_Criss-Cross_Attention_for_Semantic_Segmentation_ICCV_2019_paper.pdf). Zilong Huang, Xinggang Wang, Yunchao Wei, Lichao Huang, Humphrey Shi, Wenyu Liu, Thomas S. Huang. ICCV 2019.

[An Empirical Study of Spatial Attention Mechanisms in Deep Networks](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhu_An_Empirical_Study_of_Spatial_Attention_Mechanisms_in_Deep_Networks_ICCV_2019_paper.pdf). Xizhou Zhu, Dazhi Cheng, Zheng Zhang, Stephen Lin, Jifeng Dai. ICCV 2019.


[Attention Augmented Convolutional Networks](https://openaccess.thecvf.com/content_ICCV_2019/papers/Bello_Attention_Augmented_Convolutional_Networks_ICCV_2019_paper.pdf). Irwan Bello, Barret Zoph, Ashish Vaswani, Jonathon Shlens, Quoc V. Le. ICCV 2019.

[Disentangled Non-Local Neural Networks](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600188.pdf). Minghao Yin, Zhuliang Yao, Yue Cao, Xiu Li, Zheng Zhang, Stephen Lin, Han Hu. ECCV 2020.

<a name="papers-early"></a>
## Early Attempts


[Local Relation Networks for Image Recognition](https://openaccess.thecvf.com/content_ICCV_2019/papers/Hu_Local_Relation_Networks_for_Image_Recognition_ICCV_2019_paper.pdf). Han Hu, Zheng Zhang, Zhenda Xie, Stephen Lin. ICCV 2019.

[Stand-Alone Self-Attention in Vision Models](https://papers.nips.cc/paper/2019/file/3416a75f4cea9109507cacd8e2f2aefc-Paper.pdf). Prajit Ramachandran, Niki Parmar, Ashish Vaswani, Irwan Bello, Anselm Levskaya, Jonathon Shlens. NIPS 2019.


[Exploring Self-attention for Image Recognition](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_Exploring_Self-Attention_for_Image_Recognition_CVPR_2020_paper.pdf). Hengshuang Zhao, Jiaya Jia, Vladlen Koltun. CVPR 2020.

[Axial Attention in Multidimensional Transformers](https://arxiv.org/pdf/1912.12180). Jonathan Ho, Nal Kalchbrenner, Dirk Weissenborn, Tim Salimans. Arxiv 2019.







<a name="papers-2d"></a>
## 2D Vision Tasks

<a name="papers-classification"></a>
### Classification

[An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/pdf/2010.11929.pdf). Alexey Dosovitskiy, Lucas Beyer, Alexander Kolesnikov, Dirk Weissenborn, Xiaohua Zhai, Thomas Unterthiner, Mostafa Dehghani, Matthias Minderer, Georg Heigold, Sylvain Gelly, Jakob Uszkoreit, Neil Houlsby. ICLR 2021. 

[Training data-efficient image transformers & distillation through attention](https://arxiv.org/pdf/2012.12877). Hugo Touvron, Matthieu Cord, Matthijs Douze, Francisco Massa, Alexandre Sablayrolles, Hervé Jégou. Arxiv 2020.

[Bottleneck Transformers for Visual Recognition](https://arxiv.org/pdf/2101.11605). Aravind Srinivas, Tsung-Yi Lin, Niki Parmar, Jonathon Shlens, Pieter Abbeel, Ashish Vaswani. Arxiv 2021.

[Tokens-to-Token ViT: Training Vision Transformers from Scratch on ImageNet](https://arxiv.org/pdf/2101.11986). Li Yuan, Yunpeng Chen, Tao Wang, Weihao Yu, Yujun Shi, Francis EH Tay, Jiashi Feng, Shuicheng Yan. Arxiv 2021.

<a name="papers-detection"></a>
### Detection

[Toward Transformer-Based Object Detection](https://arxiv.org/pdf/2012.09958.pdf). Josh Beal, Eric Kim, Eric Tzeng, Dong Huk Park, Andrew Zhai, Dmitry Kislyuk. Arxiv 2020.

[Rethinking Transformer-based Set Prediction for Object Detection](https://arxiv.org/pdf/2011.10881.pdf). Zhiqing Sun, Shengcao Cao, Yiming Yang, Kris Kitani. Arxiv 2020.

[End-to-End Object Detection with Transformers](https://arxiv.org/pdf/2005.12872.pdf). Nicolas Carion, Francisco Massa, Gabriel Synnaeve, Nicolas Usunier, Alexander Kirillov, and Sergey Zagoruyko. ECCV 2020.

[Deformable DETR: Deformable Transformers for End-to-End Object Detection](https://arxiv.org/pdf/2010.04159.pdf). Xizhou Zhu, Weijie Su, Lewei Lu, Bin Li, Xiaogang Wang, Jifeng Dai. ICLR 2021. 

[UP-DETR: Unsupervised Pre-training for Object Detection with Transformers](https://arxiv.org/pdf/2011.09094.pdf). Zhigang Dai, Bolun Cai, Yugeng Lin, Junying Chen. Arxiv 2020.

[End-to-End Object Detection with Adaptive Clustering Transformer](https://arxiv.org/pdf/2011.09315). Minghang Zheng, Peng Gao, Xiaogang Wang, Hongsheng Li, Hao Dong. Arxiv 2020. 

[Fast Convergence of DETR with Spatially Modulated Co-Attention](https://arxiv.org/pdf/2101.07448.pdf). Peng Gao, Minghang Zheng, Xiaogang Wang, Jifeng Dai, Hongsheng Li. Arxiv 2021.





<a name="papers-segmentation"></a>
### Segmentation
[Axial-DeepLab: Stand-Alone Axial-Attention for Panoptic Segmentation](https://arxiv.org/abs/2003.07853). Huiyu Wang, Yukun Zhu, Bradley Green, Hartwig Adam, Alan Yuille, Liang-Chieh Chen. ECCV 2020.

[Rethinking Semantic Segmentation from a Sequence-to-Sequence Perspective with Transformers](https://arxiv.org/pdf/2012.15840.pdf). Sixiao Zheng, Jiachen Lu, Hengshuang Zhao, Xiatian Zhu, Zekun Luo, Yabiao Wang, Yanwei Fu, Jianfeng Feng, Tao Xiang, Philip H.S. Torr, Li Zhang. Arxiv 2020.

[End-to-End Video Instance Segmentation with Transformers](https://arxiv.org/pdf/2011.14503.pdf). Yuqing Wang, Zhaoliang Xu, Xinlong Wang, Chunhua Shen, Baoshan Cheng, Hao Shen, Huaxia Xia. Arxiv 2020.

[SSTVOS: Sparse Spatiotemporal Transformers for Video Object Segmentation](https://arxiv.org/pdf/2101.08833). Brendan Duke, Abdalla Ahmed, Christian Wolf, Parham Aarabi, Graham W. Taylor. Arxiv 2021.

<a name="papers-tracking"></a>
### Tracking 

[TransTrack: Multiple-Object Tracking with Transformer](https://arxiv.org/pdf/2012.15460.pdf). Peize Sun, Yi Jiang, Rufeng Zhang, Enze Xie, Jinkun Cao, Xinting Hu, Tao Kong, Zehuan Yuan, Changhu Wang, Ping Luo. Arxiv 2020.

<a name="papers-image-generation"></a>
### Image Generation

[Image Transformer](https://arxiv.org/pdf/1802.05751). Niki Parmar, Ashish Vaswani, Jakob Uszkoreit, Łukasz Kaiser, Noam Shazeer, Alexander Ku, Dustin Tran. ICML 2018.

[Taming Transformers for High-Resolution Image Synthesis](https://arxiv.org/pdf/2012.09841.pdf). Patrick Esser, Robin Rombach, Bjorn Ommer. Arxiv 2020.

<a name="papers-image-processing"></a>
### Image Processing

[Learning Texture Transformer Network for Image Super-Resolution](https://arxiv.org/pdf/2006.04139). Fuzhi Yang, Huan Yang, Jianlong Fu, Hongtao Lu, Baining Guo. CVPR 2020.

[Learning Joint Spatial-Temporal Transformations for Video Inpainting](https://arxiv.org/pdf/2007.10247). Yanhong Zeng, Jianlong Fu, Hongyang Chao. ECCV 2020.

[Colorization Transformer](https://openreview.net/pdf?id=5NA1PinlGFu). Manoj Kumar, Dirk Weissenborn, Nal Kalchbrenner. ICLR 2021.

[Pre-Trained Image Processing Transformer](https://arxiv.org/pdf/2012.00364). Hanting Chen, Yunhe Wang, Tianyu Guo, Chang Xu, Yiping Deng, Zhenhua Liu, Siwei Ma, Chunjing Xu, Chao Xu, Wen Gao. Arxiv 2020.


<a name="papers-action"></a>
### Action Understanding

[Video Action Transformer Network](https://arxiv.org/pdf/1812.02707.pdf). Rohit Girdhar, Joao Carreira, Carl Doersch, Andrew Zisserman. CVPR 2019.

[Video Transformer Network](https://arxiv.org/pdf/2102.00719.pdf). Daniel Neimark, Omri Bar, Maya Zohar, Dotan Asselmann. Arxiv 2021.


<a name="papers-3d"></a>
## 3D Vision Tasks

<a name="papers-point-cloud"></a>
### Point Cloud Processing

[PCT: Point Cloud Transformer](https://arxiv.org/pdf/2012.09688.pdf). Meng-Hao Guo, Jun-Xiong Cai, Zheng-Ning Liu, Tai-Jiang Mu, Ralph R. Martin, Shi-Min Hu. Arxiv 2020.

[Point Transformer](https://arxiv.org/pdf/2012.09164.pdf). Hengshuang Zhao, Li Jiang, Jiaya Jia, Philip Torr, Vladlen Koltun. Arxiv 2020.

<a name="papers-motion"></a>
### Motion Modeling

[Learning to Generate Diverse Dance Motions with Transformer](https://arxiv.org/pdf/2008.08171.pdf). Jiaman Li, Yihang Yin, Hang Chu, Yi Zhou, Tingwu Wang, Sanja Fidler, Hao Li. Arxiv 2020.

[A Spatio-temporal Transformer for 3D Human Motion Prediction](https://arxiv.org/pdf/2004.08692.pdf). Emre Aksan, Peng Cao, Manuel Kaufmann, Otmar Hilliges. Arxiv 2020.

<a name="papers-body"></a>
### Human Body Modeling

[End-to-End Human Pose and Mesh Reconstruction with Transformers](https://arxiv.org/pdf/2012.09760.pdf). Kevin Lin, Lijuan Wang, Zicheng Liu. Arxiv 2020.


<a name="papers-theory"></a>
## Theory

[On the Relationship between Self-Attention and Convolutional Layers](https://openreview.net/pdf?id=HJlnC1rKPB). Jean-Baptiste Cordonnier, Andreas Loukas, Martin Jaggi. ICLR 2020.


<a name="papers-survey"></a>
## Survey

[A Survey on Visual Transformer](https://arxiv.org/pdf/2012.12556). Kai Han, Yunhe Wang, Hanting Chen, Xinghao Chen, Jianyuan Guo, Zhenhua Liu, Yehui Tang, An Xiao, Chunjing Xu, Yixing Xu, Zhaohui Yang, Yiman Zhang, Dacheng Tao. Arxiv 2020.

[Transformers in Vision: A Survey](https://arxiv.org/pdf/2101.01169). Salman Khan, Muzammal Naseer, Munawar Hayat, Syed Waqas Zamir, Fahad Shahbaz Khan, Mubarak Shah. Arxiv 2021.



<a name="papers-others"></a>
## Others

[Music Transformer: Generating Music with Long-Term Structure](https://arxiv.org/pdf/1809.04281.pdf). Cheng-Zhi Anna Huang, Ashish Vaswani, Jakob Uszkoreit, Noam Shazeer, Ian Simon, Curtis Hawthorne, Andrew M. Dai, Matthew D. Hoffman, Monica Dinculescu, Douglas Eck. ICLR 2019. 

[Decoupling the Role of Data, Attention, and Losses in Multimodal Transformers](https://arxiv.org//pdf/2102.00529). Lisa Anne Hendricks, John Mellor, Rosalia Schneider, Jean-Baptiste Alayrac, Aida Nematzadeh. Arxiv 2021.



