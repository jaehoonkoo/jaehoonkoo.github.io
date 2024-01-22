---
layout: page
title: Vita
permalink: /vita/
---

## Edutation
- [Northwestern University](https://www.mccormick.northwestern.edu/industrial/) 
  - Ph.D. in Industrial Engineering and Management Sciences, 2020
  - M.S. in Industrial Engineering and Management Sciences, 2015
- [Korea Advanced Institute of Science and Technology (KAIST)](https://ie.kaist.ac.kr/) 
  - M.S. in Industrial and Systems Engineering, 2012
- [Ajou University](https://www.ajou.ac.kr/en/index.do) 
  - B.S. in Industrial Engineering, 2010
  
<!-- - Ph.D. in Industrial Engineering and Management Sciences, [Northwestern University](https://www.mccormick.northwestern.edu/industrial/), 2020, USA 
- M.S. in Industrial Engineering and Management Sciences, [Northwestern University](https://www.mccormick.northwestern.edu/industrial/), 2015, USA
- M.S. in Industrial and Systems Engineering, [Korea Advanced Institute of Science and Technology (KAIST)](https://ie.kaist.ac.kr/), 2012, South Korea
- B.S. in Industrial Engineering, [Ajou University](https://ie.ajou.ac.kr/ie/index.do), 2010, South Korea -->

## Experience
- [Hanyang University](https://www.hanyang.ac.kr/web/eng) <font size="2">(Ansan, Gyeonggi, South Korea)</font>
  - Assistant Professor in the School of Business Administration (Sep. 2022 - present)

- [Argonne National Laboratory](https://www.anl.gov/) <font size="2">(Lemont, IL, USA)</font>
  - Postdoctoral Appointee in the Mathematics and Computer Science Division (Jul. 2020 - Jul. 2022)
    - Collaborated with plasma physicists to design a combined MLP/CNN model to reconstruct plasma equilibrium images and physical quantities; implemented using Pytorch; achieved 1000x speedup over the traditional algorithms. (Project page: EFIT-AI)
    - Developed autotuning framework to explore a tree‑like search space based on Monte Carlo tree search; obtained 3.7x speedup over the default heuristic optimizations on Exascale proxy apps; collaborated with experts on compiler optimization for HPC. [[code]](https://github.com/ytopt-team/ytopt/blob/mcts/ytopt/cmcts/README.md) [[tutorial]](https://github.com/ytopt-team/ytopt/blob/mcts/docs/tutorials/mcts-gemm/tutorial-mcts-gemm.md)
    - Designed autotuning framework for online settings based on transfer learning; provided a hands‑on tutorial. [[code]](https://github.com/ytopt-team/ytopt/tree/v0.0.3) [[tutorial]](https://github.com/ytopt-team/ytopt/blob/online/docs/tutorials/omp-xsbench-tl/tutorial-omp-xsbench-tl.md)
    - Maintained a ML based autotuning software package (Ytopt); provided tutorial examples of HPC proxy apps; available in Spack.
    - Helped X‑ray scientists by designing corrector algorithm in Tensorflow to clean noisy images from dark‑field X‑ray microscope based on a CNN for optical flow (PWC‑Net).
    - Helped materials scientists using a distributed hyperparameter search software (DeepHyper) to autotune configurations of neuromorphic computing architectures under extreme environments
- [Northwestern University](https://www.northwestern.edu/) <font size="2">(Evanston, IL, USA)</font>
  - Research Assistant (Sep. 2015 - Jun. 2020)
  - Projects with Allstate Insurance Company
    - Developed inverse classification framework for churn analysis and for mortality prediction on sequential data; implemented using Tensorflow and PuLP; successfully perturbed samples as desired achieving 17% improvements over the baseline.
    - Developed a combined model of CNN and RNN for hierarchical classification of images; implemented using Tensorflow; achieved 2.5% improvements over the conventional CNNs. [[code]](https://github.com/jaehoonkoo/h_classification)
    - Designed semi‑supervised learning framework for large‑scale image classification based on stacked what‑where auto‑encoders (CNN).
    - Helped data scientists to classify initially unlabeled images through active learning with the Siamese network (CNN) using Keras‑Tensorflow.
- Nokia Bell Labs <font size="2">(Naperville, IL, USA)</font>
  - Research Intern (Jun. 2018 - Aug. 2018)
    - Developed dynamic resource allocation framework based on deep RL for network slicing of 5G networks; collaborated with mobile network experts; achieved 29\% in loss reduction over the baseline.
- Hyundai Mobis, Hyundai Motor Group <font size="2">(Seoul, South Korea)</font>
  - Specialist (Dec. 2011 - Jan. 2013)
    - Managed supply chain of CKD products sent to Hyundai Mobis Slovakia and Czech branches.
    - Solved quality issues with engineers at car-assembly and part-manufacturing lines including domestic and overseas factories.

## Publications ([Google Scholar](https://scholar.google.com/citations?user=nabCGxoAAAAJ&hl=en))
### Refereed Journal Articles
- **J. Koo**, D. Klabjan, J. Utke, An inverse classification framework with limited budget and maximum number of perturbed samples, Expert Systems With Applications, vol. 212, 2023. [10.1016/j.eswa.2022.118761](https://doi.org/10.1016/j.eswa.2022.118761)
- L. Lao, S. Kruger, C. Akcay, P. Balaprakash, T Bechtel, E. Howell, **J. Koo**, J. Leddy, M. Leinhauser, Y. Liu, S. Madireddy, J. McClenaghan, D. Orozco, A. Pankin, D. Schissel, S. Smith, X. Sun, S. Williams, and the EFIT-AI Team, Application of Machine Learning and Artificial Intelligence to Extend EFIT Equilibrium Reconstruction, Plasma Physics and Controlled Fusion, vol. 64 (7), 2022. [10.1088/1361-6587/ac6fff](https://doi.org/10.1088/1361-6587/ac6fff)
- **J. Koo**, S. Hwang, A Unified Defect Pattern Analysis of Wafer Maps Using Density-Based Clustering, IEEE Access, vol. 9, 2021, pp. 78873-78882. [10.1109/ACCESS.2021.3084221](https://doi.org/10.1109/ACCESS.2021.3084221)

### Refereed Proceedings
- T. Randall\*, **J. Koo\***, B. Videau, M. Kruse, X. Wu, P. Hovland, M. Hall, R. Ge, and P. Balaprakash\*, Transfer-Learning-Based Autotuning Using Gaussian Copula, ACM International Conference on Supercomputing (ICS), 2023, pp. 37-49. [10.1145/3577193.3593712](https://doi.org/10.1145/3577193.3593712) (\*Authors contributed equally to this work)
- X. Wu, P. Balaprakash, M. Kruse, **J. Koo**, B. Videau, P. Hovland, V. Taylor, B. Geltz, S. Jana, and M. Hall, ytopt: Autotuning Scientific Applications for Energy Efficiency at Large Scales, Cray User Group Conference (CUG), 2023. [10.48550/arXiv.2303.16245](https://arxiv.org/abs/2303.16245)
- M. Dorier, R. Egele, P. Balaprakash, **J. Koo**, S. Madireddy, A. D. Malony, S. Ramesh, R. Ross, HPC Storage Service Autotuning using Variational-Autoencoder-Guided Asynchronous Bayesian Optimization, IEEE International Conference on Cluster Computing (CLUSTER), 2022, pp. 381-393. [10.1109/CLUSTER51413.2022.00049](https://doi.org/10.1109/CLUSTER51413.2022.00049)
- **J. Koo**, P. Balaprakash, M. Kruse, X. Wu, P. Hovland, M. Hall, Customized Monte Carlo Tree Search for LLVM/Polly's Composable Loop Optimization Transformations, 12th IEEE International Workshop on Performance Modeling, Benchmarking and Simulation of High Performance Computer Systems (PMBS), 2021, pp. 82-93. [10.1109/PMBS54543.2021.00015](https://doi.org/10.1109/PMBS54543.2021.00015) [[code]](https://github.com/ytopt-team/ytopt/tree/mcts/ytopt/cmcts)
- A. Yanguas-Gil, **J. Koo**, S. Madireddy, P. Balaprakash, J. W. Elam, A. U. Mane, Neuromorphic Architectures for Edge Computing under Extreme Environments, IEEE Space Computing Conference (SCC), 2021, pp. 39-45. [10.1109/SCC49971.2021.00012](https://doi.org/10.1109/SCC49971.2021.00012)
- **J. Koo**, D. Klabjan, J. Utke, Combined Convolutional and Recurrent Neural Networks for Hierarchical Classification of Images, IEEE International Conference on Big Data, 2020, pp. 1354-1361. [10.1109/BigData50022.2020.9378237](https://doi.org/10.1109/BigData50022.2020.9378237) [[code]](https://github.com/jaehoonkoo/h_classification) [[slide]](https://github.com/jaehoonkoo/h_classification/blob/master/doc/%5BBigdata_2020%5D%20h_classification.pdf)
- **J. Koo**, D. Klabjan, Improved Classification Based on Deep Belief Networks, 29th International Conference on Artificial Neural Networks (ICANN), Lecture Notes in Computer Science. Springer, vol. 12396, 2020, pp 541–552. [10.1007/978-3-030-61609-0_43](https://doi.org/10.1007/978-3-030-61609-0_43)
- **J. Koo**, V. B. Mendiratta, M. R. Rahman, A. Walid, Deep Reinforcement Learning for Network Slicing with Heterogeneous Resource Requirements and Time Varying Traffic Dynamics, 15th International Conference on Network and Service Management, 2019. [10.23919/CNSM46954.2019.9012702](https://doi.org/10.23919/CNSM46954.2019.9012702)
- B. Yum, **J. Koo**, S. Kim, Analysis of Defective Patterns on Wafers in Semiconductor Manufacturing: A Bibliographical Review, IEEE International Conference on Automation Science and Engineering, 2012, pp. 86-90. [10.1109/CoASE.2012.6386471](https://doi.org/10.1109/CoASE.2012.6386471)

## Projects
- 2023-2026, Principal Investigator, Explainable and interpretable AI systems based on deep learning for classification, National Research Foundation of Korea (한국연구재단 기초연구사업-기본연구) 
- 2021-2022, Postdoc Researcher, EFIT‐AI: ML/AI Assisted Tokamak Equilibrium Reconstruction, DOE FES Project
- 2020-2022, Postdoc Researcher, PROTEAS‐TUNE: Programming Toolchain for Emerging Architectures and Systems, DOE ASCR Exascale Computing Project 
- 2020-2021, Postdoc Researcher, Circuit AI, Laboratory Directed Research and Development program at Argonne National Laboratory
- 2016-2020, Researcher, Projects with Allstate Insurance Company, University-Industry collaborative projects at Northwestern University  

## Talks
- 사회적경제와 인공지능–심층학습중심으로, 사회적경제혁신리더 과정 at Hanyang University, Ansan, South Korea, Nov. 2023
- Topics in Deep Learning Classification, Brown-Bag Seminar at Hanyang University Management Research Institute, Ansan, South Korea, Nov. 2022
- AI for Performance: Customized Monte Carlo Tree Search for LLVM/Polly's Composable Loop Optimization Transformations, Seminar at RAPIDS2 Project group, Virtual. Apr. 2022
- Model Order Reduction of EFIT with Deep Neural Networks, Invited talk to ML working group at Plasma Science and Fusion Center, Massachusetts Institute of Technology (MIT), Virtual. Apr. 2022
- Customized Monte Carlo Tree Search for LLVM/Polly's Composable Loop Optimization Transformations, [Postdoctoral Research and Career Symposium](https://www.anl.gov/sites/www/files/2021-11/2021_Postdoctoral_Symposium_ANL.pdf), Argonne National Lab, Virtual. Nov. 2021
- Ytop/SuRF: Machine-Learning-Based Search for Autotuning, [Exascale Computing Project Annual Meeting](https://whova.com/embedded/session/ecpan_202104/1511153/?view=), Virtual. Apr. 2021
- Mixed Integer Optimization for Prescriptive Analytics, Analytics Center of Excellence brown-bag event, Allstate, Northbrook, IL, USA. Feb. 2020 
- Deep Belief Network for Classification and Hierarchical Classification of Images, [Candidate Presentation at Mathematics and Computer Science Division](https://www.alcf.anl.gov/events/deep-belief-network-classification-and-hierarchical-classification-images), Argonne National Lab, Lemont, IL, USA. Jan. 2020
- Improved Classification Based on Deep Belief Networks, [Midwest Machine Learning Symposium](https://midwest-ml.org/2017/booklet.pdf), Chicago, IL, USA. Aug. 2017
- Models for Classification with Deep Belief Networks, INFORMS Optimization Society Conference, Princeton, NJ, USA. Mar. 2016

## Teaching
### Hanyang University <font size="2">(Ansan, Gyeonggi, South Korea)</font>
- Instructor, BUS5033 Operations Management Simulation (Spring 2024)
- Instructor, BAS3003 Operations Analytics (Spring 2023, 2024)
- Instructor, KDI0003 Digital Production Management and Manufacturing (Spring 2023)
- Instructor, BUS2013 Operations Management (Fall 2022, 2023)
- Instructor, BUS1008 Advanced Statistics for Business (Fall 2022, 2023)

### Northwestern University <font size="2">(Evanston, IL, USA)</font>
- TA/lab instructor, MSIA-423 Analytics Value Chain (Spring 2020)
- TA/lab instructor, MSIA-432 Deep Learning (Spring 2018)
- TA, IEMS-393-2 IE Design Project (Winter 2020)
- TA, IEMS-310 Operations Research (Spring 2017)
- TA, IEMS-385 Introduction to Health Systems Management (Fall 2015)

## Skills
- Programming Languages
  - Python, C++, MATLAB, R, AMPL
- Tools
  - Git, Linux, Vim, LaTex, Docker, Kubernetes, Spack
- ML-Software/libraries
  - PyTorch, Tensorflow, Keras, Caffe, Theano, Scikit-Learn, Gym, Ytopt, DeepHyper, GPTune

<!-- ## Teaching experience
- Lecturer, Hanyang University-ERICA (Spring 2023)
  - BAS3003 Operations Analytics
- Lecturer, Hanyang University-ERICA (Spring 2023)
  - KDI0003 Digital Production Management and Manufacturing
- Lecturer, Hanyang University-ERICA (Fall 2022)
  - BUS2013 Operations Management
- Lecturer, Hanyang University-ERICA (Fall 2022)
  - BUS1008 Advanced Statistics for Business
- TA/lab instructor, Northwestern University (Spring 2020)  
  - MSIA-423 Analytics Value Chain
- TA/lab instructor, Northwestern University (Spring 2018)
  - MSIA-432 Deep Learning
- TA, Northwestern University (Winter 2020)  
  - IEMS-393-2 IE Design Project
- TA, Northwestern University (Spring 2017)
  - IEMS-310 Operations Research
- TA, Northwestern University (Fall 2015)
  - IEMS-385 Introduction to Health Systems Management -->

<!-- ## Profiles
- Argonne profile at [https://www.anl.gov/profile/jaehoon-koo](https://www.anl.gov/profile/jaehoon-koo). 
- Northwestern website at [https://sites.google.com/a/u.northwestern.edu/jaehoon_koo/home](https://sites.google.com/a/u.northwestern.edu/jaehoon_koo/home). -->

<!-- - This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

[jekyll-organization]: https://github.com/jekyll -->
