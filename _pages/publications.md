---
#layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can find my Google Scholar profile [here](https://scholar.google.com/citations?hl=en&user=RegoACcAAAAJ).

Preprints
------
**Huy Phan**, Fernando Andreotti, Navin Cooray, Oliver Y. Chén, and Maarten De Vos
__Joint Classification and Prediction CNN Framework for Automatic Sleep Stage Classification__
*arXiv Preprint arXiv:1805.06546*, 2018
[[PDF]](https://arxiv.org/pdf/1805.06546)

Journal Papers
------
Ian McLoughlin, Haomin Zhang, Zhipeng Xie, Yan Song, Wei Xiao, and **Huy Phan**
__Continuous Robust Sound Event Classification Using Time-Frequency Features and Deep Learning__
*PLoS ONE*: 12(9), Article ID e0182309, 2017
[[PDF]](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0182309)

Marco Maass, Mandy Ahlborg, Anna Bakenecker, Fabrice Katzberg, **Huy Phan**, Thorsten M. Buzug, and Alfred Mertins
__A Trajectory Study for Obtaining MPI System Matrices in a Compressed-Sensing Framework__
*International Journal on Magnetic Particle Imaging (IJMPI)*: 3(2), Article ID 1706005, 2017
[[PDF]](https://journal.iwmpi.org/index.php/iwmpi/article/view/85/117)

**Huy Phan**, Lars Hertel, Marco Maass, Philipp Koch, Radoslaw Mazur, and Alfred Mertins. __Improved Audio Scene Classification based on Label-Tree Embeddings and Convolutional Neural Networks__. *IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP)*: 25(6), pp. 1278-1290, 2017 [[PDF]](http://ieeexplore.ieee.org/document/7933052/)

Marco Maass, Klaas Bente, Mandy Ahlborg, Hanne Medimagh, **Huy Phan**, Thorsten M. Buzug, and Alfred Mertins. __Optimized Compression of MPI System Matrices Using a Symmetry-Preserving Secondary Orthogonal Transform__. *International Journal on Magnetic Particle Imaging (IJMPI)*: 2(1), Article ID 1607002, 2016 [[PDF]](https://journal.iwmpi.org/index.php/iwmpi/article/download/30/22)

**Huy Phan**, Lars Hertel, Marco Maass, Radoslaw Mazur, and Alfred Mertins. __Learning Representations for Nonspeech Audio Events through Their Similarities to Speech Patterns__. *IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP)*: 24(4), pp. 807-822, 2016 [[PDF]](http://www.isip.uni-luebeck.de/fileadmin/files/publications/phan2016b.pdf)
    
**Huy Phan**, Marco Maaß, Radoslaw Mazur, and Alfred Mertins. __Random Regression Forests for Acoustic Event Detection and Classification__. *IEEE/ACM Transactions on Audio, Speech and Language Processing (TASLP)*: 23(1), pp. 20-31, 2015 [[PDF]](http://www.isip.uni-luebeck.de/fileadmin/files/publications/phan2015_02.pdf) [[CODE]](https://github.com/pquochuy/regression_forest)

**Quoc-Huy Phan**, Su-Lim Tan, Ian McLoughlin, and Duc-Lung Vu. __A Unified Framework for GPS Code and Carrier-Phase Multipath Mitigation using Support Vector Regression__. *Advances in Artificial Neural Systems*, 2013 [[PDF]](http://downloads.hindawi.com/journals/aans/2013/240564.pdf)

**Quoc-Huy Phan**, Su-Lim Tan, and Ian McLoughlin. __GPS Multipath Mitigation: A Nonlinear Regression Approach__. *GPS Solutions*: 17(3), pp. 371-380, 2013 [[PDF]](https://www.dropbox.com/s/jti32ne6pe9hsm3/2012_MultipathRegression_GPSS_rev_2.0.pdf?dl=1)
    
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
