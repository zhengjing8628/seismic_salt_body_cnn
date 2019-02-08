# seismic_salt_interpretation_cnn

This notebook contains sample Python codes to prepare input data and to construct / train convolutional neural networks for automatic seismic salt interpretation with Deep Convolutional Neural networks. The potential of CNN-based salt boy interpretation is demonstrated by using a state-of-art network structure U-Net, along with the residual learning framework ResNet, to delineate salt body with high precision.

Our paper entitled **Automatic Seismic Salt Interpretation with Deep Convolutional Neural Networks** ([arxiv:1802.01101](https://arxiv.org/abs/1812.01101)) has been accepted by *The 3rd International Conference on Information System and Data Mining* ([ICISDM 2019](http://icisdm.org/)). My co-authors of this paper are Kebei Jiang and Jie Chen.

Two main IPython notebooks are posted here:
1. salt_body_segyin_data_prep.ipynb 
   * This notebook covers data preparation from SEGY, image upsampling, image cropping.
   
2. salt_body_interpret_deep_cnn.ipynb 
   * This notebook covers evaluation metric, network architecture, network training, model improvements, discussion and conclusion. 
