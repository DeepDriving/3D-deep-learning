# 3D Deep Learning


## 3D CNNs
- [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation
](http://stanford.edu/~rqi/pointnet/)

## Interesting papers about 3D Classification

- [Deep Learning on Point Sets for 3D Classification and Segmentation](https://web.stanford.edu/class/cs331b/projects/qi.pdf).

### Voxel struct as input
- [3D Convolutional Neural Networks for Landing Zone Detection from LiDAR](https://www.ri.cmu.edu/pub_files/2015/3/maturana-root.pdf).

### Point Cloud as input
- 1 [Vote3Deep: Fast Object Detection in 3D Point Clouds Using Efficient Convolutional Neural Networks](https://arxiv.org/pdf/1609.06666v1.pdf).
- 2 [Learning objects from RGB-D sensors using point cloud-based neural networks](https://www2.informatik.uni-hamburg.de/wtm/ps/Borghetti_ESANN_2015.pdf).
- 3 [3D Object Recognition using Convolutional Neural Networks with Transfer Learning between Input Channels](http://www.di.ubi.pt/~lfbaa/pubs/ias-13.pdf)
- 4 [Orientation-boosted Voxel Nets for 3D Object Recognition](https://arxiv.org/pdf/1604.03351.pdf)
- 5 [3D Fully Convolutional Network for Vehicle Detection in Point Cloud](https://arxiv.org/pdf/1611.08069.pdf)


#### Interesting Reads and Links

- [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision). A curated list of deep learning resources for computer vision.
- [Deep Learning: An MIT Press book in preparation](http://www.iro.umontreal.ca/~bengioy/dlbook/).
- [Deep Learning Reading List](http://deeplearning.net/reading-list/). A list of books, papers, surveys and other readings about deep learning.
- [Deep down the rabbit hole: CVPR 2015 and beyond](http://www.computervisionblog.com/2015/06/deep-down-rabbit-hole-cvpr-2015-and.html). Insightful review of the CVPR2015, including ConvNets, Torch vs Caffe, object detectors, and ArXiv publishing.
- [CVPR2015 recap and where we are going](http://zoyathinks.blogspot.com.es/2015/06/cvpr-recap-and-where-were-going.html). Nice summary of the whole conference, as well as a cool summary/highlights [document](http://web.mit.edu/zoya/www/CVPR2015brief.pdf) of some selected papers.

### NVIDIA Deep Learning Course

- Introduction to Deep Learning. [Video](https://www.youtube.com/watch?v=6eBpjEdgSm0)/[Slides](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/intro-to-deep-learning.pdf)/[Hands-on lab](https://nvidia.qwiklab.com/focuses/preview/102)/[Office hours Q&A](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/intro-to-deep-learning-questions-answers.pdf).
- Getting started with the Caffe Framework. [Video](https://www.youtube.com/watch?v=rvMVqPsXL10)/[Slides](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/getting-started-with-caffe.pdf)/[Hands-on lab](https://nvidia.qwiklab.com/focuses/preview/136)/[Office hours Q&A](http://on-demand.gputechconf.com/gtc/2015/webinar/deep-learning-course/getting-started-with-caffe-questions-answers.pdf).

## Theoretical Background

### Convolutional Neural Networks (CNN)

Check out the nice Stanford CS course titled [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/). There is a nice lecture on [Convolutional Neural Networks (CNNs / ConvNets)](http://cs231n.github.io/convolutional-networks/) which provides an architectural overview as well as detailed explanations of the different layers and popular architectures.

A nice collection of final reports by the course students is available [here](http://cs231n.stanford.edu/reports.html). The following ones are specially remarkable:

- [Tiny ImageNet Challenge - Dissection of a convolutional neural network](http://cs231n.stanford.edu/reports/jbboin_finalreport.pdf). Explains a simple architecture and dissects it with useful insight. Besides, the figures are nice and can serve as inspiration.
- [Learning 3D Object Orientations From Synthetic Images](http://cs231n.stanford.edu/reports/rqi_final_report.pdf). Cool approach to mix 3D training data (which is converted to 2D) with 2D input images for object orientation detection.
- [Convolutional Neural Networks for Fashion Classification and Object Detection](http://cs231n.stanford.edu/reports/BLAO_KJAG_CS231N_FinalPaperFashionClassification.pdf). Multiple object detection in the same image, instead of single object per image.

### Deep Neural Networks (DNN)

## Frameworks

### Torch

[Torch](http://torch.ch/) is a scientific computing framework which supports a wide variety of machine learning algorithms. Characterized by an easy use thanks to its LuaJIT scripting language. It also features significant efficiency due to the underlying CUDA/C implementation.

- [GitHub repository](https://github.com/torch/torch7)
- [Convolutional Neural Network example with Lua](https://github.com/nicholas-leonard/dp/blob/master/examples/convolutionneuralnetwork.lua)
- [Object detection with Recursive Convolutional Neural Network and Lua](https://github.com/fmassa/object-detection.torch)

### Caffe

[Caffe](https://github.com/BVLC/caffe/) is a deep learning framework developed by the [Berkeley Vision and Learning Center (BVLC)](http://bvlc.eecs.berkeley.edu/). It is implemented mainly in C++ and supports GPU computing thanks to CUDA.

- [GitHub repository](https://github.com/BVLC/caffe/)
- [arXiv / ACM MM ‘14 paper. Caffe: Convolutional Architecture for Fast Feature Embedding](http://arxiv.org/abs/1408.5093)
- [Hands-On Tutorial: Deep Learning for Vision with Caffe](https://docs.google.com/presentation/d/1UeKXVgRvvxg9OUdh_UiC5G71UMscNPlvArsWER41PsU/edit#slide=id.p)

### TensorFlow

- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow)
- [First contact with TensorFlow](http://jorditorres.org/first-contact-with-tensorflow/)
- [Understanding neural networks with TensorFlow Playground](https://cloud.google.com/blog/big-data/2016/07/understanding-neural-networks-with-tensorflow-playground)

### Theano
