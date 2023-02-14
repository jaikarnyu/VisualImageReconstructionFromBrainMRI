# Computer Vision Course Project

Deep neural networks (DNNs) have recently been successfully applied to brain decoding and image reconstruction from functional magnetic resonance imaging (fMRI) activity. However, training DNNs directly on fMRI data is often avoided because the available data size is considered insufficient for training complex networks with a large number of parameters in fMRI data and images. The common approach is to use the fMRI data to decode individual DNN
features of the stimulus image and pass it to a pre-trained
Generator network to reconstruct images. In this study, we
examine the performance of the reconstruction model us-
ing several methods based on encoder-decoder models and
propose a new method that incorporates CLIP for the en-
coder. Experiments were performed using up to 6,000 train-
ing data samples (fMRI signals). The results show that we
can efficiently perform image reconstruction by perform-
ing unsupervised pretraining of image generators on large
datasets like ImageNet
