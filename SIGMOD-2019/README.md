Classical and Contemporary Approaches to Big Time Series Forecasting
===

<h3>Time: 9:00 - 12:30pm, Friday, July 5th, 2019<br/>Location: Verwey Kamer, <a href="https://www.google.com/maps/place/Beurs+van+Berlage/@52.3750622,4.8939773,17z/data=!4m12!1m6!3m5!1s0x47c609c787f17ca7:0xfdc6eede688a772f!2sBeurs+van+Berlage!8m2!3d52.3750622!4d4.8961713!3m4!1s0x47c609c787f17ca7:0xfdc6eede688a772f!8m2!3d52.3750622!4d4.8961713">Amsterdam Conference Center</a>, Amsterdam</h3>

## Overview
Time series forecasting is a key ingredient in the automation and optimization of business processes: in retail, deciding which products to order and where to store them depends on the forecasts of future demand in different regions; in cloud computing, the estimated future usage of services and infrastructure components guides capacity planning; and workforce scheduling in warehouses and factories requires forecasts of the future workload. Recent years have witnessed a paradigm shift in forecasting techniques and applications, from computer-assisted model- and assumption-based to data-driven and fully-automated. This shift can be attributed to the availability of large, rich, and diverse time series corpora and result in a set of challenges that need to be addressed such as the following. How can we build statistical models to efficiently and effectively learn to forecast from large and diverse data sources? How can we leverage the statistical power of "similar'' time series to improve forecasts in the case of limited observations? What are the implications for building forecasting systems that can handle large data volumes? The objective of this tutorial is to provide a concise and intuitive overview of the most important methods and tools available for solving large-scale forecasting problems. We review the state of the art in three related fields: (1) classical modeling of time series, (2) scalable tensor methods, and (3) deep learning for forecasting. Further, we share lessons learned from building scalable forecasting systems. While our focus is on providing an intuitive overview of the methods and practical issues which we will illustrate via case studies, we also present some technical details underlying these powerful tools.

## Presenters

