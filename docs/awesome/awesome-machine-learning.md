# Awesome Machine Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome machine learning frameworks, libraries and software (https://github.com/josephmisiti/awesome-machine-learning/blob/master/by language). Inspired by `awesome-php`.

If you want to contribute to this list (https://github.com/josephmisiti/awesome-machine-learning/blob/master/please do), send me a pull request or contact me [@josephmisiti](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://twitter.com/josephmisiti).
Also, a listed repository should be deprecated if:

* Repository's owner explicitly say that "this library is not maintained".
* Not committed for long time (https://github.com/josephmisiti/awesome-machine-learning/blob/master/2~3 years).

Further resources:

* For a list of free machine learning books available for download, go [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/books.md).

* For a list of (https://github.com/josephmisiti/awesome-machine-learning/blob/master/mostly) free machine learning courses available online, go [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/josephmisiti/awesome-machine-learning/blob/master/courses.md).

* For a list of blogs on data science and machine learning, go [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/blogs.md).

* For a list of free-to-attend meetups and local events, go [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/meetups.md).


### Frameworks and Libraries
<!-- MarkdownTOC depth=4 -->

- [APL](#apl)
    - [General-Purpose Machine Learning](#apl-general-purpose)
- [C](#c)
    - [General-Purpose Machine Learning](#c-general-purpose)
    - [Computer Vision](#c-cv)
- [C++](#cpp)
    - [Computer Vision](#cpp-cv)
    - [General-Purpose Machine Learning](#cpp-general-purpose)
    - [Natural Language Processing](#cpp-nlp)
    - [Speech Recognition](#speech-recognition-1)
    - [Sequence Analysis](#cpp-sequence)
    - [Gesture Recognition](#cpp-gestures)
- [Common Lisp](#common-lisp)
    - [General-Purpose Machine Learning](#common-lisp-general-purpose)
- [Clojure](#clojure)
    - [Natural Language Processing](#clojure-nlp)
    - [General-Purpose Machine Learning](#clojure-general-purpose)
    - [Data Analysis / Data Visualization](#clojure-data-analysis)
- [Crystal](#crystal)
    - [General-Purpose Machine Learning](#crystal-general-purpose)
- [Elixir](#elixir)
    - [General-Purpose Machine Learning](#elixir-general-purpose)
    - [Natural Language Processing](#elixir-nlp)
- [Erlang](#erlang)
    - [General-Purpose Machine Learning](#erlang-general-purpose)
- [Go](#go)
    - [Natural Language Processing](#go-nlp)
    - [General-Purpose Machine Learning](#go-general-purpose)
    - [Data Analysis / Data Visualization](#go-data-analysis)
    - [Facial Detection and Recognition](#go-facial-recognition)
    - [Image Classification](#go-image-classification)
- [Haskell](#haskell)
    - [General-Purpose Machine Learning](#haskell-general-purpose)
- [Java](#java)
    - [Natural Language Processing](#java-nlp)
    - [General-Purpose Machine Learning](#java-general-purpose)
    - [Speech Recognition](#java-speech-recognition)
    - [Data Analysis / Data Visualization](#java-data-analysis)
    - [Deep Learning](#java-deep-learning)
- [Javascript](#javascript)
    - [Natural Language Processing](#javascript-nlp)
    - [Data Analysis / Data Visualization](#javascript-data-analysis)
    - [General-Purpose Machine Learning](#javascript-general-purpose)
    - [Misc](#javascript-misc)
    - [Demos and Scripts](#javascript-demos)
- [Julia](#julia)
    - [General-Purpose Machine Learning](#julia-general-purpose)
    - [Natural Language Processing](#julia-nlp)
    - [Data Analysis / Data Visualization](#julia-data-analysis)
    - [Misc Stuff / Presentations](#julia-misc)
- [Lua](#lua)
    - [General-Purpose Machine Learning](#lua-general-purpose)
    - [Demos and Scripts](#lua-demos)
- [Matlab](#matlab)
    - [Computer Vision](#matlab-cv)
    - [Natural Language Processing](#matlab-nlp)
    - [General-Purpose Machine Learning](#matlab-general-purpose)
    - [Data Analysis / Data Visualization](#matlab-data-analysis)
- [.NET](#net)
    - [Computer Vision](#net-cv)
    - [Natural Language Processing](#net-nlp)
    - [General-Purpose Machine Learning](#net-general-purpose)
    - [Data Analysis / Data Visualization](#net-data-analysis)
- [Objective C](#objectivec)
    - [General-Purpose Machine Learning](#objectivec-general-purpose)
- [OCaml](#ocaml)
    - [General-Purpose Machine Learning](#ocaml-general-purpose)
- [Perl](#perl)
    - [Data Analysis / Data Visualization](#perl-data)
	- [General-Purpose Machine Learning](#perl-ml)
- [Perl 6](#perl6)
- [PHP](#php)
    - [Natural Language Processing](#php-nlp)
    - [General-Purpose Machine Learning](#php-general-purpose)
- [Python](#python)
    - [Computer Vision](#python-cv)
    - [Natural Language Processing](#python-nlp)
    - [General-Purpose Machine Learning](#python-general-purpose)
    - [Data Analysis / Data Visualization](#python-data-analysis)
    - [Misc Scripts / iPython Notebooks / Codebases](#python-misc)
    - [Kaggle Competition Source Code](#python-kaggle)
    - [Neural Networks](#python-neural-networks)
    - [Reinforcement Learning](#python-reinforcement-learning)
- [Ruby](#ruby)
    - [Natural Language Processing](#ruby-nlp)
    - [General-Purpose Machine Learning](#ruby-general-purpose)
    - [Data Analysis / Data Visualization](#ruby-data-analysis)
    - [Misc](#ruby-misc)
- [Rust](#rust)
    - [General-Purpose Machine Learning](#rust-general-purpose)
- [R](#r)
    - [General-Purpose Machine Learning](#r-general-purpose)
    - [Data Analysis / Data Visualization](#r-data-analysis)
- [SAS](#sas)
    - [General-Purpose Machine Learning](#sas-general-purpose)
    - [Data Analysis / Data Visualization](#sas-data-analysis)
    - [Natural Language Processing](#sas-nlp)
写个脚本把它们爬下来 - [Demos and Scripts](#sas-demos)
- [Scala](#scala)
    - [Natural Language Processing](#scala-nlp)
    - [Data Analysis / Data Visualization](#scala-data-analysis)
    - [General-Purpose Machine Learning](#scala-general-purpose)
- [Scheme](#scheme)
    - [Neural Networks](#scheme-neural-networks)
- [Swift](#swift)
    - [General-Purpose Machine Learning](#swift-general-purpose)
- [TensorFlow](#tensor)
    - [General-Purpose Machine Learning](#tensor-general-purpose)

### Tools

- [Neural Networks](#tools-neural-networks)
- [Misc](#tools-misc)


[Credits](#credits)

<!-- /MarkdownTOC -->

<a name="apl"></a>
## APL

<a name="apl-general-purpose"></a>
#### General-Purpose Machine Learning
* [naive-apl](https://github.com/mattcunningham/naive-apl) - Naive Bayesian Classifier implementation in APL. **[Deprecated]**

<a name="c"></a>
## C

<a name="c-general-purpose"></a>
#### General-Purpose Machine Learning
* [Darknet](https://github.com/pjreddie/darknet) - Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.
* [Recommender](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/GHamrouni/Recommender) - A C library for product recommendations/suggestions using collaborative filtering (https://github.com/josephmisiti/awesome-machine-learning/blob/master/CF).
* [Hybrid Recommender System](https://github.com/SeniorSA/hybrid-rs-trainner) - A hybrid recommender system based upon scikit-learn algorithms. **[Deprecated]**
* [neonrvm](https://github.com/siavashserver/neonrvm) - neonrvm is an open source machine learning library based on RVM technique. It's written in C programming language and comes with Python programming language bindings.

<a name="c-cv"></a>
#### Computer Vision

* [CCV](https://github.com/liuliu/ccv) - C-based/Cached/Core Computer Vision Library, A Modern Computer Vision Library.
* [VLFeat](http://www.vlfeat.org/) - VLFeat is an open and portable library of computer vision algorithms, which has Matlab toolbox.

<a name="cpp"></a>
## C++

<a name="cpp-cv"></a>
#### Computer Vision

* [DLib](http://dlib.net/imaging.html) - DLib has C++ and Python interfaces for face detection and training general object detectors.
* [EBLearn](http://eblearn.sourceforge.net/) - Eblearn is an object-oriented C++ library that implements various machine learning models **[Deprecated]**
* [OpenCV](https://opencv.org) - OpenCV has C++, C, Python, Java and MATLAB interfaces and supports Windows, Linux, Android and Mac OS.
* [VIGRA](https://github.com/ukoethe/vigra) - VIGRA is a generic cross-platform C++ computer vision and machine learning library for volumes of arbitrary dimensionality with Python bindings.

<a name="cpp-general-purpose"></a>
#### General-Purpose Machine Learning

* [BanditLib](https://github.com/jkomiyama/banditlib) - A simple Multi-armed Bandit library. **[Deprecated]**
* [Caffe](https://github.com/BVLC/caffe) - A deep learning framework developed with cleanliness, readability, and speed in mind. [DEEP LEARNING]
* [CatBoost](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/catboost/catboost) - General purpose gradient boosting on decision trees library with categorical features support out of the box. It is easy to install, contains fast inference implementation and supports CPU and GPU (https://github.com/josephmisiti/awesome-machine-learning/blob/master/even multi-GPU) computation.
* [CNTK](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/Microsoft/CNTK) - The Computational Network Toolkit (https://github.com/josephmisiti/awesome-machine-learning/blob/master/CNTK) by Microsoft Research, is a unified deep-learning toolkit that describes neural networks as a series of computational steps via a directed graph.
* [CUDA](https://code.google.com/p/cuda-convnet/) - This is a fast C++/CUDA implementation of convolutional [DEEP LEARNING]
* [DeepDetect](https://github.com/jolibrain/deepdetect) - A machine learning API and server written in C++11. It makes state of the art machine learning easy to work with and integrate into existing applications.
* [Distributed Machine learning Tool Kit (https://github.com/josephmisiti/awesome-machine-learning/blob/master/DMTK)](https://github.com/josephmisiti/awesome-machine-learning/blob/master/http://www.dmtk.io/) - A distributed machine learning (https://github.com/josephmisiti/awesome-machine-learning/blob/master/parameter server) framework by Microsoft. Enables training models on large data sets across multiple machines. Current tools bundled with it include: LightLDA and Distributed (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Multisense) Word Embedding.
* [DLib](http://dlib.net/ml.html) - A suite of ML tools designed to be easy to imbed in other applications.
* [DSSTNE](https://github.com/amznlabs/amazon-dsstne) - A software library created by Amazon for training and deploying deep neural networks using GPUs which emphasizes speed and scale over experimental flexibility.
* [DyNet](https://github.com/clab/dynet) - A dynamic neural network library working well with networks that have dynamic structures that change for every training instance. Written in C++ with bindings in Python.
* [Fido](https://github.com/FidoProject/Fido) - A highly-modular C++ machine learning library for embedded electronics and robotics.
* [igraph](http://igraph.org/) - General purpose graph library.
* [Intel(R) DAAL](https://github.com/intel/daal) - A high performance software library developed by Intel and optimized for Intel's architectures. Library provides algorithmic building blocks for all stages of data analytics and allows to process data in batch, online and distributed modes.
* [LightGBM](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/Microsoft/LightGBM) - Microsoft's fast, distributed, high performance gradient boosting (https://github.com/josephmisiti/awesome-machine-learning/blob/master/GBDT, GBRT, GBM or MART) framework based on decision tree algorithms, used for ranking, classification and many other machine learning tasks.
* [libfm](https://github.com/srendle/libfm) - A generic approach that allows to mimic most factorization models by feature engineering.
* [MLDB](https://mldb.ai) - The Machine Learning Database is a database designed for machine learning. Send it commands over a RESTful API to store data, explore it using SQL, then train machine learning models and expose them as APIs.
* [mlpack](https://www.mlpack.org/) - A scalable C++ machine learning library.
* [MXNet](https://github.com/apache/incubator-mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more.
* [proNet-core](https://github.com/cnclabs/proNet-core) - A general-purpose network embedding framework: pair-wise representations optimization Network Edit.
* [PyCUDA](https://mathema.tician.de/software/pycuda/) - Python interface to CUDA
* [ROOT](https://root.cern.ch) - A modular scientific software framework. It provides all the functionalities needed to deal with big data processing, statistical analysis, visualization and storage.
* [shark](http://image.diku.dk/shark/sphinx_pages/build/html/index.html) - A fast, modular, feature-rich open-source C++ machine learning library.
* [Shogun](https://github.com/shogun-toolbox/shogun) - The Shogun Machine Learning Toolbox.
* [sofia-ml](https://code.google.com/archive/p/sofia-ml) - Suite of fast incremental algorithms.
* [Stan](http://mc-stan.org/) - A probabilistic programming language implementing full Bayesian statistical inference with Hamiltonian Monte Carlo sampling.
* [Timbl](https://languagemachines.github.io/timbl/) - A software package/C++ library implementing several memory-based learning algorithms, among which IB1-IG, an implementation of k-nearest neighbor classification, and IGTree, a decision-tree approximation of IB1-IG. Commonly used for NLP.
* [Vowpal Wabbit (https://github.com/josephmisiti/awesome-machine-learning/blob/master/VW)](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/VowpalWabbit/vowpal_wabbit) - A fast out-of-core learning system.
* [Warp-CTC](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/baidu-research/warp-ctc) - A fast parallel implementation of Connectionist Temporal Classification (https://github.com/josephmisiti/awesome-machine-learning/blob/master/CTC), on both CPU and GPU.
* [XGBoost](https://github.com/dmlc/xgboost) - A parallelized optimized general purpose gradient boosting library.
* [ThunderGBM](https://github.com/Xtra-Computing/thundergbm) - A fast library for GBDTs and Random Forests on GPUs.
* [ThunderSVM](https://github.com/Xtra-Computing/thundersvm) - A fast SVM library on GPUs and CPUs.
* [LKYDeepNN](https://github.com/mosdeo/LKYDeepNN) - A header-only C++11 Neural Network library. Low dependency, native traditional chinese document.
* [xLearn](https://github.com/aksnzhy/xlearn) - A high performance, easy-to-use, and scalable machine learning package, which can be used to solve large-scale machine learning problems. xLearn is especially useful for solving machine learning problems on large-scale sparse data, which is very common in Internet services such as online advertisement and recommender systems.
* [Featuretools](https://github.com/featuretools/featuretools) - A library for automated feature engineering. It excels at transforming transactional and relational datasets into feature matrices for machine learning using reusable feature engineering "primitives". 
* [skynet](https://github.com/Tyill/skynet) - A library for learning neural network, has C-interface, net set in JSON. Written in C++ with bindings in Python, C++ and C#. 
* [Feast](https://github.com/gojek/feast) - A feature store for the management, discovery, and access of machine learning features. Feast provides a consistent view of feature data for both model training and model serving.
* [Polyaxon](https://github.com/polyaxon/polyaxon) - A platform for reproducible and scalable machine learning and deep learning.

<a name="cpp-nlp"></a>
#### Natural Language Processing

* [BLLIP Parser](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/BLLIP/bllip-parser) - BLLIP Natural Language Parser (https://github.com/josephmisiti/awesome-machine-learning/blob/master/also known as the Charniak-Johnson parser).
* [colibri-core](https://github.com/proycon/colibri-core) - C++ library, command line tools, and Python binding for extracting and working with basic linguistic constructions such as n-grams and skipgrams in a quick and memory-efficient way.
* [CRF++](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://taku910.github.io/crfpp/) - Open source implementation of Conditional Random Fields (https://github.com/josephmisiti/awesome-machine-learning/blob/master/CRFs) for segmenting/labeling sequential data & other Natural Language Processing tasks. **[Deprecated]**
* [CRFsuite](https://github.com/josephmisiti/awesome-machine-learning/blob/master/http://www.chokkan.org/software/crfsuite/) - CRFsuite is an implementation of Conditional Random Fields (https://github.com/josephmisiti/awesome-machine-learning/blob/master/CRFs) for labeling sequential data. **[Deprecated]**
* [frog](https://github.com/LanguageMachines/frog) - Memory-based NLP suite developed for Dutch: PoS tagger, lemmatiser, dependency parser, NER, shallow parser, morphological analyzer.
* [libfolia](https://github.com/LanguageMachines/libfolia) - C++ library for the [FoLiA format](https://proycon.github.io/folia/)
* [MeTA](https://github.com/meta-toolkit/meta) - [MeTA : ModErn Text Analysis](https://meta-toolkit.org/) is a C++ Data Sciences Toolkit that facilitates mining big text data.
* [MIT Information Extraction Toolkit](https://github.com/mit-nlp/MITIE) - C, C++, and Python tools for named entity recognition and relation extraction
* [ucto](https://github.com/LanguageMachines/ucto) - Unicode-aware regular-expression based tokenizer for various languages. Tool and C++ library. Supports FoLiA format.

#### Speech Recognition
* [Kaldi](https://github.com/kaldi-asr/kaldi) - Kaldi is a toolkit for speech recognition written in C++ and licensed under the Apache License v2.0. Kaldi is intended for use by speech recognition researchers.

<a name="cpp-sequence"></a>
#### Sequence Analysis
* [ToPS](https://github.com/ayoshiaki/tops) - This is an objected-oriented framework that facilitates the integration of probabilistic models for sequences over a user defined alphabet. **[Deprecated]**

<a name="cpp-gestures"></a>
#### Gesture Detection
* [grt](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/nickgillian/grt) - The Gesture Recognition Toolkit (https://github.com/josephmisiti/awesome-machine-learning/blob/master/GRT) is a cross-platform, open-source, C++ machine learning library designed for real-time gesture recognition.

<a name="common-lisp"></a>
## Common Lisp

<a name="common-lisp-general-purpose"></a>
#### General-Purpose Machine Learning

* [mgl](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/melisgl/mgl/) - Neural networks (https://github.com/josephmisiti/awesome-machine-learning/blob/master/boltzmann machines, feed-forward and recurrent nets), Gaussian Processes.
* [mgl-gpr](https://github.com/melisgl/mgl-gpr/) - Evolutionary algorithms. **[Deprecated]**
* [cl-libsvm](https://github.com/melisgl/cl-libsvm/) - Wrapper for the libsvm support vector machine library. **[Deprecated]**
* [cl-online-learning](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/masatoi/cl-online-learning) - Online learning algorithms (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Perceptron, AROW, SCW, Logistic Regression).
* [cl-random-forest](https://github.com/masatoi/cl-random-forest) - Implementation of Random Forest in Common Lisp.

<a name="clojure"></a>
## Clojure

<a name="clojure-nlp"></a>
#### Natural Language Processing

* [Clojure-openNLP](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/dakrone/clojure-opennlp) - Natural Language Processing in Clojure (https://github.com/josephmisiti/awesome-machine-learning/blob/master/opennlp).
* [Infections-clj](https://github.com/r0man/inflections-clj) - Rails-like inflection library for Clojure and ClojureScript.

<a name="clojure-general-purpose"></a>
#### General-Purpose Machine Learning

* [Touchstone](https://github.com/ptaoussanis/touchstone) - Clojure A/B testing library. **[Deprecated]**
* [Clojush](https://github.com/lspector/Clojush) - The Push programming language and the PushGP genetic programming system implemented in Clojure.
* [Infer](https://github.com/aria42/infer) - Inference and machine learning in Clojure. **[Deprecated]**
* [Clj-ML](https://github.com/antoniogarrote/clj-ml) - A machine learning library for Clojure built on top of Weka and friends. **[Deprecated]**
* [DL4CLJ](https://github.com/yetanalytics/dl4clj) - Clojure wrapper for Deeplearning4j.
* [Encog](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/jimpil/enclog) - Clojure wrapper for Encog (https://github.com/josephmisiti/awesome-machine-learning/blob/master/v3) (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Machine-Learning framework that specializes in neural-nets). **[Deprecated]**
* [Fungp](https://github.com/vollmerm/fungp) - A genetic programming library for Clojure. **[Deprecated]**
* [Statistiker](https://github.com/clojurewerkz/statistiker) - Basic Machine Learning algorithms in Clojure. **[Deprecated]**
* [clortex](https://github.com/htm-community/clortex) - General Machine Learning library using Numenta’s Cortical Learning Algorithm. **[Deprecated]**
* [comportex](https://github.com/htm-community/comportex) - Functionally composable Machine Learning library using Numenta’s Cortical Learning Algorithm. **[Deprecated]**
* [cortex](https://github.com/originrose/cortex) - Neural networks, regression and feature learning in Clojure.
* [lambda-ml](https://github.com/cloudkj/lambda-ml) - Simple, concise implementations of machine learning techniques and utilities in Clojure.

<a name="clojure-data-analysis"></a>
#### Data Analysis / Data Visualization

* [Incanter](http://incanter.org/) - Incanter is a Clojure-based, R-like platform for statistical computing and graphics.
* [PigPen](https://github.com/Netflix/PigPen) - Map-Reduce for Clojure.
* [Envision](https://github.com/clojurewerkz/envision) - Clojure Data Visualisation library, based on Statistiker and D3.

<a name="crystal"></a>
## Crystal

<a name="crystal-general-purpose"></a>
#### General-Purpose Machine Learning

* [machine](https://github.com/mathieulaporte/machine) - Simple machine learning algorithm.
* [crystal-fann](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/NeuraLegion/crystal-fann) - FANN (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Fast Artificial Neural Network) binding.

<a name="elixir"></a>
## Elixir

<a name="elixir-general-purpose"></a>
#### General-Purpose Machine Learning

* [Simple Bayes](https://github.com/fredwu/simple_bayes) - A Simple Bayes / Naive Bayes implementation in Elixir.
* [emel](https://github.com/mrdimosthenis/emel) - A simple and functional machine learning library written in Elixir.

<a name="elixir-nlp"></a>
#### Natural Language Processing

* [Stemmer](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/fredwu/stemmer) - An English (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Porter2) stemming implementation in Elixir.

<a name="erlang"></a>
## Erlang

<a name="erlang-general-purpose"></a>
#### General-Purpose Machine Learning

* [Disco](https://github.com/discoproject/disco/) - Map Reduce in Erlang. **[Deprecated]**
* [Yanni](https://bitbucket.org/nato/yanni/overview) - ANN neural networks using Erlangs leightweight processes.

<a name="go"></a>
## Go

<a name="go-nlp"></a>
#### Natural Language Processing

* [go-porterstemmer](https://github.com/reiver/go-porterstemmer) - A native Go clean room implementation of the Porter Stemming algorithm. **[Deprecated]**
* [paicehusk](https://github.com/Rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
* [snowball](https://github.com/tebeka/snowball) - Snowball Stemmer for Go.
* [Textbox](https://godoc.org/github.com/machinebox/sdk-go/textbox) - Natural language processing SDK from Machine Box
* [go-ngram](https://github.com/Lazin/go-ngram) - In-memory n-gram index with compression.
* [word-embedding](https://github.com/ynqa/word-embedding) - Word Embeddings: the full implementation of word2vec, GloVe in Go.
* [sentences](https://github.com/neurosnap/sentences) - Golang implementation of Punkt sentence tokenizer.

<a name="go-general-purpose"></a>
#### General-Purpose Machine Learning

* [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library.
* [Go Learn](https://github.com/sjwhitworth/golearn) - Machine Learning for Go. **[Deprecated]**
* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. **[Deprecated]**
* [go-ml](https://github.com/alonsovidales/go_ml) - Linear / Logistic regression, Neural Networks, Collaborative Filtering and Gaussian Multivariate Distribution. **[Deprecated]**
* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. **[Deprecated]**
* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / Golang. **[Deprecated]**
* [Cloudforest](https://github.com/ryanbressler/CloudForest) - Ensembles of decision trees in Go/Golang. **[Deprecated]**
* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in Go.
* [GoNN](https://github.com/fxsjy/gonn) - GoNN is an implementation of Neural Network in Go Language, which includes BPNN, RBF, PCN. **[Deprecated]**
* [go-mxnet-predictor](https://github.com/songtianyi/go-mxnet-predictor) - Go binding for MXNet c_predict_api to do inference with pre-trained model.
* [neat](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (https://github.com/josephmisiti/awesome-machine-learning/blob/master/NEAT). **[Deprecated]**
* [go-ml-transpiler](https://github.com/znly/go-ml-transpiler) - An open source Go transpiler for machine learning models.

<a name="go-data-analysis"></a>
#### Data Analysis / Data Visualization

* [go-graph](https://github.com/StepLg/go-graph) - Graph library for Go/Golang language. **[Deprecated]**
* [SVGo](https://github.com/ajstarks/svgo) - The Go Language library for SVG generation.
* [RF](https://github.com/fxsjy/RF.go) - Random forests implementation in Go. **[Deprecated]**
* [Glot](https://github.com/arafatk/glot) - Glot is a plotting library for Golang built on top of gnuplot. 

<a name="go-facial-recognition"></a>
#### Facial Detection and Recognition

* [Facebox](https://godoc.org/github.com/machinebox/sdk-go/facebox) - Facial detection and recognition SDK with one-shot teaching from Machine Box

<a name="go-image-classification"></a>
#### Image Classification

* [Tagbox](https://godoc.org/github.com/machinebox/sdk-go/tagbox) - Image classification SDK with one-shot teaching from Machine Box
* [Nudebox](https://godoc.org/github.com/machinebox/sdk-go/nudebox) - Nudity detection from Machine Box

<a name="haskell"></a>
## Haskell

<a name="haskell-general-purpose"></a>
#### General-Purpose Machine Learning
* [haskell-ml](https://github.com/ajtulloch/haskell-ml) - Haskell implementations of various ML algorithms. **[Deprecated]**
* [HLearn](https://github.com/mikeizbicki/HLearn) - a suite of libraries for interpreting machine learning models according to their algebraic structure. **[Deprecated]**
* [hnn](https://github.com/alpmestan/HNN) - Haskell Neural Network library.
* [hopfield-networks](https://github.com/ajtulloch/hopfield-networks) - Hopfield Networks for unsupervised learning in Haskell. **[Deprecated]**
* [DNNGraph](https://github.com/ajtulloch/dnngraph) - A DSL for deep neural networks. **[Deprecated]**
* [LambdaNet](https://github.com/jbarrow/LambdaNet) - Configurable Neural Networks in Haskell. **[Deprecated]**

<a name="java"></a>
## Java

<a name="java-nlp"></a>
#### Natural Language Processing
* [Cortical.io](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://www.cortical.io/) - Retina: an API performing complex NLP operations (https://github.com/josephmisiti/awesome-machine-learning/blob/master/disambiguation, classification, streaming text filtering, etc...) as quickly and intuitively as the brain.
* [IRIS](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/cortical-io/Iris) - [Cortical.io's](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://cortical.io) FREE NLP, Retina API Analysis Tool (https://github.com/josephmisiti/awesome-machine-learning/blob/master/written in JavaFX!) - [See the Tutorial Video](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://www.youtube.com/watch?v=CsF4pd7fGF0).
* [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml) - Stanford CoreNLP provides a set of natural language analysis tools which can take raw English language text input and give the base forms of words.
* [Stanford Parser](https://nlp.stanford.edu/software/lex-parser.shtml) - A natural language parser is a program that works out the grammatical structure of sentences.
* [Stanford POS Tagger](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://nlp.stanford.edu/software/tagger.shtml) - A Part-Of-Speech Tagger (https://github.com/josephmisiti/awesome-machine-learning/blob/master/POS Tagger).
* [Stanford Name Entity Recognizer](https://nlp.stanford.edu/software/CRF-NER.shtml) - Stanford NER is a Java implementation of a Named Entity Recognizer.
* [Stanford Word Segmenter](https://nlp.stanford.edu/software/segmenter.shtml) - Tokenization of raw text is a standard pre-processing step for many NLP tasks.
* [Tregex, Tsurgeon and Semgrex](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://nlp.stanford.edu/software/tregex.shtml) - Tregex is a utility for matching patterns in trees, based on tree relationships and regular expression matches on nodes (https://github.com/josephmisiti/awesome-machine-learning/blob/master/the name is short for "tree regular expressions").
* [Stanford Phrasal: A Phrase-Based Translation System](https://nlp.stanford.edu/phrasal/)
* [Stanford English Tokenizer](https://nlp.stanford.edu/software/tokenizer.shtml) - Stanford Phrasal is a state-of-the-art statistical phrase-based machine translation system, written in Java.
* [Stanford Tokens Regex](https://nlp.stanford.edu/software/tokensregex.shtml) - A tokenizer divides text into a sequence of tokens, which roughly correspond to "words".
* [Stanford Temporal Tagger](https://nlp.stanford.edu/software/sutime.shtml) - SUTime is a library for recognizing and normalizing time expressions.
* [Stanford SPIED](https://nlp.stanford.edu/software/patternslearning.shtml) - Learning entities from unlabeled text starting with seed sets using patterns in an iterative fashion.
* [Stanford Topic Modeling Toolbox](https://nlp.stanford.edu/software/tmt) - Topic modeling tools to social scientists and others who wish to perform analysis on datasets.
* [Twitter Text Java](https://github.com/twitter/twitter-text/tree/master/java) - A Java implementation of Twitter's text processing library.
* [MALLET](http://mallet.cs.umass.edu/) - A Java-based package for statistical natural language processing, document classification, clustering, topic modeling, information extraction, and other machine learning applications to text.
* [OpenNLP](https://opennlp.apache.org/) - a machine learning based toolkit for the processing of natural language text.
* [LingPipe](http://alias-i.com/lingpipe/index.html) - A tool kit for processing text using computational linguistics.
* [ClearTK](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/ClearTK/cleartk) - ClearTK provides a framework for developing statistical natural language processing (https://github.com/josephmisiti/awesome-machine-learning/blob/master/NLP) components in Java and is built on top of Apache UIMA. **[Deprecated]**
* [Apache cTAKES](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://ctakes.apache.org/) - Apache clinical Text Analysis and Knowledge Extraction System (https://github.com/josephmisiti/awesome-machine-learning/blob/master/cTAKES) is an open-source natural language processing system for information extraction from electronic medical record clinical free-text.
* [NLP4J](https://github.com/emorynlp/nlp4j) - The NLP4J project provides software and resources for natural language processing. The project started at the Center for Computational Language and EducAtion Research, and is currently developed by the Center for Language and Information Research at Emory University. **[Deprecated]**
* [CogcompNLP](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/CogComp/cogcomp-nlp) - This project collects a number of core libraries for Natural Language Processing (https://github.com/josephmisiti/awesome-machine-learning/blob/master/NLP) developed in the University of Illinois' Cognitive Computation Group, for example `illinois-core-utilities` which provides a set of NLP-friendly data structures and a number of NLP-related utilities that support writing NLP applications, running experiments, etc, `illinois-edison` a library for feature extraction from illinois-core-utilities data structures and many other packages.

<a name="java-general-purpose"></a>
#### General-Purpose Machine Learning

* [aerosolve](https://github.com/airbnb/aerosolve) - A machine learning library by Airbnb designed from the ground up to be human friendly.
* [AMIDST Toolbox](http://www.amidsttoolbox.com/) - A Java Toolbox for Scalable Probabilistic Machine Learning.
* [Datumbox](https://github.com/datumbox/datumbox-framework) - Machine Learning framework for rapid development of Machine Learning and Statistical applications.
* [ELKI](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://elki-project.github.io/) - Java toolkit for data mining. (https://github.com/josephmisiti/awesome-machine-learning/blob/master/unsupervised: clustering, outlier detection etc.)
* [Encog](https://github.com/encog/encog-java-core) - An advanced neural network and machine learning framework. Encog contains classes to create a wide variety of networks, as well as support classes to normalize and process data for these neural networks. Encog trains using multithreaded resilient propagation. Encog can also make use of a GPU to further speed processing time. A GUI based workbench is also provided to help model and train neural networks.
* [FlinkML in Apache Flink](https://ci.apache.org/projects/flink/flink-docs-master/dev/libs/ml/index.html) - Distributed machine learning library in Flink.
* [H2O](https://github.com/h2oai/h2o-3) - ML engine that supports distributed learning on Hadoop, Spark or your laptop via APIs in R, Python, Scala, REST/JSON.
* [htm.java](https://github.com/numenta/htm.java) - General Machine Learning library using Numenta’s Cortical Learning Algorithm.
* [liblinear-java](https://github.com/bwaldvogel/liblinear-java) - Java version of liblinear.
* [Mahout](https://github.com/apache/mahout) - Distributed machine learning.
* [Meka](https://github.com/josephmisiti/awesome-machine-learning/blob/master/http://meka.sourceforge.net/) - An open source implementation of methods for multi-label classification and evaluation (https://github.com/josephmisiti/awesome-machine-learning/blob/master/extension to Weka).
* [MLlib in Apache Spark](https://spark.apache.org/docs/latest/mllib-guide.html) - Distributed machine learning library in Spark
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - a service for deployment Apache Spark MLLib machine learning models as realtime, batch or reactive web services.
* [Neuroph](http://neuroph.sourceforge.net/) - Neuroph is lightweight Java neural network framework
* [ORYX](https://github.com/oryxproject/oryx) - Lambda Architecture Framework using Apache Spark and Apache Kafka with a specialization for real-time large-scale machine learning.
* [Samoa](https://samoa.incubator.apache.org/) SAMOA is a framework that includes distributed machine learning for data streams with an interface to plug-in different stream processing platforms.
* [RankLib](https://sourceforge.net/p/lemur/wiki/RankLib/) - RankLib is a library of learning to rank algorithms. **[Deprecated]**
* [rapaio](https://github.com/padreati/rapaio) - statistics, data mining and machine learning toolbox in Java.
* [RapidMiner](https://rapidminer.com) - RapidMiner integration into Java code.
* [Stanford Classifier](https://nlp.stanford.edu/software/classifier.shtml) - A classifier is a machine learning tool that will take data items and place them into one of k classes.
* [SmileMiner](https://github.com/haifengl/smile) - Statistical Machine Intelligence & Learning Engine.
* [SystemML](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/apache/systemml) - flexible, scalable machine learning (https://github.com/josephmisiti/awesome-machine-learning/blob/master/ML) language.
* [Weka](https://www.cs.waikato.ac.nz/ml/weka/) - Weka is a collection of machine learning algorithms for data mining tasks.
* [LBJava](https://github.com/CogComp/lbjava) - Learning Based Java is a modeling language for the rapid development of software systems, offers a convenient, declarative syntax for classifier and constraint definition directly in terms of the objects in the programmer's application.


<a name="java-speech-recognition"></a>
#### Speech Recognition
* [CMU Sphinx](https://cmusphinx.github.io) - Open Source Toolkit For Speech Recognition purely based on Java speech recognition library.

<a name="java-data-analysis"></a>
#### Data Analysis / Data Visualization

* [Flink](https://flink.apache.org/) - Open source platform for distributed stream and batch data processing.
* [Hadoop](https://github.com/apache/hadoop) - Hadoop/HDFS.
* [Onyx](https://github.com/onyx-platform/onyx) - Distributed, masterless, high performance, fault tolerant data processing. Written entirely in Clojure.
* [Spark](https://github.com/apache/spark) - Spark is a fast and general engine for large-scale data processing.
* [Storm](https://storm.apache.org/) - Storm is a distributed realtime computation system.
* [Impala](https://github.com/cloudera/impala) - Real-time Query for Hadoop.
* [DataMelt](https://jwork.org/dmelt/) - Mathematics software for numeric computation, statistics, symbolic calculations, data analysis and data visualization.
* [Dr. Michael Thomas Flanagan's Java Scientific Library](https://www.ee.ucl.ac.uk/~mflanaga/java/) **[Deprecated]**

<a name="java-deep-learning"></a>
#### Deep Learning

* [Deeplearning4j](https://github.com/deeplearning4j/deeplearning4j) - Scalable deep learning for industry with parallel GPUs.

<a name="javascript"></a>
## Javascript

<a name="javascript-nlp"></a>
#### Natural Language Processing

* [Twitter-text](https://github.com/twitter/twitter-text) - A JavaScript implementation of Twitter's text processing library.
* [natural](https://github.com/NaturalNode/natural) - General natural language facilities for node.
* [Knwl.js](https://github.com/loadfive/Knwl.js) - A Natural Language Processor in JS.
* [Retext](https://github.com/retextjs/retext) - Extensible system for analyzing and manipulating natural language.
* [NLP Compromise](https://github.com/spencermountain/compromise) - Natural Language processing in the browser.
* [nlp.js](https://github.com/axa-group/nlp.js) - An NLP library built in node over Natural, with entity extraction, sentiment analysis, automatic language identify, and so more



<a name="javascript-data-analysis"></a>
#### Data Analysis / Data Visualization

* [D3.js](https://d3js.org/)
* [High Charts](https://www.highcharts.com/)
* [NVD3.js](http://nvd3.org/)
* [dc.js](https://dc-js.github.io/dc.js/)
* [chartjs](https://www.chartjs.org/)
* [dimple](http://dimplejs.org/)
* [amCharts](https://www.amcharts.com/)
* [D3xter](https://github.com/NathanEpstein/D3xter) - Straight forward plotting built on D3. **[Deprecated]**
* [statkit](https://github.com/rigtorp/statkit) - Statistics kit for JavaScript. **[Deprecated]**
* [datakit](https://github.com/nathanepstein/datakit) - A lightweight framework for data analysis in JavaScript
* [science.js](https://github.com/jasondavies/science.js/) - Scientific and statistical computing in JavaScript. **[Deprecated]**
* [Z3d](https://github.com/NathanEpstein/Z3d) - Easily make interactive 3d plots built on Three.js **[Deprecated]**
* [Sigma.js](http://sigmajs.org/) - JavaScript library dedicated to graph drawing.
* [C3.js](https://c3js.org/) - customizable library based on D3.js for easy chart drawing.
* [Datamaps](https://datamaps.github.io/) - Customizable SVG map/geo visualizations using D3.js. **[Deprecated]**
* [ZingChart](https://www.zingchart.com/) - library written on Vanilla JS for big data visualization.
* [cheminfo](https://www.cheminfo.org/) - Platform for data visualization and analysis, using the [visualizer](https://github.com/npellet/visualizer) project.
* [Learn JS Data](http://learnjsdata.com/)
* [AnyChart](https://www.anychart.com/)
* [FusionCharts](https://www.fusioncharts.com/)
* [Nivo](https://nivo.rocks) - built on top of the awesome d3 and Reactjs libraries


<a name="javascript-general-purpose"></a>
#### General-Purpose Machine Learning

* [Auto ML](https://github.com/ClimbsRocks/auto_ml) - Automated machine learning, data formatting, ensembling, and hyperparameter optimization for competitions and exploration- just give it a .csv file!
* [Convnet.js](https://cs.stanford.edu/people/karpathy/convnetjs/) - ConvNetJS is a Javascript library for training Deep Learning models[DEEP LEARNING] **[Deprecated]**
* [Clusterfck](https://harthur.github.io/clusterfck/) - Agglomerative hierarchical clustering implemented in Javascript for Node.js and the browser. **[Deprecated]**
* [Clustering.js](https://github.com/emilbayes/clustering.js) - Clustering algorithms implemented in Javascript for Node.js and the browser. **[Deprecated]**
* [Decision Trees](https://github.com/serendipious/nodejs-decision-tree-id3) - NodeJS Implementation of Decision Tree using ID3 Algorithm. **[Deprecated]**
* [DN2A](https://github.com/antoniodeluca/dn2a.js) - Digital Neural Networks Architecture. **[Deprecated]**
* [figue](https://code.google.com/archive/p/figue) - K-means, fuzzy c-means and agglomerative clustering.
* [Gaussian Mixture Model](https://github.com/lukapopijac/gaussian-mixture-model) - Unsupervised machine learning with multivariate Gaussian mixture model.
* [Node-fann](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/rlidwka/node-fann) - FANN (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Fast Artificial Neural Network Library) bindings for Node.js **[Deprecated]**
* [Keras.js](https://github.com/transcranial/keras-js) - Run Keras models in the browser, with GPU support provided by WebGL 2.
* [Kmeans.js](https://github.com/emilbayes/kMeans.js) - Simple Javascript implementation of the k-means algorithm, for node.js and the browser. **[Deprecated]**
* [LDA.js](https://github.com/primaryobjects/lda) - LDA topic modeling for Node.js
* [Learning.js](https://github.com/yandongliu/learningjs) - Javascript implementation of logistic regression/c4.5 decision tree **[Deprecated]**
* [machinelearn.js](https://github.com/machinelearnjs/machinelearnjs) - Machine Learning library for the web, Node.js and developers
* [mil-tokyo](https://github.com/mil-tokyo) - List of several machine learning libraries.
* [Node-SVM](https://github.com/nicolaspanel/node-svm) - Support Vector Machine for Node.js
* [Brain](https://github.com/harthur/brain) - Neural networks in JavaScript **[Deprecated]**
* [Brain.js](https://github.com/BrainJS/brain.js) - Neural networks in JavaScript - continued community fork of [Brain](https://github.com/harthur/brain).
* [Bayesian-Bandit](https://github.com/omphalos/bayesian-bandit.js) - Bayesian bandit implementation for Node and the browser. **[Deprecated]**
* [Synaptic](https://github.com/cazala/synaptic) - Architecture-free neural network library for Node.js and the browser.
* [kNear](https://github.com/NathanEpstein/kNear) - JavaScript implementation of the k nearest neighbors algorithm for supervised learning.
* [NeuralN](https://github.com/totemstech/neuraln) - C++ Neural Network library for Node.js. It has advantage on large dataset and multi-threaded training. **[Deprecated]**
* [kalman](https://github.com/itamarwe/kalman) - Kalman filter for Javascript. **[Deprecated]**
* [shaman](https://github.com/luccastera/shaman) - Node.js library with support for both simple and multiple linear regression. **[Deprecated]**
* [ml.js](https://github.com/mljs/ml) - Machine learning and numerical analysis tools for Node.js and the Browser!
* [ml5](https://github.com/ml5js/ml5-library) - Friendly machine learning for the web!
* [Pavlov.js](https://github.com/NathanEpstein/Pavlov.js) - Reinforcement learning using Markov Decision Processes.
* [MXNet](https://github.com/apache/incubator-mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more.
* [TensorFlow.js](https://js.tensorflow.org/) - A WebGL accelerated, browser based JavaScript library for training and deploying ML models.
* [JSMLT](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/jsmlt/jsmlt) - Machine learning toolkit with classification and clustering for Node.js; supports visualization (https://github.com/josephmisiti/awesome-machine-learning/blob/master/see [visualml.io](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://visualml.io)).
* [xgboost-node](https://github.com/nuanio/xgboost-node) - Run XGBoost model and make predictions in Node.js.
* [Netron](https://github.com/lutzroeder/netron) - Visualizer for machine learning models.
* [WebDNN](https://github.com/mil-tokyo/webdnn) - Fast Deep Neural Network Javascript Framework. WebDNN uses next generation JavaScript API, WebGPU for GPU execution, and WebAssembly for CPU execution.  

<a name="javascript-misc"></a>
#### Misc

* [stdlib](https://github.com/stdlib-js/stdlib) - A standard library for JavaScript and Node.js, with an emphasis on numeric computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.
* [sylvester](https://github.com/jcoglan/sylvester) - Vector and Matrix math for JavaScript. **[Deprecated]**
* [simple-statistics](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/simple-statistics/simple-statistics) - A JavaScript implementation of descriptive, regression, and inference statistics. Implemented in literate JavaScript with no dependencies, designed to work in all modern browsers (https://github.com/josephmisiti/awesome-machine-learning/blob/master/including IE) as well as in Node.js.
* [regression-js](https://github.com/Tom-Alexander/regression-js) - A javascript library containing a collection of least squares fitting methods for finding a trend in a set of data.
* [Lyric](https://github.com/flurry/Lyric) - Linear Regression library. **[Deprecated]**
* [GreatCircle](https://github.com/mwgg/GreatCircle) - Library for calculating great circle distance.
* [MLPleaseHelp](https://github.com/jgreenemi/MLPleaseHelp) - MLPleaseHelp is a simple ML resource search engine. You can use this search engine right now at [https://jgreenemi.github.io/MLPleaseHelp/](https://jgreenemi.github.io/MLPleaseHelp/), provided via Github Pages.

<a name="javascript-demos"></a>
#### Demos and Scripts
* [The Bot](https://github.com/sta-ger/TheBot) - Example of how the neural network learns to predict the angle between two points created with [Synaptic](https://github.com/cazala/synaptic).
* [Half Beer](https://github.com/sta-ger/HalfBeer) - Beer glass classifier created with [Synaptic](https://github.com/cazala/synaptic).

<a name="julia"></a>
## Julia

<a name="julia-general-purpose"></a>
#### General-Purpose Machine Learning

* [MachineLearning](https://github.com/benhamner/MachineLearning.jl) - Julia Machine Learning library. **[Deprecated]**
* [MLBase](https://github.com/JuliaStats/MLBase.jl) - A set of functions to support the development of machine learning algorithms.
* [PGM](https://github.com/JuliaStats/PGM.jl) - A Julia framework for probabilistic graphical models.
* [DA](https://github.com/trthatcher/DiscriminantAnalysis.jl) - Julia package for Regularized Discriminant Analysis.
* [Regression](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/lindahua/Regression.jl) - Algorithms for regression analysis (https://github.com/josephmisiti/awesome-machine-learning/blob/master/e.g. linear regression and logistic regression). **[Deprecated]**
* [Local Regression](https://github.com/JuliaStats/Loess.jl) - Local regression, so smooooth!
* [Naive Bayes](https://github.com/nutsiepully/NaiveBayes.jl) - Simple Naive Bayes implementation in Julia. **[Deprecated]**
* [Mixed Models](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/dmbates/MixedModels.jl) - A Julia package for fitting (https://github.com/josephmisiti/awesome-machine-learning/blob/master/statistical) mixed-effects models.
* [Simple MCMC](https://github.com/fredo-dedup/SimpleMCMC.jl) - basic mcmc sampler implemented in Julia. **[Deprecated]**
* [Distances](https://github.com/JuliaStats/Distances.jl) - Julia module for Distance evaluation.
* [Decision Tree](https://github.com/bensadeghi/DecisionTree.jl) - Decision Tree Classifier and Regressor.
* [Neural](https://github.com/compressed/BackpropNeuralNet.jl) - A neural network in Julia.
* [MCMC](https://github.com/doobwa/MCMC.jl) - MCMC tools for Julia. **[Deprecated]**
* [Mamba](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/brian-j-smith/Mamba.jl) - Markov chain Monte Carlo (https://github.com/josephmisiti/awesome-machine-learning/blob/master/MCMC) for Bayesian analysis in Julia.
* [GLM](https://github.com/JuliaStats/GLM.jl) - Generalized linear models in Julia.
* [Gaussian Processes](https://github.com/STOR-i/GaussianProcesses.jl) - Julia package for Gaussian processes.
* [Online Learning](https://github.com/lendle/OnlineLearning.jl) **[Deprecated]**
* [GLMNet](https://github.com/simonster/GLMNet.jl) - Julia wrapper for fitting Lasso/ElasticNet GLM models using glmnet.
* [Clustering](https://github.com/JuliaStats/Clustering.jl) - Basic functions for clustering data: k-means, dp-means, etc.
* [SVM](https://github.com/JuliaStats/SVM.jl) - SVM's for Julia. **[Deprecated]**
* [Kernel Density](https://github.com/JuliaStats/KernelDensity.jl) - Kernel density estimators for julia.
* [MultivariateStats](https://github.com/JuliaStats/MultivariateStats.jl) - Methods for dimensionality reduction.
* [NMF](https://github.com/JuliaStats/NMF.jl) - A Julia package for non-negative matrix factorization.
* [ANN](https://github.com/EricChiang/ANN.jl) - Julia artificial neural networks. **[Deprecated]**
* [Mocha](https://github.com/pluskid/Mocha.jl) - Deep Learning framework for Julia inspired by Caffe. **[Deprecated]**
* [XGBoost](https://github.com/dmlc/XGBoost.jl) - eXtreme Gradient Boosting Package in Julia.
* [ManifoldLearning](https://github.com/wildart/ManifoldLearning.jl) - A Julia package for manifold learning and nonlinear dimensionality reduction.
* [MXNet](https://github.com/apache/incubator-mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more.
* [Merlin](https://github.com/hshindo/Merlin.jl) - Flexible Deep Learning Framework in Julia.
* [ROCAnalysis](https://github.com/davidavdav/ROCAnalysis.jl) - Receiver Operating Characteristics and functions for evaluation probabilistic binary classifiers.
* [GaussianMixtures](https://github.com/davidavdav/GaussianMixtures.jl) - Large scale Gaussian Mixture Models.
* [ScikitLearn](https://github.com/cstjean/ScikitLearn.jl) - Julia implementation of the scikit-learn API.
* [Knet](https://github.com/denizyuret/Knet.jl) - Koç University Deep Learning Framework.

<a name="julia-nlp"></a>
#### Natural Language Processing

* [Topic Models](https://github.com/slycoder/TopicModels.jl) - TopicModels for Julia. **[Deprecated]**
* [Text Analysis](https://github.com/JuliaText/TextAnalysis.jl) - Julia package for text analysis.


<a name="julia-data-analysis"></a>
#### Data Analysis / Data Visualization

* [Graph Layout](https://github.com/IainNZ/GraphLayout.jl) - Graph layout algorithms in pure Julia.
* [LightGraphs](https://github.com/JuliaGraphs/LightGraphs.jl) - Graph modeling and analysis.
* [Data Frames Meta](https://github.com/JuliaData/DataFramesMeta.jl) - Metaprogramming tools for DataFrames.
* [Julia Data](https://github.com/nfoti/JuliaData) - library for working with tabular data in Julia. **[Deprecated]**
* [Data Read](https://github.com/queryverse/ReadStat.jl) - Read files from Stata, SAS, and SPSS.
* [Hypothesis Tests](https://github.com/JuliaStats/HypothesisTests.jl) - Hypothesis tests for Julia.
* [Gadfly](https://github.com/GiovineItalia/Gadfly.jl) - Crafty statistical graphics for Julia.
* [Stats](https://github.com/JuliaStats/StatsKit.jl) - Statistical tests for Julia.
* [RDataSets](https://github.com/johnmyleswhite/RDatasets.jl) - Julia package for loading many of the data sets available in R.
* [DataFrames](https://github.com/JuliaData/DataFrames.jl) - library for working with tabular data in Julia.
* [Distributions](https://github.com/JuliaStats/Distributions.jl) - A Julia package for probability distributions and associated functions.
* [Data Arrays](https://github.com/JuliaStats/DataArrays.jl) - Data structures that allow missing values. **[Deprecated]**
* [Time Series](https://github.com/JuliaStats/TimeSeries.jl) - Time series toolkit for Julia.
* [Sampling](https://github.com/lindahua/Sampling.jl) - Basic sampling algorithms for Julia.

<a name="julia-misc"></a>
#### Misc Stuff / Presentations

* [DSP](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/JuliaDSP/DSP.jl) - Digital Signal Processing (https://github.com/josephmisiti/awesome-machine-learning/blob/master/filtering, periodograms, spectrograms, window functions).
* [JuliaCon Presentations](https://github.com/JuliaCon/presentations) - Presentations for JuliaCon.
* [SignalProcessing](https://github.com/JuliaDSP/DSP.jl) - Signal Processing tools for Julia.
* [Images](https://github.com/JuliaImages/Images.jl) - An image library for Julia.

<a name="lua"></a>
## Lua

<a name="lua-general-purpose"></a>
#### General-Purpose Machine Learning

* [Torch7](http://torch.ch/)
  * [cephes](https://github.com/deepmind/torch-cephes) - Cephes mathematical functions library, wrapped for Torch. Provides and wraps the 180+ special mathematical functions from the Cephes mathematical library, developed by Stephen L. Moshier. It is used, among many other places, at the heart of SciPy. **[Deprecated]**
  * [autograd](https://github.com/twitter/torch-autograd) - Autograd automatically differentiates native Torch code. Inspired by the original Python version.
  * [graph](https://github.com/torch/graph) - Graph package for Torch. **[Deprecated]**
  * [randomkit](https://github.com/deepmind/torch-randomkit) - Numpy's randomkit, wrapped for Torch. **[Deprecated]**
  * [signal](https://github.com/soumith/torch-signal) - A signal processing toolbox for Torch-7. FFT, DCT, Hilbert, cepstrums, stft.
  * [nn](https://github.com/torch/nn) - Neural Network package for Torch.
  * [torchnet](https://github.com/torchnet/torchnet) - framework for torch which provides a set of abstractions aiming at encouraging code re-use as well as encouraging modular programming.
  * [nngraph](https://github.com/torch/nngraph) - This package provides graphical computation for nn library in Torch7.
  * [nnx](https://github.com/clementfarabet/lua---nnx) - A completely unstable and experimental package that extends Torch's builtin nn library.
  * [rnn](https://github.com/Element-Research/rnn) - A Recurrent Neural Network library that extends Torch's nn. RNNs, LSTMs, GRUs, BRNNs, BLSTMs, etc.
  * [dpnn](https://github.com/Element-Research/dpnn) - Many useful features that aren't part of the main nn package.
  * [dp](https://github.com/nicholas-leonard/dp) - A deep learning library designed for streamlining research and development using the Torch7 distribution. It emphasizes flexibility through the elegant use of object-oriented design patterns. **[Deprecated]**
  * [optim](https://github.com/torch/optim) - An optimization library for Torch. SGD, Adagrad, Conjugate-Gradient, LBFGS, RProp and more.
  * [unsup](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/koraykv/unsup) - A package for unsupervised learning in Torch. Provides modules that are compatible with nn (https://github.com/josephmisiti/awesome-machine-learning/blob/master/LinearPsd, ConvPsd, AutoEncoder, ...), and self-contained algorithms (https://github.com/josephmisiti/awesome-machine-learning/blob/master/k-means, PCA). **[Deprecated]**
  * [manifold](https://github.com/clementfarabet/manifold) - A package to manipulate manifolds.
  * [svm](https://github.com/koraykv/torch-svm) - Torch-SVM library. **[Deprecated]**
  * [lbfgs](https://github.com/clementfarabet/lbfgs) - FFI Wrapper for liblbfgs. **[Deprecated]**
  * [vowpalwabbit](https://github.com/clementfarabet/vowpal_wabbit) - An old vowpalwabbit interface to torch. **[Deprecated]**
  * [OpenGM](https://github.com/clementfarabet/lua---opengm) - OpenGM is a C++ library for graphical modeling, and inference. The Lua bindings provide a simple way of describing graphs, from Lua, and then optimizing them with OpenGM. **[Deprecated]**
  * [spaghetti](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/MichaelMathieu/lua---spaghetti) - Spaghetti (https://github.com/josephmisiti/awesome-machine-learning/blob/master/sparse linear) module for torch7 by @MichaelMathieu **[Deprecated]**
  * [LuaSHKit](https://github.com/ocallaco/LuaSHkit) - A lua wrapper around the Locality sensitive hashing library SHKit **[Deprecated]**
  * [kernel smoothing](https://github.com/rlowrance/kernel-smoothers) - KNN, kernel-weighted average, local linear regression smoothers. **[Deprecated]**
  * [cutorch](https://github.com/torch/cutorch) - Torch CUDA Implementation.
  * [cunn](https://github.com/torch/cunn) - Torch CUDA Neural Network Implementation.
  * [imgraph](https://github.com/clementfarabet/lua---imgraph) - An image/graph library for Torch. This package provides routines to construct graphs on images, segment them, build trees out of them, and convert them back to images. **[Deprecated]**
  * [videograph](https://github.com/clementfarabet/videograph) - A video/graph library for Torch. This package provides routines to construct graphs on videos, segment them, build trees out of them, and convert them back to videos. **[Deprecated]**
  * [saliency](https://github.com/marcoscoffier/torch-saliency) - code and tools around integral images. A library for finding interest points based on fast integral histograms. **[Deprecated]**
  * [stitch](https://github.com/marcoscoffier/lua---stitch) - allows us to use hugin to stitch images and apply same stitching to a video sequence. **[Deprecated]**
  * [sfm](https://github.com/marcoscoffier/lua---sfm) - A bundle adjustment/structure from motion package. **[Deprecated]**
  * [fex](https://github.com/koraykv/fex) - A package for feature extraction in Torch. Provides SIFT and dSIFT modules. **[Deprecated]**
  * [OverFeat](https://github.com/sermanet/OverFeat) - A state-of-the-art generic dense feature extractor. **[Deprecated]**
  * [wav2letter](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/facebookresearch/wav2letter) - a simple and efficient end-to-end Automatic Speech Recognition (https://github.com/josephmisiti/awesome-machine-learning/blob/master/ASR) system from Facebook AI Research.
* [Numeric Lua](http://numlua.luaforge.net/)
* [Lunatic Python](https://labix.org/lunatic-python)
* [SciLua](http://scilua.org/)
* [Lua - Numerical Algorithms](https://bitbucket.org/lucashnegri/lna) **[Deprecated]**
* [Lunum](https://github.com/jzrake/lunum) **[Deprecated]**

<a name="lua-demos"></a>
#### Demos and Scripts
* [Core torch7 demos repository](https://github.com/e-lab/torch7-demos).
  * linear-regression, logistic-regression
  * face detector (https://github.com/josephmisiti/awesome-machine-learning/blob/master/training and detection as separate demos)
  * mst-based-segmenter
  * train-a-digit-classifier
  * train-autoencoder
  * optical flow demo
  * train-on-housenumbers
  * train-on-cifar
  * tracking with deep nets
  * kinect demo
  * filter-bank visualization
  * saliency-networks
* [Training a Convnet for the Galaxy-Zoo Kaggle challenge(https://github.com/josephmisiti/awesome-machine-learning/blob/master/CUDA demo)](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/soumith/galaxyzoo)
* [Music Tagging](https://github.com/mbhenaff/MusicTagging) - Music Tagging scripts for torch7.
* [torch-datasets](https://github.com/rosejn/torch-datasets) - Scripts to load several popular datasets including:
  * BSR 500
  * CIFAR-10
  * COIL
  * Street View House Numbers
  * MNIST
  * NORB
* [Atari2600](https://github.com/fidlej/aledataset) - Scripts to generate a dataset with static frames from the Arcade Learning Environment.



<a name="matlab"></a>
## Matlab

<a name="matlab-cv"></a>
#### Computer Vision

* [Contourlets](http://www.ifp.illinois.edu/~minhdo/software/contourlet_toolbox.tar) - MATLAB source code that implements the contourlet transform and its utility functions.
* [Shearlets](https://www3.math.tu-berlin.de/numerik/www.shearlab.org/software) - MATLAB code for shearlet transform.
* [Curvelets](http://www.curvelet.org/software.html) - The Curvelet transform is a higher dimensional generalization of the Wavelet transform designed to represent images at different scales and different angles.
* [Bandlets](http://www.cmap.polytechnique.fr/~peyre/download/) - MATLAB code for bandlet transform.
* [mexopencv](https://kyamagu.github.io/mexopencv/) - Collection and a development kit of MATLAB mex functions for OpenCV library.

<a name="matlab-nlp"></a>
#### Natural Language Processing

* [NLP](https://amplab.cs.berkeley.edu/an-nlp-library-for-matlab/) - An NLP library for Matlab.

<a name="matlab-general-purpose"></a>
#### General-Purpose Machine Learning

* [Training a deep autoencoder or a classifier
on MNIST digits](https://www.cs.toronto.edu/~hinton/MatlabForSciencePaper.html) - Training a deep autoencoder or a classifier
on MNIST digits[DEEP LEARNING].
* [Convolutional-Recursive Deep Learning for 3D Object Classification](https://www.socher.org/index.php/Main/Convolutional-RecursiveDeepLearningFor3DObjectClassification) - Convolutional-Recursive Deep Learning for 3D Object Classification[DEEP LEARNING].
* [Spider](https://people.kyb.tuebingen.mpg.de/spider/) - The spider is intended to be a complete object orientated environment for machine learning in Matlab.
* [LibSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/#matlab) - A Library for Support Vector Machines.
* [ThunderSVM](https://github.com/Xtra-Computing/thundersvm) - An Open-Source SVM Library on GPUs and CPUs
* [LibLinear](https://www.csie.ntu.edu.tw/~cjlin/liblinear/#download) - A Library for Large Linear Classification.
* [Machine Learning Module](https://github.com/josephmisiti/machine-learning-module) - Class on machine w/ PDF, lectures, code
* [Caffe](https://github.com/BVLC/caffe) - A deep learning framework developed with cleanliness, readability, and speed in mind.
* [Pattern Recognition Toolbox](https://github.com/covartech/PRT) - A complete object-oriented environment for machine learning in Matlab.
* [Pattern Recognition and Machine Learning](https://github.com/PRML/PRMLT) - This package contains the matlab implementation of the algorithms described in the book Pattern Recognition and Machine Learning by C. Bishop.
* [Optunity](https://optunity.readthedocs.io/en/latest/) - A library dedicated to automated hyperparameter optimization with a simple, lightweight API to facilitate drop-in replacement of grid search. Optunity is written in Python but interfaces seamlessly with MATLAB.
* [MXNet](https://github.com/apache/incubator-mxnet/) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more.
* [Machine Learning in MatLab/Octave](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/trekhleb/machine-learning-octave) - examples of popular machine learning algorithms (https://github.com/josephmisiti/awesome-machine-learning/blob/master/neural networks, linear/logistic regressions, K-Means, etc.) with code examples and mathematics behind them being explained.


<a name="matlab-data-analysis"></a>
#### Data Analysis / Data Visualization

* [matlab_bgl](https://www.cs.purdue.edu/homes/dgleich/packages/matlab_bgl/) - MatlabBGL is a Matlab package for working with graphs.
* [gaimc](https://www.mathworks.com/matlabcentral/fileexchange/24134-gaimc---graph-algorithms-in-matlab-code) - Efficient pure-Matlab implementations of graph algorithms to complement MatlabBGL's mex functions.

<a name="net"></a>
## .NET

<a name="net-cv"></a>
#### Computer Vision

* [OpenCVDotNet](https://code.google.com/archive/p/opencvdotnet) - A wrapper for the OpenCV project to be used with .NET applications.
* [Emgu CV](http://www.emgu.com/wiki/index.php/Main_Page) - Cross platform wrapper of OpenCV which can be compiled in Mono to be run on Windows, Linus, Mac OS X, iOS, and Android.
* [AForge.NET](http://www.aforgenet.com/framework/) - Open source C# framework for developers and researchers in the fields of Computer Vision and Artificial Intelligence. Development has now shifted to GitHub.
* [Accord.NET](http://accord-framework.net) - Together with AForge.NET, this library can provide image processing and computer vision algorithms to Windows, Windows RT and Windows Phone. Some components are also available for Java and Android.

<a name="net-nlp"></a>
#### Natural Language Processing

* [Stanford.NLP for .NET](https://github.com/sergey-tihon/Stanford.NLP.NET/) - A full port of Stanford NLP packages to .NET and also available precompiled as a NuGet package.

<a name="net-general-purpose"></a>
#### General-Purpose Machine Learning

* [Accord-Framework](http://accord-framework.net/) -The Accord.NET Framework is a complete framework for building machine learning, computer vision, computer audition, signal processing and statistical applications.
* [Accord.MachineLearning](https://www.nuget.org/packages/Accord.MachineLearning/) - Support Vector Machines, Decision Trees, Naive Bayesian models, K-means, Gaussian Mixture models and general algorithms such as Ransac, Cross-validation and Grid-Search for machine-learning applications. This package is part of the Accord.NET Framework.
* [DiffSharp](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://diffsharp.github.io/DiffSharp/) - An automatic differentiation (https://github.com/josephmisiti/awesome-machine-learning/blob/master/AD) library providing exact and efficient derivatives (https://github.com/josephmisiti/awesome-machine-learning/blob/master/gradients, Hessians, Jacobians, directional derivatives, and matrix-free Hessian- and Jacobian-vector products) for machine learning and optimization applications. Operations can be nested to any level, meaning that you can compute exact higher-order derivatives and differentiate functions that are internally making use of differentiation, for applications such as hyperparameter optimization.
* [Encog](https://www.nuget.org/packages/encog-dotnet-core/) - An advanced neural network and machine learning framework. Encog contains classes to create a wide variety of networks, as well as support classes to normalize and process data for these neural networks. Encog trains using multithreaded resilient propagation. Encog can also make use of a GPU to further speed processing time. A GUI based workbench is also provided to help model and train neural networks.
* [GeneticSharp](https://github.com/giacomelli/GeneticSharp) - Multi-platform genetic algorithm library for .NET Core and .NET Framework. The library has several implementations of GA operators, like: selection, crossover, mutation, reinsertion and termination.
* [Infer.NET](https://dotnet.github.io/infer/) - Infer.NET is a framework for running Bayesian inference in graphical models. One can use Infer.NET to solve many different kinds of machine learning problems, from standard problems like classification, recommendation or clustering through to customised solutions to domain-specific problems. Infer.NET has been used in a wide variety of domains including information retrieval, bioinformatics, epidemiology, vision, and many others.
* [ML.NET](https://github.com/dotnet/machinelearning) - ML.NET is a cross-platform open-source machine learning framework which makes machine learning accessible to .NET developers. ML.NET was originally developed in Microsoft Research and evolved into a significant framework over the last decade and is used across many product groups in Microsoft like Windows, Bing, PowerPoint, Excel and more.
* [Neural Network Designer](https://sourceforge.net/projects/nnd/) - DBMS management system and designer for neural networks. The designer application is developed using WPF, and is a user interface which allows you to design your neural network, query the network, create and configure chat bots that are capable of asking questions and learning from your feed back. The chat bots can even scrape the internet for information to return in their output as well as to use for learning.
* [Vulpes](https://github.com/fsprojects/Vulpes) - Deep belief and deep learning implementation written in F# and leverages CUDA GPU execution with Alea.cuBase.

<a name="net-data-analysis"></a>
#### Data Analysis / Data Visualization

* [numl](https://www.nuget.org/packages/numl/) - numl is a machine learning library intended to ease the use of using standard modeling techniques for both prediction and clustering.
* [Math.NET Numerics](https://www.nuget.org/packages/MathNet.Numerics/) - Numerical foundation of the Math.NET project, aiming to provide methods and algorithms for numerical computations in science, engineering and every day use. Supports .Net 4.0, .Net 3.5 and Mono on Windows, Linux and Mac; Silverlight 5, WindowsPhone/SL 8, WindowsPhone 8.1 and Windows 8 with PCL Portable Profiles 47 and 344; Android/iOS with Xamarin.
* [Sho](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://www.microsoft.com/en-us/research/project/sho-the-net-playground-for-data/) - Sho is an interactive environment for data analysis and scientific computing that lets you seamlessly connect scripts (https://github.com/josephmisiti/awesome-machine-learning/blob/master/in IronPython) with compiled code (https://github.com/josephmisiti/awesome-machine-learning/blob/master/in .NET) to enable fast and flexible prototyping. The environment includes powerful and efficient libraries for linear algebra as well as data visualization that can be used from any .NET language, as well as a feature-rich interactive shell for rapid development.

<a name="objectivec"></a>
## Objective C

<a name="objectivec-general-purpose"></a>
### General-Purpose Machine Learning

* [YCML](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/yconst/YCML) - A Machine Learning framework for Objective-C and Swift (https://github.com/josephmisiti/awesome-machine-learning/blob/master/OS X / iOS).
* [MLPNeuralNet](https://github.com/nikolaypavlov/MLPNeuralNet) - Fast multilayer perceptron neural network library for iOS and Mac OS X. MLPNeuralNet predicts new examples by trained neural network. It is built on top of the Apple's Accelerate Framework, using vectorized operations and hardware acceleration if available. **[Deprecated]**
* [MAChineLearning](https://github.com/gianlucabertani/MAChineLearning) - An Objective-C multilayer perceptron library, with full support for training through backpropagation. Implemented using vDSP and vecLib, it's 20 times faster than its Java equivalent. Includes sample code for use from Swift.
* [BPN-NeuralNetwork](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/Kalvar/ios-BPN-NeuralNetwork) - It implemented 3 layers neural network (https://github.com/josephmisiti/awesome-machine-learning/blob/master/ Input Layer, Hidden Layer and Output Layer ) and it named Back Propagation Neural Network (https://github.com/josephmisiti/awesome-machine-learning/blob/master/BPN). This network can be used in products recommendation, user behavior analysis, data mining and data analysis. **[Deprecated]**
* [Multi-Perceptron-NeuralNetwork](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/Kalvar/ios-Multi-Perceptron-NeuralNetwork) - it implemented multi-perceptrons neural network (https://github.com/josephmisiti/awesome-machine-learning/blob/master/ニューラルネットワーク) based on Back Propagation Neural Network (https://github.com/josephmisiti/awesome-machine-learning/blob/master/BPN) and designed unlimited-hidden-layers.
* [KRHebbian-Algorithm](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/Kalvar/ios-KRHebbian-Algorithm) - It is a non-supervisor and self-learning algorithm (https://github.com/josephmisiti/awesome-machine-learning/blob/master/adjust the weights) in neural network of Machine Learning. **[Deprecated]**
* [KRKmeans-Algorithm](https://github.com/Kalvar/ios-KRKmeans-Algorithm) - It implemented K-Means the clustering and classification algorithm. It could be used in data mining and image compression. **[Deprecated]**
* [KRFuzzyCMeans-Algorithm](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/Kalvar/ios-KRFuzzyCMeans-Algorithm) - It implemented Fuzzy C-Means (https://github.com/josephmisiti/awesome-machine-learning/blob/master/FCM) the fuzzy clustering / classification algorithm on Machine Learning. It could be used in data mining and image compression. **[Deprecated]**

<a name="ocaml"></a>
## OCaml

<a name="ocaml-general-purpose"></a>
### General-Purpose Machine Learning

* [Oml](https://github.com/rleonid/oml) - A general statistics and machine learning library.
* [GPR](https://mmottl.github.io/gpr/) - Efficient Gaussian Process Regression in OCaml.
* [Libra-Tk](https://libra.cs.uoregon.edu) - Algorithms for learning and inference with discrete probabilistic models.
* [TensorFlow](https://github.com/LaurentMazare/tensorflow-ocaml) - OCaml bindings for TensorFlow.

<a name="perl"></a>
## Perl

<a name="perl-data"></a>
### Data Analysis / Data Visualization

* [Perl Data Language](https://metacpan.org/pod/Paws::MachineLearning), a pluggable architecture for data and image processing, which can
be [used for machine learning](https://github.com/zenogantner/PDL-ML). 

<a name="perl-ml"></a>
### General-Purpose Machine Learning

* [MXnet for Deep Learning, in Perl](https://github.com/apache/incubator-mxnet/tree/master/perl-package),
also [released in CPAN](https://metacpan.org/pod/AI::MXNet).
* [Perl Data Language](https://metacpan.org/pod/Paws::MachineLearning),
using AWS machine learning platform from Perl.
* [Algorithm::SVMLight](https://metacpan.org/pod/Algorithm::SVMLight),
  implementation of Support Vector Machines with SVMLight under it. **[Deprecated]**
* Several machine learning and artificial intelligence models are
  included in the [`AI`](https://metacpan.org/search?size=20&q=AI)
  namespace. For instance, you can
  find [Naïve Bayes](https://metacpan.org/pod/AI::NaiveBayes).

<a name="perl6"></a>
## Perl 6

* [Support Vector Machines](https://github.com/titsuki/p6-Algorithm-LibSVM)
* [Naïve Bayes](https://github.com/titsuki/p6-Algorithm-NaiveBayes)

### Data Analysis / Data Visualization

* [Perl Data Language](https://metacpan.org/pod/Paws::MachineLearning),
a pluggable architecture for data and image processing, which can
be
[used for machine learning](https://github.com/zenogantner/PDL-ML). 

### General-Purpose Machine Learning

<a name="php"></a>
## PHP

<a name="php-nlp"></a>
### Natural Language Processing

* [jieba-php](https://github.com/fukuball/jieba-php) - Chinese Words Segmentation Utilities.

<a name="php-general-purpose"></a>
### General-Purpose Machine Learning

* [PHP-ML](https://github.com/php-ai/php-ml) - Machine Learning library for PHP. Algorithms, Cross Validation, Neural Network, Preprocessing, Feature Extraction and much more in one library.
* [PredictionBuilder](https://github.com/denissimon/prediction-builder) - A library for machine learning that builds predictions using a linear regression.
* [Rubix ML](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/RubixML) - A high-level machine learning (https://github.com/josephmisiti/awesome-machine-learning/blob/master/ML) library that lets you build programs that learn from data using the PHP language.
* [19 Questions](https://github.com/fulldecent/19-questions) - A machine learning / bayesian inference assigning attributes to objects.

<a name="python"></a>
## Python

<a name="python-cv"></a>
#### Computer Vision

* [Scikit-Image](https://github.com/scikit-image/scikit-image) - A collection of algorithms for image processing in Python.
* [SimpleCV](http://simplecv.org/) - An open source computer vision framework that gives access to several high-powered computer vision libraries, such as OpenCV. Written on Python and runs on Mac, Windows, and Ubuntu Linux.
* [Vigranumpy](https://github.com/ukoethe/vigra) - Python bindings for the VIGRA C++ computer vision library.
* [OpenFace](https://cmusatyalab.github.io/openface/) - Free and open source face recognition with deep neural networks.
* [PCV](https://github.com/jesolem/PCV) - Open source Python module for computer vision. **[Deprecated]**
* [face_recognition](https://github.com/ageitgey/face_recognition) - Face recognition library that recognize and manipulate faces from Python or from the command line.
* [dockerface](https://github.com/natanielruiz/dockerface) - Easy to install and use deep learning Faster R-CNN face detection for images and video in a docker container.
* [Detectron](https://github.com/facebookresearch/Detectron) - FAIR's software system that implements state-of-the-art object detection algorithms, including Mask R-CNN. It is written in Python and powered by the Caffe2 deep learning framework.
* [albumentations](https://github.com/albu/albumentations) - А fast and framework agnostic image augmentation library that implements a diverse set of augmentation techniques. Supports classification, segmentation, detection out of the box. Was used to win a number of Deep Learning competitions at Kaggle, Topcoder and those that were a part of the CVPR workshops.
* [pytessarct](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/madmaze/pytesseract) - Python-tesseract is an optical character recognition (https://github.com/josephmisiti/awesome-machine-learning/blob/master/OCR) tool for python. That is, it will recognize and "read" the text embedded in images.Python-tesseract is a wrapper for [Google's Tesseract-OCR Engine](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/tesseract-ocr/tesseract)>.
* [imutils](https://github.com/jrosebr1/imutils) - A library containg Convenience functions to make basic image processing operations such as translation, rotation, resizing, skeletonization, and displaying Matplotlib images easier with OpenCV and Python.
* [PyTorchCV](https://github.com/donnyyou/PyTorchCV) - A PyTorch-Based Framework for Deep Learning in Computer Vision.

<a name="python-nlp"></a>
#### Natural Language Processing

* [pkuseg-python](https://github.com/lancopku/pkuseg-python) - A better version of Jieba, developed by Peking University. 
* [NLTK](https://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
* [Pattern](http://www.clips.ua.ac.be/pattern) - A web mining module for the Python programming language. It has tools for natural language processing, machine learning, among others.
* [Quepy](https://github.com/machinalis/quepy) - A python framework to transform natural language questions to queries in a database query language.
* [TextBlob](https://github.com/josephmisiti/awesome-machine-learning/blob/master/http://textblob.readthedocs.io/en/dev/) - Providing a consistent API for diving into common natural language processing (https://github.com/josephmisiti/awesome-machine-learning/blob/master/NLP) tasks. Stands on the giant shoulders of NLTK and Pattern, and plays nicely with both.
* [YAlign](https://github.com/machinalis/yalign) - A sentence aligner, a friendly tool for extracting parallel sentences from comparable corpora. **[Deprecated]**
* [jieba](https://github.com/fxsjy/jieba#jieba-1) - Chinese Words Segmentation Utilities.
* [SnowNLP](https://github.com/isnowfy/snownlp) - A library for processing Chinese text.
* [spammy](https://github.com/tasdikrahman/spammy) - A library for email Spam filtering built on top of nltk
* [loso](https://github.com/fangpenlin/loso) - Another Chinese segmentation library. **[Deprecated]**
* [genius](https://github.com/duanhongyi/genius) - A Chinese segment base on Conditional Random Field.
* [KoNLPy](http://konlpy.org) - A Python package for Korean natural language processing.
* [nut](https://github.com/pprett/nut) - Natural language Understanding Toolkit. **[Deprecated]**
* [Rosetta](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/columbia-applied-data-science/rosetta) - Text processing tools and wrappers (https://github.com/josephmisiti/awesome-machine-learning/blob/master/e.g. Vowpal Wabbit)
* [BLLIP Parser](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://pypi.org/project/bllipparser/) - Python bindings for the BLLIP Natural Language Parser (https://github.com/josephmisiti/awesome-machine-learning/blob/master/also known as the Charniak-Johnson parser). **[Deprecated]**
* [PyNLPl](https://github.com/proycon/pynlpl) - Python Natural Language Processing Library. General purpose NLP library for Python. Also contains some specific modules for parsing common NLP formats, most notably for [FoLiA](https://proycon.github.io/folia/), but also ARPA language models, Moses phrasetables, GIZA++ alignments.
* [python-ucto](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/proycon/python-ucto) - Python binding to ucto (https://github.com/josephmisiti/awesome-machine-learning/blob/master/a unicode-aware rule-based tokenizer for various languages).
* [python-frog](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/proycon/python-frog) - Python binding to Frog, an NLP suite for Dutch. (https://github.com/josephmisiti/awesome-machine-learning/blob/master/pos tagging, lemmatisation, dependency parsing, NER)
* [python-zpar](https://github.com/EducationalTestingService/python-zpar) - Python bindings for [ZPar](https://github.com/frcchang/zpar), a statistical part-of-speech-tagger, constiuency parser, and dependency parser for English.
* [colibri-core](https://github.com/proycon/colibri-core) - Python binding to C++ library for extracting and working with with basic linguistic constructions such as n-grams and skipgrams in a quick and memory-efficient way.
* [spaCy](https://github.com/explosion/spaCy) - Industrial strength NLP with Python and Cython.
* [PyStanfordDependencies](https://github.com/dmcc/PyStanfordDependencies) - Python interface for converting Penn Treebank trees to Stanford Dependencies.
* [Distance](https://github.com/doukremt/distance) - Levenshtein and Hamming distance computation. **[Deprecated]**
* [Fuzzy Wuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching in Python.
* [jellyfish](https://github.com/jamesturk/jellyfish) - a python library for doing approximate and phonetic matching of strings.
* [editdistance](https://pypi.org/project/editdistance/) - fast implementation of edit distance.
* [textacy](https://github.com/chartbeat-labs/textacy) - higher-level NLP built on Spacy.
* [stanford-corenlp-python](https://github.com/dasmith/stanford-corenlp-python) - Python wrapper for [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP) **[Deprecated]**
* [CLTK](https://github.com/cltk/cltk) - The Classical Language Toolkit.
* [rasa_nlu](https://github.com/RasaHQ/rasa_nlu) - turn natural language into structured data.
* [yase](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/PPACI/yase) - Transcode sentence (https://github.com/josephmisiti/awesome-machine-learning/blob/master/or other sequence) to list of word vector .
* [Polyglot](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/aboSamoor/polyglot) - Multilingual text (https://github.com/josephmisiti/awesome-machine-learning/blob/master/NLP) processing toolkit.
* [DrQA](https://github.com/facebookresearch/DrQA) - Reading Wikipedia to answer open-domain questions.
* [Dedupe](https://github.com/dedupeio/dedupe) - A python library for accurate and scalable fuzzy matching, record deduplication and entity-resolution.
* [Snips NLU](https://github.com/snipsco/snips-nlu) - Natural Language Understanding library for intent classification and entity extraction
* [NeuroNER](https://github.com/Franck-Dernoncourt/NeuroNER) - Named-entity recognition using neural networks providing state-of-the-art-results

<a name="python-general-purpose"></a>
#### General-Purpose Machine Learning
* [PyOD](https://github.com/yzhao062/pyod) -> Python Outlier Detection, comprehensive and scalable Python toolkit for detecting outlying objects in multivariate data. Featured for Advanced models, including Neural Networks/Deep Learning and Outlier Ensembles.
* [steppy](https://github.com/neptune-ml/steppy) -> Lightweight, Python library for fast and reproducible machine learning experimentation. Introduces very simple interface that enables clean machine learning pipeline design.
* [steppy-toolkit](https://github.com/neptune-ml/steppy-toolkit) -> Curated collection of the neural networks, transformers and models that make your machine learning work faster and more effective.
* [CNTK](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/Microsoft/CNTK) - Microsoft Cognitive Toolkit (https://github.com/josephmisiti/awesome-machine-learning/blob/master/CNTK), an open source deep-learning toolkit. Documentation can be found [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://docs.microsoft.com/cognitive-toolkit/).
* [auto_ml](https://github.com/ClimbsRocks/auto_ml) - Automated machine learning for production and analytics. Lets you focus on the fun parts of ML, while outputting production-ready code, and detailed analytics of your dataset and results. Includes support for NLP, XGBoost, CatBoost, LightGBM, and soon, deep learning. 
* [machine learning](https://github.com/jeff1evesque/machine-learning) - automated build consisting of a [web-interface](https://github.com/jeff1evesque/machine-learning#web-interface), and set of [programmatic-interface](https://github.com/jeff1evesque/machine-learning#programmatic-interface) API, for support vector machines. Corresponding dataset(s) are stored into a SQL database, then generated model(s) used for prediction(s), are stored into a NoSQL datastore.
* [XGBoost](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/dmlc/xgboost) - Python bindings for eXtreme Gradient Boosting (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Tree) Library.
* [Apache SINGA](https://singa.apache.org) - An Apache Incubating project for developing an open source machine learning library.
* [Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Book/iPython notebooks on Probabilistic Programming in Python.
* [Featureforge](https://github.com/machinalis/featureforge) A set of tools for creating and testing machine learning features, with a scikit-learn compatible API.
* [MLlib in Apache Spark](http://spark.apache.org/docs/latest/mllib-guide.html) - Distributed machine learning library in Spark
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - a service for deployment Apache Spark MLLib machine learning models as realtime, batch or reactive web services.
* [scikit-learn](https://scikit-learn.org/) - A Python module for machine learning built on top of SciPy.
* [metric-learn](https://github.com/metric-learn/metric-learn) - A Python module for metric learning.
* [SimpleAI](https://github.com/simpleai-team/simpleai) Python implementation of many of the artificial intelligence algorithms described on the book "Artificial Intelligence, a Modern Approach". It focuses on providing an easy to use, well documented and tested library.
* [astroML](https://www.astroml.org/) - Machine Learning and Data Mining for Astronomy.
* [graphlab-create](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://turi.com/products/create/docs/) - A library with various machine learning models (https://github.com/josephmisiti/awesome-machine-learning/blob/master/regression, clustering, recommender systems, graph analytics, etc.) implemented on top of a disk-backed DataFrame.
* [BigML](https://bigml.com) - A library that contacts external servers.
* [pattern](https://github.com/clips/pattern) - Web mining module for Python.
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing.
* [Pylearn2](https://github.com/lisa-lab/pylearn2) - A Machine Learning library based on [Theano](https://github.com/Theano/Theano).
* [keras](https://github.com/keras-team/keras) - High-level neural networks frontend for [TensorFlow](https://github.com/tensorflow/tensorflow), [CNTK](https://github.com/Microsoft/CNTK) and [Theano](https://github.com/Theano/Theano).
* [Lasagne](https://github.com/Lasagne/Lasagne) - Lightweight library to build and train neural networks in Theano.
* [hebel](https://github.com/hannes-brt/hebel) - GPU-Accelerated Deep Learning Library in Python. **[Deprecated]**
* [Chainer](https://github.com/chainer/chainer) - Flexible neural network framework.
* [prophet](https://facebook.github.io/prophet/) - Fast and automated time series forecasting framework by Facebook.
* [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modelling for Humans.
* [topik](https://github.com/ContinuumIO/topik) - Topic modelling toolkit. **[Deprecated]**
* [PyBrain](https://github.com/pybrain/pybrain) - Another Python Machine Learning Library.
* [Brainstorm](https://github.com/IDSIA/brainstorm) - Fast, flexible and fun neural networks. This is the successor of PyBrain.
* [Surprise](https://surpriselib.com) - A scikit for building and analyzing recommender systems.
* [Crab](https://github.com/muricoca/crab) - A flexible, fast recommender engine. **[Deprecated]**
* [python-recsys](https://github.com/ocelma/python-recsys) - A Python library for implementing a Recommender System.
* [thinking bayes](https://github.com/AllenDowney/ThinkBayes) - Book on Bayesian Analysis.
* [Image-to-Image Translation with Conditional Adversarial Networks](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/williamFalcon/pix2pix-keras) - Implementation of image to image (https://github.com/josephmisiti/awesome-machine-learning/blob/master/pix2pix) translation from the paper by [isola et al](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://arxiv.org/pdf/1611.07004.pdf).[DEEP LEARNING]
* [Restricted Boltzmann Machines](https://github.com/echen/restricted-boltzmann-machines) -Restricted Boltzmann Machines in Python. [DEEP LEARNING]
* [Bolt](https://github.com/pprett/bolt) - Bolt Online Learning Toolbox. **[Deprecated]**
* [CoverTree](https://github.com/patvarilly/CoverTree) - Python implementation of cover trees, near-drop-in replacement for scipy.spatial.kdtree **[Deprecated]**
* [nilearn](https://github.com/nilearn/nilearn) - Machine learning for NeuroImaging in Python.
* [neuropredict](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/raamana/neuropredict) - Aimed at novice machine learners and non-expert programmers, this package offers easy (https://github.com/josephmisiti/awesome-machine-learning/blob/master/no coding needed) and comprehensive machine learning (https://github.com/josephmisiti/awesome-machine-learning/blob/master/evaluation and full report of predictive performance WITHOUT requiring you to code) in Python for NeuroImaging and any other type of features. This is aimed at absorbing the much of the ML workflow, unlike other packages like nilearn and pymvpa, which require you to learn their API and code to produce anything useful.
* [imbalanced-learn](https://imbalanced-learn.org/en/stable/index.html) - Python module to perform under sampling and over sampling with various techniques.
* [Shogun](https://github.com/shogun-toolbox/shogun) - The Shogun Machine Learning Toolbox.
* [Pyevolve](https://github.com/perone/Pyevolve) - Genetic algorithm framework. **[Deprecated]**
* [Caffe](https://github.com/BVLC/caffe) - A deep learning framework developed with cleanliness, readability, and speed in mind.
* [breze](https://github.com/breze-no-salt/breze) - Theano based library for deep and recurrent neural networks. **[Deprecated]**
* [pyhsmm](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/mattjj/pyhsmm) - library for approximate unsupervised inference in Bayesian Hidden Markov Models (https://github.com/josephmisiti/awesome-machine-learning/blob/master/HMMs) and explicit-duration Hidden semi-Markov Models (https://github.com/josephmisiti/awesome-machine-learning/blob/master/HSMMs), focusing on the Bayesian Nonparametric extensions, the HDP-HMM and HDP-HSMM, mostly with weak-limit approximations.
* [mrjob](https://pythonhosted.org/mrjob/) - A library to let Python program run on Hadoop.
* [SKLL](https://github.com/EducationalTestingService/skll) - A wrapper around scikit-learn that makes it simpler to conduct experiments.
* [neurolab](https://github.com/zueve/neurolab)
* [Spearmint](https://github.com/HIPS/Spearmint) - Spearmint is a package to perform Bayesian optimization according to the algorithms outlined in the paper: Practical Bayesian Optimization of Machine Learning Algorithms. Jasper Snoek, Hugo Larochelle and Ryan P. Adams. Advances in Neural Information Processing Systems, 2012. **[Deprecated]**
* [Pebl](https://github.com/abhik/pebl/) - Python Environment for Bayesian Learning. **[Deprecated]**
* [Theano](https://github.com/Theano/Theano/) - Optimizing GPU-meta-programming code generating array oriented optimizing math compiler in Python.
* [TensorFlow](https://github.com/tensorflow/tensorflow/) - Open source software library for numerical computation using data flow graphs.
* [pomegranate](https://github.com/jmschrei/pomegranate) - Hidden Markov Models for Python, implemented in Cython for speed and efficiency.
* [python-timbl](https://github.com/proycon/python-timbl) - A Python extension module wrapping the full TiMBL C++ programming interface. Timbl is an elaborate k-Nearest Neighbours machine learning toolkit.
* [deap](https://github.com/deap/deap) - Evolutionary algorithm framework.
* [pydeep](https://github.com/andersbll/deeppy) - Deep Learning In Python. **[Deprecated]**
* [mlxtend](https://github.com/rasbt/mlxtend) - A library consisting of useful tools for data science and machine learning tasks.
* [neon](https://github.com/NervanaSystems/neon) - Nervana's [high-performance](https://github.com/soumith/convnet-benchmarks) Python-based Deep Learning framework [DEEP LEARNING].
* [Optunity](https://optunity.readthedocs.io/en/latest/) - A library dedicated to automated hyperparameter optimization with a simple, lightweight API to facilitate drop-in replacement of grid search.
* [Neural Networks and Deep Learning](https://github.com/mnielsen/neural-networks-and-deep-learning) - Code samples for my book "Neural Networks and Deep Learning" [DEEP LEARNING].
* [Annoy](https://github.com/spotify/annoy) - Approximate nearest neighbours implementation.
* [TPOT](https://github.com/EpistasisLab/tpot) - Tool that automatically creates and optimizes machine learning pipelines using genetic programming. Consider it your personal data science assistant, automating a tedious part of machine learning.
* [pgmpy](https://github.com/pgmpy/pgmpy) A python library for working with Probabilistic Graphical Models.
* [DIGITS](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/NVIDIA/DIGITS) - The Deep Learning GPU Training System (https://github.com/josephmisiti/awesome-machine-learning/blob/master/DIGITS) is a web application for training deep learning models.
* [Orange](https://orange.biolab.si/) - Open source data visualization and data analysis for novices and experts.
* [MXNet](https://github.com/apache/incubator-mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more.
* [milk](https://github.com/luispedro/milk) - Machine learning toolkit focused on supervised classification. **[Deprecated]**
* [TFLearn](https://github.com/tflearn/tflearn) - Deep learning library featuring a higher-level API for TensorFlow.
* [REP](https://github.com/yandex/rep) - an IPython-based environment for conducting data-driven research in a consistent and reproducible way. REP is not trying to substitute scikit-learn, but extends it and provides better user experience. **[Deprecated]**
* [rgf_python](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/RGF-team/rgf) - Python bindings for Regularized Greedy Forest (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Tree) Library.
* [skbayes](https://github.com/AmazaspShumik/sklearn-bayes) - Python package for Bayesian Machine Learning with scikit-learn API.
* [fuku-ml](https://github.com/fukuball/fuku-ml) - Simple machine learning library, including Perceptron, Regression, Support Vector Machine, Decision Tree and more, it's easy to use and easy to learn for beginners.
* [Xcessiv](https://github.com/reiinakano/xcessiv) - A web-based application for quick, scalable, and automated hyperparameter tuning and stacked ensembling.
* [PyTorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration
* [ML-From-Scratch](https://github.com/eriklindernoren/ML-From-Scratch) - Implementations of Machine Learning models from scratch in Python with a focus on transparency. Aims to showcase the nuts and bolts of ML in an accessible way.
* [Edward](http://edwardlib.org/) - A library for probabilistic modeling, inference, and criticism. Built on top of TensorFlow.
* [xRBM](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/omimo/xRBM) - A library for Restricted Boltzmann Machine (https://github.com/josephmisiti/awesome-machine-learning/blob/master/RBM) and its conditional variants in Tensorflow.
* [CatBoost](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/catboost/catboost) - General purpose gradient boosting on decision trees library with categorical features support out of the box. It is easy to install, well documented and supports CPU and GPU (https://github.com/josephmisiti/awesome-machine-learning/blob/master/even multi-GPU) computation.
* [stacked_generalization](https://github.com/fukatani/stacked_generalization) - Implementation of machine learning stacking technic as handy library in Python.
* [modAL](https://github.com/modAL-python/modAL) - A modular active learning framework for Python, built on top of scikit-learn.
* [Cogitare](https://github.com/cogitare-ai/cogitare): A Modern, Fast, and Modular Deep Learning and Machine Learning framework for Python. 
* [Parris](https://github.com/jgreenemi/Parris) - Parris, the automated infrastructure setup tool for machine learning algorithms.
* [neonrvm](https://github.com/siavashserver/neonrvm) - neonrvm is an open source machine learning library based on RVM technique. It's written in C programming language and comes with Python programming language bindings.
* [Turi Create](https://github.com/apple/turicreate) - Machine learning from Apple. Turi Create simplifies the development of custom machine learning models. You don't have to be a machine learning expert to add recommendations, object detection, image classification, image similarity or activity classification to your app.
* [xLearn](https://github.com/aksnzhy/xlearn) - A high performance, easy-to-use, and scalable machine learning package, which can be used to solve large-scale machine learning problems. xLearn is especially useful for solving machine learning problems on large-scale sparse data, which is very common in Internet services such as online advertisement and recommender systems.
* [mlens](https://github.com/flennerhag/mlens) - A high performance, memory efficient, maximally parallelized ensemble learning, integrated with scikit-learn.
* [Netron](https://github.com/lutzroeder/netron) - Visualizer for machine learning models.
* [Thampi](https://github.com/scoremedia/thampi) - Machine Learning Prediction System on AWS Lambda
* [MindsDB](https://github.com/mindsdb/mindsdb) - Open Source framework to streamline use of neural networks.
* [Gorgonia](https://github.com/gorgonia/gorgonia) - Gorgonia is a library that helps facilitate machine learning in Golang.

<a name="python-data-analysis"></a>
#### Data Analysis / Data Visualization

* [SciPy](https://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [NumPy](https://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [Numba](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://numba.pydata.org/) - Python JIT (https://github.com/josephmisiti/awesome-machine-learning/blob/master/just in time) compiler to LLVM aimed at scientific Python by the developers of Cython and NumPy.
* [Mars](https://github.com/mars-project/mars) - A tensor-based framework for large-scale data computation which often regarded as a parallel and distributed version of NumPy. 
* [NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [igraph](https://igraph.org/python/) - binding to igraph library - General purpose graph library.
* [Pandas](https://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [Open Mining](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/mining/mining) - Business Intelligence (https://github.com/josephmisiti/awesome-machine-learning/blob/master/BI) in Python (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Pandas web interface) **[Deprecated]**
* [PyMC](https://github.com/pymc-devs/pymc) - Markov Chain Monte Carlo sampling toolkit.
* [zipline](https://github.com/quantopian/zipline) - A Pythonic algorithmic trading library.
* [PyDy](https://www.pydy.org/) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion based around NumPy, SciPy, IPython, and matplotlib.
* [SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.
* [astropy](https://www.astropy.org/) - A community Python library for Astronomy.
* [matplotlib](https://matplotlib.org/) - A Python 2D plotting library.
* [bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
* [plotly](https://plot.ly/python/) - Collaborative web plotting for Python and matplotlib.
* [altair](https://github.com/altair-viz/altair) - A Python to Vega translator.
* [d3py](https://github.com/mikedewar/d3py) - A plotting library for Python, based on [D3.js](https://d3js.org/).
* [PyDexter](https://github.com/D3xterjs/pydexter) - Simple plotting for Python. Wrapper for D3xterjs; easily render charts in-browser.
* [ggplot](https://github.com/yhat/ggpy) - Same API as ggplot2 for R. **[Deprecated]**
* [ggfortify](https://github.com/sinhrks/ggfortify) - Unified interface to ggplot2 popular R packages.
* [Kartograph.py](https://github.com/kartograph/kartograph.py) - Rendering beautiful SVG maps in Python.
* [pygal](http://pygal.org/en/stable/) - A Python SVG Charts Creator.
* [PyQtGraph](https://github.com/pyqtgraph/pyqtgraph) - A pure-python graphics and GUI library built on PyQt4 / PySide and NumPy.
* [pycascading](https://github.com/twitter/pycascading) **[Deprecated]**
* [Petrel](https://github.com/AirSage/Petrel) - Tools for writing, submitting, debugging, and monitoring Storm topologies in pure Python.
* [Blaze](https://github.com/blaze/blaze) - NumPy and Pandas interface to Big Data.
* [emcee](https://github.com/dfm/emcee) - The Python ensemble sampling toolkit for affine-invariant MCMC.
* [windML](https://github.com/cigroup-ol/windml) - A Python Framework for Wind Energy Analysis and Prediction.
* [vispy](https://github.com/vispy/vispy) - GPU-based high-performance interactive OpenGL 2D/3D data visualization library.
* [cerebro2](https://github.com/numenta/nupic.cerebro2) A web-based visualization and debugging platform for NuPIC. **[Deprecated]**
* [NuPIC Studio](https://github.com/htm-community/nupic.studio) An all-in-one NuPIC Hierarchical Temporal Memory visualization and debugging super-tool! **[Deprecated]**
* [SparklingPandas](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/sparklingpandas/sparklingpandas) Pandas on PySpark (https://github.com/josephmisiti/awesome-machine-learning/blob/master/POPS).
* [Seaborn](https://seaborn.pydata.org/) - A python visualization library based on matplotlib.
* [bqplot](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/bloomberg/bqplot) - An API for plotting in Jupyter (https://github.com/josephmisiti/awesome-machine-learning/blob/master/IPython).
* [pastalog](https://github.com/rewonc/pastalog) - Simple, realtime visualization of neural network training performance.
* [Superset](https://github.com/apache/incubator-superset) - A data exploration platform designed to be visual, intuitive, and interactive.
* [Dora](https://github.com/nathanepstein/dora) - Tools for exploratory data analysis in Python.
* [Ruffus](http://www.ruffus.org.uk) - Computation Pipeline library for python.
* [SOMPY](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/sevamoo/SOMPY) - Self Organizing Map written in Python (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Uses neural networks for data analysis).
* [somoclu](https://github.com/peterwittek/somoclu) Massively parallel self-organizing maps: accelerate training on multicore CPUs, GPUs, and clusters, has python API.
* [HDBScan](https://github.com/lmcinnes/hdbscan) - implementation of the hdbscan algorithm in Python - used for clustering
* [visualize_ML](https://github.com/ayush1997/visualize_ML) - A python package for data exploration and data analysis. **[Deprecated]**
* [scikit-plot](https://github.com/reiinakano/scikit-plot) - A visualization library for quick and easy generation of common plots in data analysis and machine learning.
* [Bowtie](https://github.com/jwkvam/bowtie) - A dashboard library for interactive visualizations using flask socketio and react.
* [lime](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/marcotcr/lime) - Lime is about explaining what machine learning classifiers (https://github.com/josephmisiti/awesome-machine-learning/blob/master/or models) are doing. It is able to explain any black box classifier, with two or more classes.
* [PyCM](https://github.com/sepandhaghighi/pycm) - PyCM is a multi-class confusion matrix library written in Python that supports both input data vectors and direct matrix, and a proper tool for post-classification model evaluation that supports most classes and overall statistics parameters
* [Dash](https://github.com/plotly/dash) - A framework for creating analytical web applications built on top of Plotly.js, React, and Flask
* [Lambdo](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/asavinov/lambdo) - A workflow engine for solving machine learning problems by combining in one analysis pipeline (https://github.com/josephmisiti/awesome-machine-learning/blob/master/i) feature engineering and machine learning (https://github.com/josephmisiti/awesome-machine-learning/blob/master/ii) model training and prediction (https://github.com/josephmisiti/awesome-machine-learning/blob/master/iii) table population and column evaluation via user-defined (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Python) functions.

<a name="python-misc"></a>
#### Misc Scripts / iPython Notebooks / Codebases
* [Map/Reduce implementations of common ML algorithms](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/Yannael/BigDataAnalytics_INFOH515): Jupyter notebooks that cover how to implement from scratch different ML algorithms (https://github.com/josephmisiti/awesome-machine-learning/blob/master/ordinary least squares, gradient descent, k-means, alternating least squares), using Python NumPy, and how to then make these implementations scalable using Map/Reduce and Spark. 
* [BioPy](https://github.com/jaredthecoder/BioPy) - Biologically-Inspired and Machine Learning Algorithms in Python. **[Deprecated]**
* [SVM Explorer](https://github.com/plotly/dash-svm) - Interactive SVM Explorer, using Dash and scikit-learn
* [pattern_classification](https://github.com/rasbt/pattern_classification)
* [thinking stats 2](https://github.com/Wavelets/ThinkStats2)
* [hyperopt](https://github.com/hyperopt/hyperopt-sklearn)
* [numpic](https://github.com/numenta/nupic)
* [2012-paper-diginorm](https://github.com/dib-lab/2012-paper-diginorm)
* [A gallery of interesting IPython notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
* [ipython-notebooks](https://github.com/ogrisel/notebooks)
* [data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) - Continually updated Data Science Python Notebooks: Spark, Hadoop MapReduce, HDFS, AWS, Kaggle, scikit-learn, matplotlib, pandas, NumPy, SciPy, and various command lines.
* [decision-weights](https://github.com/CamDavidsonPilon/decision-weights)
* [Sarah Palin LDA](https://github.com/Wavelets/sarah-palin-lda) - Topic Modeling the Sarah Palin emails.
* [Diffusion Segmentation](https://github.com/Wavelets/diffusion-segmentation) - A collection of image segmentation algorithms based on diffusion methods.
* [Scipy Tutorials](https://github.com/Wavelets/scipy-tutorials) - SciPy tutorials. This is outdated, check out scipy-lecture-notes.
* [Crab](https://github.com/marcelcaraciolo/crab) - A recommendation engine library for Python.
* [BayesPy](https://github.com/maxsklar/BayesPy) - Bayesian Inference Tools in Python.
* [scikit-learn tutorials](https://github.com/GaelVaroquaux/scikit-learn-tutorial) - Series of notebooks for learning scikit-learn.
* [sentiment-analyzer](https://github.com/madhusudancs/sentiment-analyzer) - Tweets Sentiment Analyzer
* [sentiment_classifier](https://github.com/kevincobain2000/sentiment_classifier) - Sentiment classifier using word sense disambiguation.
* [group-lasso](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/fabianp/group_lasso) - Some experiments with the coordinate descent algorithm used in the (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Sparse) Group Lasso model.
* [jProcessing](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/kevincobain2000/jProcessing) - Kanji / Hiragana / Katakana to Romaji Converter. Edict Dictionary & parallel sentences Search. Sentence Similarity between two JP Sentences. Sentiment Analysis of Japanese Text. Run Cabocha(https://github.com/josephmisiti/awesome-machine-learning/blob/master/ISO--8859-1 configured) in Python.
* [mne-python-notebooks](https://github.com/mne-tools/mne-python-notebooks) - IPython notebooks for EEG/MEG data processing using mne-python.
* [Neon Course](https://github.com/NervanaSystems/neon_course) - IPython notebooks for a complete course around understanding Nervana's Neon.
* [pandas cookbook](https://github.com/jvns/pandas-cookbook) - Recipes for using Python's pandas library.
* [climin](https://github.com/BRML/climin) - Optimization library focused on machine learning, pythonic implementations of gradient descent, LBFGS, rmsprop, adadelta and others.
* [Allen Downey’s Data Science Course](https://github.com/AllenDowney/DataScience) - Code for Data Science at Olin College, Spring 2014.
* [Allen Downey’s Think Bayes Code](https://github.com/AllenDowney/ThinkBayes) - Code repository for Think Bayes.
* [Allen Downey’s Think Complexity Code](https://github.com/AllenDowney/ThinkComplexity) - Code for Allen Downey's book Think Complexity.
* [Allen Downey’s Think OS Code](https://github.com/AllenDowney/ThinkOS) - Text and supporting code for Think OS: A Brief Introduction to Operating Systems.
* [Python Programming for the Humanities](https://www.karsdorp.io/python-course/) - Course for Python programming for the Humanities, assuming no prior knowledge. Heavy focus on text processing / NLP.
* [GreatCircle](https://github.com/mwgg/GreatCircle) - Library for calculating great circle distance.
* [Optunity examples](http://optunity.readthedocs.io/en/latest/notebooks/index.html) - Examples demonstrating how to use Optunity in synergy with machine learning libraries.
* [Dive into Machine Learning  with Python Jupyter notebook and scikit-learn](https://github.com/hangtwenty/dive-into-machine-learning) - "I learned Python by hacking first, and getting serious *later.* I wanted to do this with Machine Learning. If this is your style, join me in getting a bit ahead of yourself."
* [TDB](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/ericjang/tdb) - TensorDebugger (https://github.com/josephmisiti/awesome-machine-learning/blob/master/TDB) is a visual debugger for deep learning. It features interactive, node-by-node debugging and visualization for TensorFlow.
* [Suiron](https://github.com/kendricktan/suiron/) - Machine Learning for RC Cars.
* [Introduction to machine learning with scikit-learn](https://github.com/justmarkham/scikit-learn-videos) - IPython notebooks from Data School's video tutorials on scikit-learn.
* [Practical XGBoost in Python](https://parrotprediction.teachable.com/p/practical-xgboost-in-python) - comprehensive online course about using XGBoost in Python.
* [Introduction to Machine Learning with Python](https://github.com/amueller/introduction_to_ml_with_python) - Notebooks and code for the book "Introduction to Machine Learning with Python"
* [Pydata book](https://github.com/wesm/pydata-book) - Materials and IPython notebooks for "Python for Data Analysis" by Wes McKinney, published by O'Reilly Media
* [Homemade Machine Learning](https://github.com/trekhleb/homemade-machine-learning) - Python examples of popular machine learning algorithms with interactive Jupyter demos and math being explained

<a name="python-neural-networks"></a>
#### Neural Networks
* [NeuralTalk](https://github.com/karpathy/neuraltalk2) - NeuralTalk is a Python+numpy project for learning Multimodal Recurrent Neural Networks that describe images with sentences. **[Deprecated]**
* [Neuron](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/molcik/python-neuron) - Neuron is simple class for time series predictions. It's utilize LNU (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Linear Neural Unit), QNU (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Quadratic Neural Unit), RBF (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Radial Basis Function), MLP (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Multi Layer Perceptron), MLP-ELM (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Multi Layer Perceptron - Extreme Learning Machine) neural networks learned with Gradient descent or LeLevenberg–Marquardt algorithm. **[Deprecated]**
* [Data Driven Code](https://github.com/atmb4u/data-driven-code) - Very simple implementation of neural networks for dummies in python without using any libraries, with detailed comments.

<a name="python-kaggle"></a>
#### Kaggle Competition Source Code
* [open-solution-home-credit](https://github.com/neptune-ml/open-solution-home-credit) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Home-Credit-Default-Risk) for [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk).
* [open-solution-googleai-object-detection](https://github.com/neptune-ml/open-solution-googleai-object-detection) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Google-AI-Object-Detection-Challenge) for [Google AI Open Images - Object Detection Track](https://www.kaggle.com/c/google-ai-open-images-object-detection-track).
* [open-solution-salt-identification](https://github.com/neptune-ml/open-solution-salt-identification) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Salt-Detection) for [TGS Salt Identification Challenge](https://www.kaggle.com/c/tgs-salt-identification-challenge).
* [open-solution-ship-detection](https://github.com/neptune-ml/open-solution-ship-detection) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Ships) for [Airbus Ship Detection Challenge](https://www.kaggle.com/c/airbus-ship-detection).
* [open-solution-data-science-bowl-2018](https://github.com/neptune-ml/open-solution-data-science-bowl-2018) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Data-Science-Bowl-2018) for [2018 Data Science Bowl](https://www.kaggle.com/c/data-science-bowl-2018).
* [open-solution-value-prediction](https://github.com/neptune-ml/open-solution-value-prediction) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Santander-Value-Prediction-Challenge) for [Santander Value Prediction Challenge](https://www.kaggle.com/c/santander-value-prediction-challenge).
* [open-solution-toxic-comments](https://github.com/neptune-ml/open-solution-toxic-comments) -> source code for [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge).
* [wiki challenge](https://github.com/hammer/wikichallenge) - An implementation of Dell Zhang's solution to Wikipedia's Participation Challenge on Kaggle.
* [kaggle insults](https://github.com/amueller/kaggle_insults) - Kaggle Submission for "Detecting Insults in Social Commentary".
* [kaggle_acquire-valued-shoppers-challenge](https://github.com/MLWave/kaggle_acquire-valued-shoppers-challenge) - Code for the Kaggle acquire valued shoppers challenge.
* [kaggle-cifar](https://github.com/zygmuntz/kaggle-cifar) - Code for the CIFAR-10 competition at Kaggle, uses cuda-convnet.
* [kaggle-blackbox](https://github.com/zygmuntz/kaggle-blackbox) - Deep learning made easy.
* [kaggle-accelerometer](https://github.com/zygmuntz/kaggle-accelerometer) - Code for Accelerometer Biometric Competition at Kaggle.
* [kaggle-advertised-salaries](https://github.com/zygmuntz/kaggle-advertised-salaries) - Predicting job salaries from ads - a Kaggle competition.
* [kaggle amazon](https://github.com/zygmuntz/kaggle-amazon) - Amazon access control challenge.
* [kaggle-bestbuy_big](https://github.com/zygmuntz/kaggle-bestbuy_big) - Code for the Best Buy competition at Kaggle.
* [kaggle-bestbuy_small](https://github.com/zygmuntz/kaggle-bestbuy_small)
* [Kaggle Dogs vs. Cats](https://github.com/kastnerkyle/kaggle-dogs-vs-cats) - Code for Kaggle Dogs vs. Cats competition.
* [Kaggle Galaxy Challenge](https://github.com/benanne/kaggle-galaxies) - Winning solution for the Galaxy Challenge on Kaggle.
* [Kaggle Gender](https://github.com/zygmuntz/kaggle-gender) - A Kaggle competition: discriminate gender based on handwriting.
* [Kaggle Merck](https://github.com/zygmuntz/kaggle-merck) - Merck challenge at Kaggle.
* [Kaggle Stackoverflow](https://github.com/zygmuntz/kaggle-stackoverflow) - Predicting closed questions on Stack Overflow.
* [kaggle_acquire-valued-shoppers-challenge](https://github.com/MLWave/kaggle_acquire-valued-shoppers-challenge) - Code for the Kaggle acquire valued shoppers challenge.
* [wine-quality](https://github.com/zygmuntz/wine-quality) - Predicting wine quality.

<a name="python-reinforcement-learning"></a>
#### Reinforcement Learning
* [DeepMind Lab](https://github.com/deepmind/lab) - DeepMind Lab is a 3D learning environment based on id Software's Quake III Arena via ioquake3 and other open source software. Its primary purpose is to act as a testbed for research in artificial intelligence, especially deep reinforcement learning.
* [Gym](https://github.com/openai/gym) - OpenAI Gym is a toolkit for developing and comparing reinforcement learning algorithms.
* [Serpent.AI](https://github.com/SerpentAI/SerpentAI) - Serpent.AI is a game agent framework that allows you to turn any video game you own into a sandbox to develop AI and machine learning experiments. For both researchers and hobbyists. 
* [ViZDoom](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/mwydmuch/ViZDoom) - ViZDoom allows developing AI bots that play Doom using only the visual information (https://github.com/josephmisiti/awesome-machine-learning/blob/master/the screen buffer). It is primarily intended for research in machine visual learning, and deep reinforcement learning, in particular.
* [Roboschool](https://github.com/openai/roboschool) - Open-source software for robot simulation, integrated with OpenAI Gym.
* [Retro](https://github.com/openai/retro) - Retro Games in Gym
* [SLM Lab](https://github.com/kengz/SLM-Lab) - Modular Deep Reinforcement Learning framework in PyTorch.
* [Coach](https://github.com/NervanaSystems/coach) - Reinforcement Learning Coach by Intel® AI Lab enables easy experimentation with state of the art Reinforcement Learning algorithms

<a name="ruby"></a>
## Ruby

<a name="ruby-nlp"></a>
#### Natural Language Processing

* [Awesome NLP with Ruby](https://github.com/arbox/nlp-with-ruby) - Curated link list for practical natural language processing in Ruby.
* [Treat](https://github.com/louismullie/treat) - Text REtrieval and Annotation Toolkit, definitely the most comprehensive toolkit I’ve encountered so far for Ruby.
* [Stemmer](https://github.com/aurelian/ruby-stemmer) - Expose libstemmer_c to Ruby. **[Deprecated]**
* [Raspel](https://sourceforge.net/projects/raspell/) - raspell is an interface binding for ruby. **[Deprecated]**
* [UEA Stemmer](https://github.com/ealdent/uea-stemmer) - Ruby port of UEALite Stemmer - a conservative stemmer for search and indexing.
* [Twitter-text-rb](https://github.com/twitter/twitter-text/tree/master/rb) - A library that does auto linking and extraction of usernames, lists and hashtags in tweets.

<a name="ruby-general-purpose"></a>
#### General-Purpose Machine Learning

* [Awesome Machine Learning with Ruby](https://github.com/arbox/machine-learning-with-ruby) - Curated list of ML related resources for Ruby.
* [Ruby Machine Learning](https://github.com/tsycho/ruby-machine-learning) - Some Machine Learning algorithms, implemented in Ruby. **[Deprecated]**
* [Machine Learning Ruby](https://github.com/mizoR/machine-learning-ruby) **[Deprecated]**
* [jRuby Mahout](https://github.com/vasinov/jruby_mahout) - JRuby Mahout is a gem that unleashes the power of Apache Mahout in the world of JRuby. **[Deprecated]**
* [CardMagic-Classifier](https://github.com/cardmagic/classifier) - A general classifier module to allow Bayesian and other types of classifications.
* [rb-libsvm](https://github.com/febeling/rb-libsvm) - Ruby language bindings for LIBSVM which is a Library for Support Vector Machines.
* [Scoruby](https://github.com/asafschers/scoruby) - Creates Random Forest classifiers from PMML files.

<a name="ruby-data-analysis"></a>
#### Data Analysis / Data Visualization

* [rsruby](https://github.com/alexgutteridge/rsruby) - Ruby - R bridge.
* [ruby-plot](https://www.ruby-toolbox.com/projects/ruby-plot) - gnuplot wrapper for Ruby, especially for plotting ROC curves into SVG files. **[Deprecated]**
* [plot-rb](https://github.com/zuhao/plotrb) - A plotting library in Ruby built on top of Vega and D3. **[Deprecated]**
* [scruffy](https://github.com/delano/scruffy) - A beautiful graphing toolkit for Ruby.
* [SciRuby](http://sciruby.com/)
* [Glean](https://github.com/glean/glean) - A data management tool for humans. **[Deprecated]**
* [Bioruby](https://github.com/bioruby/bioruby)
* [Arel](https://github.com/nkallen/arel) **[Deprecated]**

<a name="ruby-misc"></a>
#### Misc

* [Big Data For Chimps](https://github.com/infochimps-labs/big_data_for_chimps)
* [Listof](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/kevincobain2000/listof) - Community based data collection, packed in gem. Get list of pretty much anything (https://github.com/josephmisiti/awesome-machine-learning/blob/master/stop words, countries, non words) in txt, json or hash. [Demo/Search for a list](https://github.com/josephmisiti/awesome-machine-learning/blob/master/http://kevincobain2000.github.io/listof/)


<a name="rust"></a>
## Rust

<a name="rust-general-purpose"></a>
#### General-Purpose Machine Learning
* [deeplearn-rs](https://github.com/tedsta/deeplearn-rs) - deeplearn-rs provides simple networks that use matrix multiplication, addition, and ReLU under the MIT license.
* [rustlearn](https://github.com/maciejkula/rustlearn) - a machine learning framework featuring logistic regression, support vector machines, decision trees and random forests.
* [rusty-machine](https://github.com/AtheMathmo/rusty-machine) - a pure-rust machine learning library.
* [leaf](https://github.com/autumnai/leaf) - open source framework for machine intelligence, sharing concepts from TensorFlow and Caffe. Available under the MIT license. [**[Deprecated]**](https://medium.com/@mjhirn/tensorflow-wins-89b78b29aafb#.s0a3uy4cc)
* [RustNN](https://github.com/jackm321/RustNN) - RustNN is a feedforward neural network library. **[Deprecated]**
* [RusticSOM](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/avinashshenoy97/RusticSOM) - A Rust library for Self Organising Maps (https://github.com/josephmisiti/awesome-machine-learning/blob/master/SOM).


<a name="r"></a>
## R

<a name="r-general-purpose"></a>
#### General-Purpose Machine Learning

* [ahaz](https://cran.r-project.org/web/packages/ahaz/index.html) - ahaz: Regularization for semiparametric additive hazards regression. **[Deprecated]**
* [arules](https://cran.r-project.org/web/packages/arules/index.html) - arules: Mining Association Rules and Frequent Itemsets
* [biglasso](https://cran.r-project.org/web/packages/biglasso/index.html) - biglasso: Extending Lasso Model Fitting to Big Data in R.
* [bmrm](https://cran.r-project.org/web/packages/bmrm/index.html) - bmrm: Bundle Methods for Regularized Risk Minimization Package.
* [Boruta](https://cran.r-project.org/web/packages/Boruta/index.html) - Boruta: A wrapper algorithm for all-relevant feature selection.
* [bst](https://cran.r-project.org/web/packages/bst/index.html) - bst: Gradient Boosting.
* [C50](https://cran.r-project.org/web/packages/C50/index.html) - C50: C5.0 Decision Trees and Rule-Based Models.
* [caret](https://topepo.github.io/caret/index.html) - Classification and Regression Training: Unified interface to ~150 ML algorithms in R.
* [caretEnsemble](https://cran.r-project.org/web/packages/caretEnsemble/index.html) - caretEnsemble: Framework for fitting multiple caret models as well as creating ensembles of such models. **[Deprecated]**
* [CatBoost](https://github.com/catboost/catboost) - General purpose gradient boosting on decision trees library with categorical features support out of the box for R.
* [Clever Algorithms For Machine Learning](https://machinelearningmastery.com/)
* [CORElearn](https://cran.r-project.org/web/packages/CORElearn/index.html) - CORElearn: Classification, regression, feature evaluation and ordinal evaluation.
* [CoxBoost](https://cran.r-project.org/web/packages/CoxBoost/index.html) - CoxBoost: Cox models by likelihood based boosting for a single survival endpoint or competing risks **[Deprecated]**
* [Cubist](https://cran.r-project.org/web/packages/Cubist/index.html) - Cubist: Rule- and Instance-Based Regression Modeling.
* [e1071](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://cran.r-project.org/web/packages/e1071/index.html) - e1071: Misc Functions of the Department of Statistics (https://github.com/josephmisiti/awesome-machine-learning/blob/master/e1071), TU Wien
* [earth](https://cran.r-project.org/web/packages/earth/index.html) - earth: Multivariate Adaptive Regression Spline Models
* [elasticnet](https://cran.r-project.org/web/packages/elasticnet/index.html) - elasticnet: Elastic-Net for Sparse Estimation and Sparse PCA.
* [ElemStatLearn](https://cran.r-project.org/web/packages/ElemStatLearn/index.html) - ElemStatLearn: Data sets, functions and examples from the book: "The Elements of Statistical Learning, Data Mining, Inference, and Prediction" by Trevor Hastie, Robert Tibshirani and Jerome Friedman Prediction" by Trevor Hastie, Robert Tibshirani and Jerome Friedman.
* [evtree](https://cran.r-project.org/web/packages/evtree/index.html) - evtree: Evolutionary Learning of Globally Optimal Trees.
* [forecast](https://cran.r-project.org/web/packages/forecast/index.html) - forecast: Timeseries forecasting using ARIMA, ETS, STLM, TBATS, and neural network models.
* [forecastHybrid](https://cran.r-project.org/web/packages/forecastHybrid/index.html) - forecastHybrid: Automatic ensemble and cross validation of ARIMA, ETS, STLM, TBATS, and neural network models from the "forecast" package.
* [fpc](https://cran.r-project.org/web/packages/fpc/index.html) - fpc: Flexible procedures for clustering.
* [frbs](https://cran.r-project.org/web/packages/frbs/index.html) - frbs: Fuzzy Rule-based Systems for Classification and Regression Tasks. **[Deprecated]**
* [GAMBoost](https://cran.r-project.org/web/packages/GAMBoost/index.html) - GAMBoost: Generalized linear and additive models by likelihood based boosting. **[Deprecated]**
* [gamboostLSS](https://cran.r-project.org/web/packages/gamboostLSS/index.html) - gamboostLSS: Boosting Methods for GAMLSS.
* [gbm](https://cran.r-project.org/web/packages/gbm/index.html) - gbm: Generalized Boosted Regression Models.
* [glmnet](https://cran.r-project.org/web/packages/glmnet/index.html) - glmnet: Lasso and elastic-net regularized generalized linear models.
* [glmpath](https://cran.r-project.org/web/packages/glmpath/index.html) - glmpath: L1 Regularization Path for Generalized Linear Models and Cox Proportional Hazards Model.
* [GMMBoost](https://cran.r-project.org/web/packages/GMMBoost/index.html) - GMMBoost: Likelihood-based Boosting for Generalized mixed models. **[Deprecated]**
* [grplasso](https://cran.r-project.org/web/packages/grplasso/index.html) - grplasso: Fitting user specified models with Group Lasso penalty.
* [grpreg](https://cran.r-project.org/web/packages/grpreg/index.html) - grpreg: Regularization paths for regression models with grouped covariates.
* [h2o](https://cran.r-project.org/web/packages/h2o/index.html) - A framework for fast, parallel, and distributed machine learning algorithms at scale -- Deeplearning, Random forests, GBM, KMeans, PCA, GLM.
* [hda](https://cran.r-project.org/web/packages/hda/index.html) - hda: Heteroscedastic Discriminant Analysis. **[Deprecated]**
* [Introduction to Statistical Learning](https://www-bcf.usc.edu/~gareth/ISL/)
* [ipred](https://cran.r-project.org/web/packages/ipred/index.html) - ipred: Improved Predictors.
* [kernlab](https://cran.r-project.org/web/packages/kernlab/index.html) - kernlab: Kernel-based Machine Learning Lab.
* [klaR](https://cran.r-project.org/web/packages/klaR/index.html) - klaR: Classification and visualization.
* [L0Learn](https://cran.r-project.org/web/packages/L0Learn/index.html) - L0Learn: Fast algorithms for best subset selection.
* [lars](https://cran.r-project.org/web/packages/lars/index.html) - lars: Least Angle Regression, Lasso and Forward Stagewise. **[Deprecated]**
* [lasso2](https://cran.r-project.org/web/packages/lasso2/index.html) - lasso2: L1 constrained estimation aka ‘lasso’.
* [LiblineaR](https://cran.r-project.org/web/packages/LiblineaR/index.html) - LiblineaR: Linear Predictive Models Based On The Liblinear C/C++ Library.
* [LogicReg](https://cran.r-project.org/web/packages/LogicReg/index.html) - LogicReg: Logic Regression.
* [Machine Learning For Hackers](https://github.com/johnmyleswhite/ML_for_Hackers)
* [maptree](https://cran.r-project.org/web/packages/maptree/index.html) - maptree: Mapping, pruning, and graphing tree models. **[Deprecated]**
* [mboost](https://cran.r-project.org/web/packages/mboost/index.html) - mboost: Model-Based Boosting.
* [medley](https://www.kaggle.com/general/3661) - medley: Blending regression models, using a greedy stepwise approach.
* [mlr](https://cran.r-project.org/web/packages/mlr/index.html) - mlr: Machine Learning in R.
* [ncvreg](https://cran.r-project.org/web/packages/ncvreg/index.html) - ncvreg: Regularization paths for SCAD- and MCP-penalized regression models.
* [nnet](https://cran.r-project.org/web/packages/nnet/index.html) - nnet: Feed-forward Neural Networks and Multinomial Log-Linear Models. **[Deprecated]**
* [pamr](https://cran.r-project.org/web/packages/pamr/index.html) - pamr: Pam: prediction analysis for microarrays. **[Deprecated]**
* [party](https://cran.r-project.org/web/packages/party/index.html) - party: A Laboratory for Recursive Partytioning.
* [partykit](https://cran.r-project.org/web/packages/partykit/index.html) - partykit: A Toolkit for Recursive Partytioning.
* [penalized](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://cran.r-project.org/web/packages/penalized/index.html) - penalized: L1 (https://github.com/josephmisiti/awesome-machine-learning/blob/master/lasso and fused lasso) and L2 (https://github.com/josephmisiti/awesome-machine-learning/blob/master/ridge) penalized estimation in GLMs and in the Cox model.
* [penalizedLDA](https://cran.r-project.org/web/packages/penalizedLDA/index.html) - penalizedLDA: Penalized classification using Fisher's linear discriminant. **[Deprecated]**
* [penalizedSVM](https://cran.r-project.org/web/packages/penalizedSVM/index.html) - penalizedSVM: Feature Selection SVM using penalty functions.
* [quantregForest](https://cran.r-project.org/web/packages/quantregForest/index.html) - quantregForest: Quantile Regression Forests.
* [randomForest](https://cran.r-project.org/web/packages/randomForest/index.html) - randomForest: Breiman and Cutler's random forests for classification and regression.
* [randomForestSRC](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://cran.r-project.org/web/packages/randomForestSRC/index.html) - randomForestSRC: Random Forests for Survival, Regression and Classification (https://github.com/josephmisiti/awesome-machine-learning/blob/master/RF-SRC).
* [rattle](https://cran.r-project.org/web/packages/rattle/index.html) - rattle: Graphical user interface for data mining in R.
* [rda](https://cran.r-project.org/web/packages/rda/index.html) - rda: Shrunken Centroids Regularized Discriminant Analysis.
* [rdetools](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://cran.r-project.org/web/packages/rdetools/index.html) - rdetools: Relevant Dimension Estimation (https://github.com/josephmisiti/awesome-machine-learning/blob/master/RDE) in Feature Spaces. **[Deprecated]**
* [REEMtree](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://cran.r-project.org/web/packages/REEMtree/index.html) - REEMtree: Regression Trees with Random Effects for Longitudinal (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Panel) Data. **[Deprecated]**
* [relaxo](https://cran.r-project.org/web/packages/relaxo/index.html) - relaxo: Relaxed Lasso. **[Deprecated]**
* [rgenoud](https://cran.r-project.org/web/packages/rgenoud/index.html) - rgenoud: R version of GENetic Optimization Using Derivatives
* [Rmalschains](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://cran.r-project.org/web/packages/Rmalschains/index.html) - Rmalschains: Continuous Optimization using Memetic Algorithms with Local Search Chains (https://github.com/josephmisiti/awesome-machine-learning/blob/master/MA-LS-Chains) in R.
* [rminer](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://cran.r-project.org/web/packages/rminer/index.html) - rminer: Simpler use of data mining methods (https://github.com/josephmisiti/awesome-machine-learning/blob/master/e.g. NN and SVM) in classification and regression. **[Deprecated]**
* [ROCR](https://cran.r-project.org/web/packages/ROCR/index.html) - ROCR: Visualizing the performance of scoring classifiers. **[Deprecated]**
* [RoughSets](https://cran.r-project.org/web/packages/RoughSets/index.html) - RoughSets: Data Analysis Using Rough Set and Fuzzy Rough Set Theories. **[Deprecated]**
* [rpart](https://cran.r-project.org/web/packages/rpart/index.html) - rpart: Recursive Partitioning and Regression Trees.
* [RPMM](https://cran.r-project.org/web/packages/RPMM/index.html) - RPMM: Recursively Partitioned Mixture Model.
* [RSNNS](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://cran.r-project.org/web/packages/RSNNS/index.html) - RSNNS: Neural Networks in R using the Stuttgart Neural Network Simulator (https://github.com/josephmisiti/awesome-machine-learning/blob/master/SNNS).
* [RWeka](https://cran.r-project.org/web/packages/RWeka/index.html) - RWeka: R/Weka interface.
* [RXshrink](https://cran.r-project.org/web/packages/RXshrink/index.html) - RXshrink: Maximum Likelihood Shrinkage via Generalized Ridge or Least Angle Regression.
* [sda](https://cran.r-project.org/web/packages/sda/index.html) - sda: Shrinkage Discriminant Analysis and CAT Score Variable Selection. **[Deprecated]**
* [SuperLearner](https://github.com/ecpolley/SuperLearner) - Multi-algorithm ensemble learning packages.
* [svmpath](https://cran.r-project.org/web/packages/svmpath/index.html) - svmpath: svmpath: the SVM Path algorithm. **[Deprecated]**
* [tgp](https://cran.r-project.org/web/packages/tgp/index.html) - tgp: Bayesian treed Gaussian process models. **[Deprecated]**
* [tree](https://cran.r-project.org/web/packages/tree/index.html) - tree: Classification and regression trees.
* [varSelRF](https://cran.r-project.org/web/packages/varSelRF/index.html) - varSelRF: Variable selection using random forests.
* [XGBoost.R](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/tqchen/xgboost/tree/master/R-package) - R binding for eXtreme Gradient Boosting (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Tree) Library.
* [Optunity](https://optunity.readthedocs.io/en/latest/) - A library dedicated to automated hyperparameter optimization with a simple, lightweight API to facilitate drop-in replacement of grid search. Optunity is written in Python but interfaces seamlessly to R.
* [igraph](https://igraph.org/r/) - binding to igraph library - General purpose graph library.
* [MXNet](https://github.com/apache/incubator-mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more.
* [TDSP-Utilities](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/Azure/Azure-TDSP-Utilities) - Two data science utilities in R from Microsoft: 1) Interactive Data Exploration, Analysis, and Reporting (https://github.com/josephmisiti/awesome-machine-learning/blob/master/IDEAR) ; 2) Automated Modeling and Reporting (https://github.com/josephmisiti/awesome-machine-learning/blob/master/AMR).

<a name="r-data-analysis"></a>
#### Data Analysis / Data Visualization

* [ggplot2](https://ggplot2.tidyverse.org/) - A data visualization package based on the grammar of graphics.
* [tmap](https://cran.r-project.org/web/packages/tmap/vignettes/tmap-getstarted.html) for visualizing geospatial data with static maps and [leaflet](https://rstudio.github.io/leaflet/) for interactive maps
* [tm](https://www.rdocumentation.org/packages/tm/) and [quanteda](https://quanteda.io/) are the main packages for managing,  analyzing, and visualizing textual data.
* [shiny](https://shiny.rstudio.com/) is the basis for truly interactive displays and dashboards in R. However, some measure of interactivity can be achieved with [htmlwidgets](https://www.htmlwidgets.org/) bringing javascript libraries to R. These include, [plotly](https://plot.ly/r/), [dygraphs](http://rstudio.github.io/dygraphs), [highcharter](http://jkunst.com/highcharter/), and several others.

<a name="sas"></a>
## SAS

<a name="sas-general-purpose"></a>
#### General-Purpose Machine Learning

* [Visual Data Mining and Machine Learning](https://www.sas.com/en_us/software/visual-data-mining-machine-learning.html) - Interactive, automated, and programmatic modeling with the latest machine learning algorithms in and end-to-end analytics environment, from data prep to deployment. Free trial available.
* [Enterprise Miner](https://www.sas.com/en_us/software/enterprise-miner.html) - Data mining and machine learning that creates deployable models using a GUI or code.
* [Factory Miner](https://www.sas.com/en_us/software/factory-miner.html) - Automatically creates deployable machine learning models across numerous market or customer segments using a GUI.

<a name="sas-data-analysis"></a>
#### Data Analysis / Data Visualization

* [SAS/STAT](https://www.sas.com/en_us/software/stat.html) - For conducting advanced statistical analysis.
* [University Edition](https://www.sas.com/en_us/software/university-edition.html) - FREE! Includes all SAS packages necessary for data analysis and visualization, and includes online SAS courses.

<a name="sas-nlp"></a>
#### Natural Language Processing

* [Contextual Analysis](https://www.sas.com/en_us/software/contextual-analysis.html) - Add structure to unstructured text using a GUI.
* [Sentiment Analysis](https://www.sas.com/en_us/software/sentiment-analysis.html) - Extract sentiment from text using a GUI.
* [Text Miner](https://www.sas.com/en_us/software/text-miner.html) - Text mining using a GUI or code.

<a name="sas-demos"></a>
#### Demos and Scripts

* [ML_Tables](https://github.com/sassoftware/enlighten-apply/tree/master/ML_tables) - Concise cheat sheets containing machine learning best practices.
* [enlighten-apply](https://github.com/sassoftware/enlighten-apply) - Example code and materials that illustrate applications of SAS machine learning techniques.
* [enlighten-integration](https://github.com/sassoftware/enlighten-integration) - Example code and materials that illustrate techniques for integrating SAS with other analytics technologies in Java, PMML, Python and R.
* [enlighten-deep](https://github.com/sassoftware/enlighten-deep) - Example code and materials that illustrate using neural networks with several hidden layers in SAS.
* [dm-flow](https://github.com/sassoftware/dm-flow) - Library of SAS Enterprise Miner process flow diagrams to help you learn by example about specific data mining topics.


<a name="scala"></a>
## Scala

<a name="scala-nlp"></a>
#### Natural Language Processing

* [ScalaNLP](http://www.scalanlp.org/) - ScalaNLP is a suite of machine learning and numerical computing libraries.
* [Breeze](https://github.com/scalanlp/breeze) - Breeze is a numerical processing library for Scala.
* [Chalk](https://github.com/scalanlp/chalk) - Chalk is a natural language processing library. **[Deprecated]**
* [FACTORIE](https://github.com/factorie/factorie) - FACTORIE is a toolkit for deployable probabilistic modeling, implemented as a software library in Scala. It provides its users with a succinct language for creating relational factor graphs, estimating parameters and performing inference.
* [Montague](https://github.com/Workday/upshot-montague) - Montague is a semantic parsing library for Scala with an easy-to-use DSL.

<a name="scala-data-analysis"></a>
#### Data Analysis / Data Visualization

* [MLlib in Apache Spark](https://spark.apache.org/docs/latest/mllib-guide.html) - Distributed machine learning library in Spark
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - a service for deployment Apache Spark MLLib machine learning models as realtime, batch or reactive web services.
* [Scalding](https://github.com/twitter/scalding) - A Scala API for Cascading.
* [Summing Bird](https://github.com/twitter/summingbird) - Streaming MapReduce with Scalding and Storm.
* [Algebird](https://github.com/twitter/algebird) - Abstract Algebra for Scala.
* [xerial](https://github.com/xerial/xerial) - Data management utilities for Scala. **[Deprecated]**
* [PredictionIO](https://github.com/apache/predictionio) - PredictionIO, a machine learning server for software developers and data engineers.
* [BIDMat](https://github.com/BIDData/BIDMat) - CPU and GPU-accelerated matrix library intended to support large-scale exploratory data analysis.
* [Flink](https://flink.apache.org/) - Open source platform for distributed stream and batch data processing.
* [Spark Notebook](http://spark-notebook.io) - Interactive and Reactive Data Science using Scala and Spark.

<a name="scala-general-purpose"></a>
#### General-Purpose Machine Learning

* [DeepLearning.scala](https://deeplearning.thoughtworks.school/) - Creating statically typed dynamic neural networks from object-oriented & functional programming constructs.
* [Conjecture](https://github.com/etsy/Conjecture) - Scalable Machine Learning in Scalding.
* [brushfire](https://github.com/stripe/brushfire) - Distributed decision tree ensemble learning in Scala.
* [ganitha](https://github.com/tresata/ganitha) - Scalding powered machine learning. **[Deprecated]**
* [adam](https://github.com/bigdatagenomics/adam) - A genomics processing engine and specialized file format built using Apache Avro, Apache Spark and Parquet. Apache 2 licensed.
* [bioscala](https://github.com/bioscala/bioscala) - Bioinformatics for the Scala programming language
* [BIDMach](https://github.com/BIDData/BIDMach) - CPU and GPU-accelerated Machine Learning Library.
* [Figaro](https://github.com/p2t2/figaro) - a Scala library for constructing probabilistic models.
* [H2O Sparkling Water](https://github.com/h2oai/sparkling-water) - H2O and Spark interoperability.
* [FlinkML in Apache Flink](https://ci.apache.org/projects/flink/flink-docs-master/dev/libs/ml/index.html) - Distributed machine learning library in Flink.
* [DynaML](https://github.com/transcendent-ai-labs/DynaML) - Scala Library/REPL for Machine Learning Research.
* [Saul](https://github.com/CogComp/saul) - Flexible Declarative Learning-Based Programming.
* [SwiftLearner](https://github.com/valdanylchuk/swiftlearner/) - Simply written algorithms to help study ML or write your own implementations.
* [Smile](https://haifengl.github.io/smile/) - Statistical Machine Intelligence and Learning Engine.
* [doddle-model](https://github.com/picnicml/doddle-model) - An in-memory machine learning library built on top of Breeze. It provides immutable objects and exposes its functionality through a scikit-learn-like API.

<a name="scheme"></a>
## Scheme

<a name="scheme-neural-networks"></a>
#### Neural Networks

* [layer](https://github.com/cloudkj/layer) - Neural network inference from the command line, implemented in [CHICKEN Scheme](https://www.call-cc.org/).

<a name="swift"></a>
## Swift

<a name="swift-general-purpose"></a>
#### General-Purpose Machine Learning

* [Bender](https://github.com/xmartlabs/Bender) - Fast Neural Networks framework built on top of Metal. Supports TensorFlow models.
* [Swift AI](https://github.com/Swift-AI/Swift-AI) - Highly optimized artificial intelligence and machine learning library written in Swift.
* [BrainCore](https://github.com/alejandro-isaza/BrainCore) - The iOS and OS X neural network framework.
* [swix](https://github.com/stsievert/swix) - A bare bones library that includes a general matrix language and wraps some OpenCV for iOS development. **[Deprecated]**
* [AIToolbox](https://github.com/KevinCoble/AIToolbox) - A toolbox framework of AI modules written in Swift: Graphs/Trees, Linear Regression, Support Vector Machines, Neural Networks, PCA, KMeans, Genetic Algorithms, MDP, Mixture of Gaussians.
* [MLKit](https://github.com/Somnibyte/MLKit) - A simple Machine Learning Framework written in Swift. Currently features Simple Linear Regression, Polynomial Regression, and Ridge Regression.
* [Swift Brain](https://github.com/vlall/Swift-Brain) - The first neural network / machine learning library written in Swift. This is a project for AI algorithms in Swift for iOS and OS X development. This project includes algorithms focused on Bayes theorem, neural networks, SVMs, Matrices, etc...
* [Perfect TensorFlow](https://github.com/PerfectlySoft/Perfect-TensorFlow) - Swift Language Bindings of TensorFlow. Using native TensorFlow models on both macOS / Linux.
* [PredictionBuilder](https://github.com/denissimon/prediction-builder-swift) - A library for machine learning that builds predictions using a linear regression.
* [Awesome CoreML](https://github.com/SwiftBrain/awesome-CoreML-models) - A curated list of pretrained CoreML models.
* [Awesome Core ML Models](https://github.com/likedan/Awesome-CoreML-Models) - A curated list of machine learning models in CoreML format.

<a name="tensor"></a>
## TensorFlow

<a name="tensor-general-purpose"></a>
#### General-Purpose Machine Learning
* [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) - A list of all things related to TensorFlow.

<a name="tools"></a>
## Tools

<a name="tools-neural-networks"></a>
#### Neural Networks
* [layer](https://github.com/cloudkj/layer) - Neural network inference from the command line

<a name="tools-misc"></a>
#### Misc
* [Notebooks](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/rlan/notebooks) - A starter kit for Jupyter notebooks and machine learning. Companion docker images consist of all combinations of python versions, machine learning frameworks (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Keras, PyTorch and Tensorflow) and CPU/CUDA versions.
* [DVC](https://github.com/iterative/dvc) - Data Science Version Control is an open-source version control system for machine learning projects with pipelines support. It makes ML projects reproducible and shareable.

<a name="credits"></a>
## Credits

* Some of the python libraries were cut-and-pasted from [vinta](https://github.com/vinta/awesome-python)
* The few go reference I found where pulled from [this page](https://github.com/golang/go/wiki/Projects)com/likedan/Awesome-CoreML-Models) - A curated list of machine learning models in CoreML format.

<a name="tensor"></a>
## TensorFlow

<a name="tensor-general-purpose"></a>
#### General-Purpose Machine Learning
* [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) - A list of all things related to TensorFlow.

<a name="tools"></a>
## Tools

<a name="tools-neural-networks"></a>
#### Neural Networks
* [layer](https://github.com/cloudkj/layer) - Neural network inference from the command line

<a name="tools-misc"></a>
#### Misc
* [Notebooks](https://github.com/josephmisiti/awesome-machine-learning/blob/master/https://github.com/rlan/notebooks) - A starter kit for Jupyter notebooks and machine learning. Companion docker images consist of all combinations of python versions, machine learning frameworks (https://github.com/josephmisiti/awesome-machine-learning/blob/master/Keras, PyTorch and Tensorflow) and CPU/CUDA versions.
* [DVC](https://github.com/iterative/dvc) - Data Science Version Control is an open-source version control system for machine learning projects with pipelines support. It makes ML projects reproducible and shareable.

<a name="credits"></a>
## Credits

* Some of the python libraries were cut-and-pasted from [vinta](https://github.com/vinta/awesome-python)
* The few go reference I found where pulled from [this page](https://github.com/golang/go/wiki/Projects)