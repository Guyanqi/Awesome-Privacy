# Awesome-Privacy  

This is a repository for resources on all kinds of things of Privacy Enhancing techinques (PETs). Currently it's maintained by [Yanqi Gu](https://guyanqi.github.io).   
All these papers are sorted by time and seperated by category. Any suggestions and pull requests are welcome. This repository is only for research purpose. If any authors don't want their paper to be listed here, please feel free to contact me(you can find my email address on my homepage).  

This repository will focus on:     
Differential Privacy (DP), including 1.Mathematical Frameworks(theoretical research in differential privacy) and 2.Privacy in practice(applications of differential privacy algorithms)   
TBA:   
Multi-party Computation (MPC)    
Homomorphic Encryption (HE)    
Trusted Execution Environment (TEE)    


## Framework  
### DP theory
* Gaussian differential privacy [[paper]](https://arxiv.org/pdf/1905.02383) by Jinshuo Dong,  Aaron Roth, Weijie J. Su.  2019
* Average-Case Averages: Private Algorithms for Smooth Sensitivity and Mean Estimation[[paper]](https://arxiv.org/pdf/1906.02830.pdf) by Mark Bun and Thomas Steinke. 2019
* New Differentially Private Algorithms for Learning Mixtures of Well-Separated Gaussians[[paper]](https://arxiv.org/pdf/1909.03951.pdf) by Gautam Kamath, Or Sheffet, Vikrant Singhal, Jonathan Ullman. 2019 
* Private Hypothesis Selection [[paper]](https://arxiv.org/pdf/1905.13229.pdf) by Mark Bun, Gautam Kamath, Thomas Steinke,Steven Wu. 2019
* Privacy Amplification by Iteration [[paper]](https://arxiv.org/abs/1808.06651) by Vitaly Feldman, Ilya Mironov, Kunal Talwar, Abhradeep Thakurta. 2018
* pMSE Mechanism: Differentially Private Synthetic Data with Maximal Distributional Similarity [[paper]](https://arxiv.org/pdf/1805.09392.pdf) by Joshua Snoke and Aleksandra Slavkovic. 2018
* Differentially Private Continual Learning [[paper]](https://arxiv.org/pdf/1902.06497.pdf) by S.Farquhar and Yarin Gal. 2018
* Individual Fairness Under Composition [[paper]](http://www.fatml.org/media/documents/individual_fairness_under_composition.pdf) by Cynthia Dwork and Christina Ilvento. 2018  
* Differentially Private Fair Learning [[paper]](https://arxiv.org/abs/1812.02696) by Matthew Jagielski, Michael Kearns, Jieming Mao, Alina Oprea, Aaron Roth, Saeed Sharifi-Malvajerdi, Jonathan Ullman. 2018  
* Differentially Private False Discovery Rate Control [[paper]](https://arxiv.org/abs/1807.04209) by Cynthia Dwork, Weijie J. Su, Li Zhang. 2018  
* Accuracy First: Selecting a Differential Privacy Level for Accuracy-Constrained ERM [[paper]](https://arxiv.org/abs/1705.10829) [[code]](https://github.com/steven7woo/Accuracy-First-Differential-Privacy) by Katrina Ligett, Seth Neel, Aaron Roth, Bo Waggoner, Z. Steven Wu. 2017  
* Penalizing Unfairness in Binary Classification [[paper]](https://arxiv.org/abs/1707.00044) by Yahav Bechavod, Katrina Ligett. 2017  
* Concentrated Differential Privacy [[paper]](https://arxiv.org/abs/1603.01887) by Cynthia Dwork, Guy N. Rothblum. 2016  
* Protecting Privacy when Disclosing Information: k-Anonymity and Its Enforcement through Generalization and Suppression [[paper]](https://epic.org/privacy/reidentification/Samarati_Sweeney_paper.pdf) by Pierangela Samarati and Latanya Sweeney  

### Local Differential Privacy  
* Answering multi-dimensional analytical queries under local differential privacy [[paper]](https://par.nsf.gov/servlets/purl/10194803) by  Tianhao Wang, Bolin Ding, Jingren Zhou, Cheng Hong, Zhicong Huang, Ninghui Li, Somesh Jha. 2019
* Locally Private Gaussian Estimation [[paper]](https://arxiv.org/abs/1811.08382) by Matthew Joseph, Janardhan Kulkarni, Jieming Mao, Zhiwei Steven Wu. 2019  
* Local Differential Privacy for Evolving Data [[paper]](https://arxiv.org/abs/1802.07128) by Matthew Joseph, Aaron Roth, Jonathan Ullman, Bo Waggoner. 2018  
* Privacy at Scale: Local Differential Privacy in Practice [[paper]](http://dimacs.rutgers.edu/~graham/pubs/papers/ldptutorial.pdf) by Graham Cormode, Somesh Jha, Tejas kulkarni, Ninghui Li, Divesh Srivastava, Tianhao Wang. 2018  
* Locally Private Gaussian Estimation [[paper]](https://arxiv.org/abs/1811.08382) by Matthew Joseph, Janardhan Kulkarni, Jieming Mao, Zhiwei Steven Wu. 2018  
* Locally differentially private protocols for frequency estimation [[paper]](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-wang-tianhao.pdf) by  Tianhao Wang, Jeremiah Blocki, Ninghui Li, Somesh Jha. 2017

### Image Privacy
* Learning to Anonymize Faces for Privacy Preserving Action Detection [[paper]](https://web.cs.ucdavis.edu/~yjlee/projects/eccv2018-privacy.pdf) by Zhongzheng Ren, Yong Jae Lee and Michael S.Ryoo. 2019
* Image Privacy Prediction Using Deep Neural Networks [[paper]](https://arxiv.org/pdf/1903.03695.pdf) by Ashwini Tonge, Cornelia Caragea. 2019

### Adversarial Examples and Robustness    
* A unified view on differential privacy and robustness to adversarial examples [[paper]](https://arxiv.org/abs/1906.07982) by Rafael Pinot, et al. 2019   
* Certified Robustness to Adversarial Examples with Differential Privacy [[paper]](https://arxiv.org/abs/1802.03471) by Mathias Lecuyer, Vaggelis Atlidakis, Roxana Geambasu, Daniel Hsu, Suman Jana. 2018  

### Privacy and Generative Model
* Generalization in Generative Adversarial Networks:A Novel Perspective from Privacy Protection [[paper]](https://arxiv.org/pdf/1908.07882.pdf) by Bingzhe Wu etc. 2019
* DP-CGAN : Differentially Private Synthetic Data and Label Generation [[paper]](http://openaccess.thecvf.com/content_CVPRW_2019/papers/CV-COPS/Torkzadehmahani_DP-CGAN_Differentially_Private_Synthetic_Data_and_Label_Generation_CVPRW_2019_paper.pdf) by Peter Kairouz etc. 2019
* Siamese Generative Adversarial Privatizer for Biometric Data [[paper]](https://arxiv.org/pdf/1804.08757.pdf) [[code]](https://github.com/WUT-ML/privacy) by WUT and peter kairouz. 2018
* Generative Adversarial Models for Learning Private and Fair Representations(GAPF) [[paper]](https://arxiv.org/abs/1807.05306) [[code]](https://github.com/cabreraalex/private-fair-GAN) by Chong Huang, Peter Kairouz, Lalitha Sankar. 2018
* Context-Aware Generative Adversarial Privacy(GAP) [[paper]](https://arxiv.org/abs/1710.09549) by Chong Huang, Peter Kairouz, Xiao Chen, Lalitha Sankar, Ram Rajagopal. 2017  
* Differentially Private Generative Adversarial Networks for Time Series, Continuous, and Discrete Open Data
 [[paper]](https://arxiv.org/abs/1901.02477) by Lorenzo Frigerio, Anderson Santana de Oliveira, Laurent Gomez, Patrick Duverger. 2018   
* Generative Adversarial Nets [[paper]](https://arxiv.org/abs/1406.2661) by Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio. 2014  

### Privacy in Federated Learning  
* Beyond Inferring Class Representatives: User-Level Privacy Leakage From Federated Learning [[paper]](https://arxiv.org/pdf/1812.00535.pdf) by Zhibo Wang, etc. 2019
* Exploiting Unintended Feature Leakage in Collaborative Learning [[paper]](https://arxiv.org/pdf/1805.04049.pdf) [[code]](https://github.com/csong27/property-inference-collaborative-ml) by Vitaly's group. 2019
* How To Backdoor Federated Learning [[paper]](https://arxiv.org/abs/1807.00459) [[code]](https://github.com/ebagdasa/backdoor_federated_learning) by Vitaly's group. 2018
* Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning [[paper]](https://arxiv.org/abs/1702.07464) by Briland Hitaj, Giuseppe Ateniese, Fernando Perez-Cruz. 2017  

### Private ML  
* Towards practical differentially private convex optimization [[paper]](http://www.omthakkar.com/papers/TPDPCO.pdf) by  Roger Iyengar, Joseph P Near, Dawn Song, Om Thakkar, Abhradeep Thakurta, Lun Wang. 2019
* Bolt-on Differential Privacy for Scalable Stochastic Gradient Descent-based Analytics [[paper]](https://dl.acm.org/doi/pdf/10.1145/3035918.3064047) by  Xi Wu, Fengan Li, Arun Kumar, Kamalika Chaudhuri, Somesh Jha, Jeffrey F Naughton. 2017
* Deep learning with differential privacy [[paper]](https://arxiv.org/pdf/1607.00133.pdf%20) by  Martin Abadi, Andy Chu, Ian Goodfellow, H Brendan McMahan, Ilya Mironov, Kunal Talwar, Li Zhang. 2016
* Learning with differential privacy: stability, learnability and the sufficiency and necessity of ERM principle [[paper]](https://dl.acm.org/citation.cfm?id=3053465) by Yu-Xiang Wang, Jing Lei, Stephen E.Fienberg. 2016  
* Privacy-Preserving Deep Learning [[paper]](https://www.cs.cornell.edu/~shmat/shmat_ccs15.pdf) by Reza Shokri and Vitaly Shmatikov.2015  
* Differential Privacy and Machine Learning: a Survey and Review [[paper]](https://arxiv.org/abs/1412.7584) by Zhanglong Ji, Zachary C. Lipton, Charles Elkan. 2014  

### Privacy in MAB  
* Privacy-Preserving Contextual Bandits [[paper]](https://arxiv.org/pdf/1910.05299.pdf) by Facebook AI Research. 2019
* Differentially Private Contextual Linear Bandits [[paper]](https://arxiv.org/pdf/1810.00068.pdf) by Roshan Shariff and Or Sheffet. 2018  
* Achieving Privacy in the Adversarial Multi-Armed Bandit [[paper]](https://arxiv.org/abs/1701.04222) by Aristide C. Y. Tossou, Christos Dimitrakakis. 2017  
* Differentially Private Policy Evaluation [[paper]](https://arxiv.org/abs/1603.02010) by Borja Balle, Maziar Gomrokchi, Doina Precup. 2016  
* Algorithms for Differentially Private Multi-Armed Bandits [[paper]](https://arxiv.org/abs/1511.08681) by Aristide Tossou, Christos Dimitrakakis. 2015  
* MAB problems [[paper]](http://web.eecs.umich.edu/faculty/teneketzis/papers/MAB-Survey.pdf) by Aditya Mahajan and D.teneketzis  
* (Nearly) Optimal Differentially Private Stochastic Multi-Arm Bandits [[paper]](http://auai.org/uai2015/proceedings/papers/58.pdf) by Nikita Mishra and Abhradeep Thakurta  
* Taming the Monster: A Fast and Simple Algorithm for Contextual Bandits [[paper]](http://proceedings.mlr.press/v32/agarwalb14.pdf) by A.A, D.H, S.K, J.L, L.L, R.E.S  

### Privacy-preserving Encrypted Neural Network
* SHE: A Fast and Accurate Deep Neural Network for Encrypted Data [[paper]](https://arxiv.org/abs/1906.00148) [[code]](https://github.com/safednn/SHE) by Qian Lou, Lei Jiang. 2019
* 2P-DNN : Privacy-Preserving Deep Neural Networks Based on Homomorphic Cryptosystem [[paper]](https://arxiv.org/abs/1807.08459) [[code]](https://github.com/zhustrong/pigstrong/tree/master/pigstrong) by Qiang Zhu, Xixiang Lv. 2018
* ABY3 A Mixed Protocol Framework for Machine Learning [[paper]](https://eprint.iacr.org/2018/403.pdf) by  Payman Mohassel, Peter Rindal . 2018
* Secureml: A system for scalable privacy-preserving machine learning [[paper]](http://web.eecs.umich.edu/~mosharaf/Readings/SecureML.pdf) by  Payman Mohassel, Yupeng Zhang. 2017


## Differential Privacy Tutorial
* For dummies [[link]](https://robertovitillo.com/2016/07/29/differential-privacy-for-dummies/)
* Emory University CS 573 Data Privacy and Security, Fall 2018 [[course website]](http://www.cs.emory.edu/~lxiong/cs573/)
* KDD 2018 Privacy tutorial [[link]](https://sites.google.com/view/kdd2018privacytutorial)
* KDD 2018 Privacy at scale: Local Differential Privacy in Practice [[link]](https://sites.google.com/view/kdd2018-tutorial/home)