[<img align="right" width="150" src="https://kdd18.mxnet.io/_static/amazon_ai.png">](https://aws.amazon.com)
[<img align="right" width="115" src="http://www.cs.cmu.edu/~jhclark/logos/scslogo_no_outline_simple.gif">](https://www.cs.cmu.edu)

  * [Christos Faloutsos](http://www.cs.cmu.edu/~christos/) (CMU and Amazon)
  * [Jan Gasthaus](http://www.gatsby.ucl.ac.uk/~ucabjga/) (AWS AI Labs)
  * [Tim Januschowski](http://www.januschowski.de/tim/) (AWS AI Labs)
  * [Yuyang (Bernie) Wang](http://www.mit.edu/~ywang02/) (AWS AI Labs)

## Slides [[PDF](https://www.dropbox.com/s/fob700v6a6xyt4m/fcst-tutorial-sigmod.pdf?dl=0)]

## Cite [[PDF](https://dl.acm.org/citation.cfm?doid=3299869.3314033)]
```
@inproceedings{faloutsos2019classical,
  title={Classical and Contemporary Approaches to Big Time Series Forecasting},
  author={Faloutsos, Christos and Gasthaus, Jan and Januschowski, Tim and Wang, Yuyang},
  booktitle={Proceedings of the 2019 International Conference on Management of Data},
  pages={2042--2047},
  year={2019},
  organization={ACM}
}
```

## Tentative Schedule
* Introduction to Forecasting
  * Basic (explanatory) analysis and decomposition of time series, i.e., trend, level, seasonality, etc.
  * Point forecast vs. probabilistic forecast
  * Forecast accuracy metric and backtest scenario  
* Classical approaches: Linear and Non-linear models (local, learning one time series at a time)
  * Naive baselines: mean, drift, seasonal naive, ...
  * Generalized Linear Models (GLM), Autoregressive GLM (AR models)
  * Exponential smoothing, state-space models
* Modern approaches: Tensor Analysis and Deep Learning models (globally finding patterns)
  * Large scale tensor analysis
  * Deep learning for forecasting
    * Multi-layer perceptron (feedforward neural networks)
    * Recurrent neural networks (RNN)s: canonical, Sequence-to-Sequence and other architectures
    * Others structures: Convolution, WaveNet, and all that
* Lessons learnt building forecasting system
  * Building large scale forecasting systems
  * Developing Deep Autoregressive Network ([DeepAR](https://arxiv.org/abs/1704.04110)) in [AWS Sagemaker](https://aws.amazon.com/sagemaker/) and other models in [Amazon Forecast](https://aws.amazon.com/forecast/)
  * Getting started with Forecasting using [GluonTS](https://gluon-ts.mxnet.io) 

## Presenters' Bio

<img align="left" src="https://github.com/lovvge/Forecasting-Tutorials/raw/master/figures/faloutsos.jpg"> *Christos Faloutsos* is a Professor at Carnegie Mellon University. He has received the Presidential Young Investigator Award by the National Science Foundation (1989), the Research Contributions Award in ICDM 2006, the SIGKDD Innovations Award (2010), twenty ``best paper'' awards (including two test of time awards), and four teaching awards. Five of his advisees have attracted KDD or SCS dissertation awards. He is an ACM Fellow, he has served as a member of the executive committee of SIGKDD; he has published over 300 refereed articles, 17 book chapters, and two monographs. He holds eight patents and has given over 40 tutorials and over 20 invited distinguished lectures. His research interests include data mining for graphs and streams, fractals, database performance, and indexing for multimedia and bioinformatics data.

<img align="left" src="https://github.com/lovvge/Forecasting-Tutorials/raw/master/figures/gasthaus.jpg"> *Jan Gasthaus* is a Senior Machine Learning Scientist in the Amazon AI Labs, working mainly on time series forecasting and large-scale probabilistic machine learning. He is passionate about developing novel machine learning solutions for addressing challenging business problems with scalable machine learning systems, all the way from scientific ideation to productization. Prior to joining Amazon, Jan obtained a BS in Cognitive Science from the University of Osnabrueck, an MS in Intelligent Systems from UCL, and pursued a PhD at the Gatsby Unit, UCL, focusing on Nonparametric Bayesian methods for sequence data.

<img align="left" src="https://github.com/lovvge/Forecasting-Tutorials/raw/master/figures/januschowski.jpg"> *Tim Januschowski* is a Machine Learning Science Manager in Amazon AI Labs. He has worked on forecasting since starting his professional career. At Amazon, he has produced end-to-end solutions for a wide variety of forecasting problems, from demand forecasting to server capacity forecasting. Tim's personal interests in forecasting span applications, system, algorithm and modeling aspects and the downstream mathematical programming problems. He studied Mathematics at TU Berlin, IMPA, Rio de Janeiro, and Zuse-Institute Berlin and holds a PhD from University College Cork.

<img align="left" src="https://github.com/lovvge/Forecasting-Tutorials/raw/master/figures/wang.jpg"> *Yuyang (Bernie) Wang* is a Senior Machine Learning Scientist in Amazon AI Labs, working mainly on large-scale probabilistic machine learning with its application in Forecasting. He received his PhD in Computer Science from Tufts University, MA, US and he holds an MS from the Department of Computer Science at Tsinghua University, Beijing, China. His research interests span statistical machine learning, numerical linear algebra, and random matrix theory. In forecasting, Yuyang has worked on all aspects ranging from practical applications to theoretical foundations.

## Related Tutorials
Some recent tutorials by Christos and Co. on big time series mining:
  * [Forecasting Big Time Series: Old and New, VLDB 2018](https://lovvge.github.io/Forecasting-Tutorial-VLDB-2018/)
  * [Mining and Forecasting of Big Time-series Data, SIGMOD 2015](http://www.cs.kumamoto-u.ac.jp/~yasuko/TALKS/15-SIGMOD-tut/)
  * [Mining Big Time-series Data on the Web, WWW 2016](http://www.cs.kumamoto-u.ac.jp/~yasuko/TALKS/16-WWW-tut/)
  * [Smart Analytics for Big Time-series Data, KDD 2017](http://www.cs.kumamoto-u.ac.jp/~yasuko/TALKS/17-KDD-tut/)

## Notebooks with [MXNet Gluon](https://mxnet.incubator.apache.org) 
<img align="left" width="230" src="https://kdd18.mxnet.io/_static/gluon_logo_horizontal_small.png">

Several of the notebooks come from the time series chapter we are writing for [Deep Learning -- The Straight Dope](https://github.com/zackchase/mxnet-the-straight-dope), an interactive book on deep learning by our colleagues at Amazon: Zachary C. Lipton ([@zackchase](https://github.com/zackchase)), Mu Li ([@mli](https://github.com/mli)), Alex Smola ([@smolix](https://github.com/smolix)), Sheng Zha ([@szha](https://github.com/szha)), Aston Zhang ([@astonzhang](https://github.com/astonzhang)), and others.

* Prerequisite: 
  * [A crash course on Gluon](https://gluon-crash-course.mxnet.io)
  * [Gluon Tutorial at KDD18](https://kdd18.mxnet.io) and [KDD18-Gluon repository](https://github.com/szha/KDD18-Gluon)
* [Introduction to Forecasting](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/chapter12_time-series/intro-forecasting-gluon.ipynb)
  * Basic elements of forecasting  
  * Forecast Evaluation: metrics, backtest scenarios
* Classical Models
  * [Generalized Linear Models](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/chapter12_time-series/intro-forecasting-1-gluon.ipynb)
  * [Linear Dynamical System](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/chapter12_time-series/lds-scratch.ipynb)
  * [Exponential Smoothing and Innovative State-space modeling](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/chapter12_time-series/issm-scratch.ipynb)
* Neural Network Models
  * [Multi-layer Perceptron](https://github.com/zackchase/mxnet-the-straight-dope/blob/master/chapter12_time-series/intro-forecasting-2-gluon.ipynb)
  * [Recurrent Neural Networks (RNN)](./notebooks/RNN-with-Beer-simple.ipynb)
  * [Bayesian RNN](./notebooks/RNN-BBB-with-Beer-Forecasting.ipynb)
  * CNN-based models
* [Doing Forecasting with DeepAR in AWS SageMaker](https://github.com/awslabs/amazon-sagemaker-examples/blob/master/introduction_to_amazon_algorithms/deepar_synthetic/deepar_synthetic.ipynb)
* [Building Neural Network Models for Forecasting with GluonTS](https://aws.amazon.com/blogs/machine-learning/creating-neural-time-series-models-with-gluon-time-series/)
***

<p align="center">
<img align="middle" width="115" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/Amazon_logo_plain.svg/2000px-Amazon_logo_plain.svg.png">
</p>
