
# Deep Learning (CAS machine intelligence, 2021  ) 

This course in deep learning focuses on practical aspects of deep learning. We therefore provide jupyter notebooks ([complete overview of all notebooks](https://github.com/tensorchiefs/dl_course_2020/tree/master/notebooks) used in the course). 

For doing the hands-on part we recommend to use colab (you might need a google account) an internet connections is needed. If you want to do it without internet connection on your own computer you can either install anaconda ([details and installation instruction](anaconda.md)) or use the provided a docker container ([details and installation instruction](docker.md)).

To easily follow the course please make sure that you are familiar with the some [basic math and python skills](prerequistites.md). 

## Info for the projects
You can join together in small groups and choose a topic for your DL project. You should prepare a poster and a spotlight talk (5 minutes) which you will present on the last course day. To get some hints how to create a good poster you can check out the links that are provided in <a href="https://www.dropbox.com/s/u1f6mqk4pc3uhxe/poster-guidelines.pdf?dl=1">poster_guidelines.pdf</a> 

If you need free GPU resources, we might want to follow the [instructions how to use google colab](co.md). Help for preparing a hdf5 file from your images you can be found in the <a href="https://github.com/tensorchiefs/dl_course_2018/blob/master/notebooks/data_prep.ipynb"> example Notebook.</a> 

Examples for projects from the DL course 2018 and 2019 can be found [here](projects.md).

**Fill in the Title and the Topic of your Projects until 24.03.2020 [here](https://docs.google.com/spreadsheets/d/18VFrPbKq3YSOg8Ebc1q1wGgkfgaWl7IkcCClGEDGj6Q/edit#gid=0)**

## Other resources 
We took inspiration (and sometimes slides / figures) from the following resources.

* Probabilistic Deep Learning (DL-Book) [Probabilistic Deep Learning](https://www.manning.com/books/probabilistic-deep-learning?a_aid=probabilistic_deep_learning&a_bid=78e55885). This book is by the tensorchiefs and covers the increasingly popular probabilistic approach to deep learning .

* Deep Learning Book (DL-Book) [http://www.deeplearningbook.org/](http://www.deeplearningbook.org/). This is a quite comprehensive book which goes far beyond the scope of this course.

* Convolutional Neural Networks for Visual Recognition [http://cs231n.stanford.edu/](http://cs231n.stanford.edu/), has additional material and [youtube videos of the lectures](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC). While the focus is on computer vision, it also treats other topics such as optimization, backpropagation and RNNs. Lecture notes can be found at [http://cs231n.github.io/](http://cs231n.github.io/).

* More TensorFlow examples can be found at [dl_tutorial](https://github.com/oduerr/dl_tutorial/tree/master/tensorflow/) 

* Another applied course in DL: [TensorFlow and Deep Learning without a PhD](https://cloud.google.com/blog/big-data/2017/01/learn-tensorflow-and-deep-learning-without-a-phd)

## Dates 
The course is split in 8 sessions, each 4 lectures long. 

| Day  |      Date    |      Time    |
|:--------:|:--------------|:---------------|
| 1        | 23.02.2021|9:00-12:30
| 2        | 02.03.2021|9:00-12:30
| 3        | 09.03.2021|9:00-12:30
| 4        | 16.03.2021|9:00-12:30
| 5        | 23.03.2021|9:00-12:30
| 6        | 30.03.2021|9:00-12:30
| 7        | 06.04.2021|9:00-12:30
| 8        | 13.04.2021|9:00-12:30

## Syllabus (might change during course)

| Day  |      Topic and Slides    |      Additional Material    |		Exercises and homework  |
|:----------------:|:-----------------------|:----------------------------|:--------------------------------------|
| 1        | Introduction, Fully Connected Networks, Keras [slides](https://github.com/tensorchiefs/dl_course_2021/blob/master/slides/01_Introduction.pdf) |[Network Playground](https://playground.tensorflow.org/) |[01_simple_forward_pass](https://github.com/tensorchiefs/dl_course_2021/blob/master/notebooks/01_simple_forward_pass.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2021/blob/master/notebooks/01_simple_forward_pass.ipynb)<br>[02_fcnn_with_banknote](https://github.com/tensorchiefs/dl_course_2021/blob/master/notebooks/02_fcnn_with_banknote.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2021/blob/master/notebooks/02_fcnn_with_banknote.ipynb)
| 2        |Looking back at fcNN, working with loss curves, convolutional neural networks [slides](https://github.com/tensorchiefs/dl_course_2021/blob/master/slides/02_fcNN_CNN.pdf) |[Understanding convolution](https://towardsdatascience.com/intuitively-understanding-convolutions-for-deep-learning-1f6f42faee1)|[03_fcnn_mnist](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/03_fcnn_mnist.ipynb)<br>[04_fcnn_mnist_shuffled](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/04_fcnn_mnist_shuffled.ipynb)<br>[05_cnn_edge_lover](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/05_cnn_edge_lover.ipynb)<br>[06_cnn_mnist_shuffled](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/06_cnn_mnist_shuffled.ipynb)<br>[07_cifar10_norm](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/07_cifar10_norm.ipynb)
| x| Below not updated for 2021 | Below not updated for 2021 | Below not updated for 2021 
| 3        |Tricks of the trade in CNNs [slides](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/03_CNN.pdf)|[Understanding CNNs](http://cs231n.github.io/understanding-cnn)|[08_cifar10_tricks](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/08_cifar10_tricks.ipynb)<br>[09_1DConv](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/09_1DConv.ipynb)
| 4        |Details: Backpropagation in DL, MaxLike-Principle [slides](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/04_Details.pdf)| |[10_linreg_tensorflow](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/10_linreg_tensorflow.ipynb)<br>[11_backpropagation](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/11_backpropagation.ipynb)<br>[maxlik](https://github.com/tensorchiefs/dl_book/blob/master/chapter_04/nb_ch04_01.ipynb)
|**no lecture due to corona crisis**         |**no lecture due to corona crisis**|**no lecture due to corona crisis**|**no lecture due to corona crisis**
|6     |Probabilistic Models [slides_part_1](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/05_Probabilistic_Modeling_part1.pdf)  [slides_part_2](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/05_part2.pdf)| |[13_linreg_with_tfp](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/13_linreg_with_tfp.ipynb)<br>[14_poisreg_with_tfp](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/14_poisreg_with_tfp.ipynb)
| 7        |Probabilistic models in the wild [slides_part_1](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/06_part1.pdf) [slides_part_2](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/06_mixtures_and_bayes_part2.pdf) ||[15_zipreg_with_tfp](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/15_zipreg_with_tfp.ipynb)<br>[16_linreg_with_tfp_const_sigma](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/16_linreg_with_tfp_const_sigma.ipynb)<br>[17_faces_regression](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/17_faces_regression.ipynb)<br>[18_elephant_in_the_room](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/18_elephant_in_the_room.ipynb)
| 8        | Bayesian Deep Learning [slides_part_1](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/07_bayes_part1.pdf) [slides_part_2](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/07_bayes_part2.pdf)| |[20_cifar10_classification_mc_and_vi](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/20_cifar10_classification_mc_and_vi.ipynb)|
|9        |presentation of team projects | |


