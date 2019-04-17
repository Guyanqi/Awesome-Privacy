# Awesome-Privacy  

This is a repository for papers on all kinds of things on privacy. Currently its' only for personal use.  
Privacy is a very interesting research area, it has promising application in interaction with learning theory, IoT, multi-agent systems.  
This is a collection of research and review papers of privacy. The papers are sorted by time. Any suggestions and pull requests are welcome.  
The sharing is only for research purpose. If any authors don't want their paper to be listed here, please feel free to contact me(you can find my email address on my github homepage).  
In my opinion, there're currently several things that researchers in this area need to pay attention to:   
Mathematical Frameworks(Theoretical research in differential privacy is getting hotter, including private learning algorithms and fair learning),
Privacy in practice(Since we already have these privacy algorithms, it's important to think about how to implement them efficiently),
Domains Usage(Currently privacy is important and need to be studied in CPS systems, mobile systems and tracking systems),
Policy(This part is for politics).  

## Framework  
### DP theory  
* [Individual Fairness Under Composition](http://www.fatml.org/media/documents/individual_fairness_under_composition.pdf) by Cynthia Dwork and Christina Ilvento. 2018  
* [Differentially Private Fair Learning](https://arxiv.org/abs/1812.02696) by Matthew Jagielski, Michael Kearns, Jieming Mao, Alina Oprea, Aaron Roth, Saeed Sharifi-Malvajerdi, Jonathan Ullman. 2018  
* [Differentially Private False Discovery Rate Control](https://arxiv.org/abs/1807.04209) by Cynthia Dwork, Weijie J. Su, Li Zhang. 2018  
* [THE FIENBERG PROBLEM: HOW TO ALLOW HUMAN INTERACTIVE DATA ANALYSIS IN THE AGE OF DIFFERENTIAL PRIVACY] by Cynthia Dwork and Jonathan Ullman. 2018
* [Accuracy First: Selecting a Differential Privacy Level for Accuracy-Constrained ERM](https://arxiv.org/abs/1705.10829) by Katrina Ligett, Seth Neel, Aaron Roth, Bo Waggoner, Z. Steven Wu. 2017  
* [Penalizing Unfairness in Binary Classification](https://arxiv.org/abs/1707.00044) by Yahav Bechavod, Katrina Ligett. 2017  
* [Concentrated Differential Privacy](https://arxiv.org/abs/1603.01887) by Cynthia Dwork, Guy N. Rothblum. 2016  
* [Protecting Privacy when Disclosing Information: k-Anonymity and Its Enforcement through Generalization and Suppression](https://epic.org/privacy/reidentification/Samarati_Sweeney_paper.pdf) by Pierangela Samarati and Latanya Sweeney  

### Local Differential Privacy  
* [Local Differential Privacy for Evolving Data](https://arxiv.org/abs/1802.07128) by Matthew Joseph, Aaron Roth, Jonathan Ullman, Bo Waggoner. 2018  
* [Privacy at Scale: Local Differential Privacy in Practice](http://dimacs.rutgers.edu/~graham/pubs/papers/ldptutorial.pdf) by Graham Cormode, Somesh Jha, Tejas kulkarni, Ninghui Li, Divesh Srivastava, Tianhao Wang. 2018  
* [Locally Private Gaussian Estimation](https://arxiv.org/abs/1811.08382) by Matthew Joseph, Janardhan Kulkarni, Jieming Mao, Zhiwei Steven Wu. 2018  

### Privacy in Collaborative Learning  
* [Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning](https://arxiv.org/abs/1702.07464) by Briland Hitaj, Giuseppe Ateniese, Fernando Perez-Cruz. 2017  

### Privacy in ML  
* [Faster CryptoNets: Leveraging Sparsity for Real-World Encrypted Inference](https://arxiv.org/abs/1811.09953) by Edward Chou, Josh Beal, Daniel Levy, Serena Yeung, Albert Haque, Li Fei-Fei. 2018  
* [Learning with differential privacy: stability, learnability and the sufficiency and necessity of ERM principle](https://dl.acm.org/citation.cfm?id=3053465) by Yu-Xiang Wang, Jing Lei, Stephen E.Fienberg. 2016  
* [Privacy-Preserving Deep Learning](https://www.cs.cornell.edu/~shmat/shmat_ccs15.pdf) by Reza Shokri and Vitaly Shmatikov.2015  
* [Differential Privacy and Machine Learning: a Survey and Review](https://arxiv.org/abs/1412.7584) by Zhanglong Ji, Zachary C. Lipton, Charles Elkan. 2014  

### Privacy in GAN  
* [Differentially Private Generative Adversarial Networks for Time Series, Continuous, and Discrete Open Data
](https://arxiv.org/abs/1901.02477) by Lorenzo Frigerio, Anderson Santana de Oliveira, Laurent Gomez, Patrick Duverger. 2019   
* [Generative Adversarial Nets](https://arxiv.org/abs/1406.2661) by Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio. 2014  

### Privacy in MAB  
* [Differentially Private Contextual Linear Bandits](https://arxiv.org/pdf/1810.00068.pdf) by Roshan Shariff and Or Sheffet. 2018  
* [Achieving Privacy in the Adversarial Multi-Armed Bandit](https://arxiv.org/abs/1701.04222) by Aristide C. Y. Tossou, Christos Dimitrakakis. 2017  
* [Differentially Private Policy Evaluation](https://arxiv.org/abs/1603.02010) by Borja Balle, Maziar Gomrokchi, Doina Precup. 2016  
* [Algorithms for Differentially Private Multi-Armed Bandits](https://arxiv.org/abs/1511.08681) by Aristide Tossou, Christos Dimitrakakis. 2015  
* [MAB problems](http://web.eecs.umich.edu/faculty/teneketzis/papers/MAB-Survey.pdf) by Aditya Mahajan and D.teneketzis  
* [(Nearly) Optimal Differentially Private Stochastic Multi-Arm Bandits](http://auai.org/uai2015/proceedings/papers/58.pdf) by Nikita Mishra and Abhradeep Thakurta  
* [Taming the Monster: A Fast and Simple Algorithm for Contextual Bandits](http://proceedings.mlr.press/v32/agarwalb14.pdf) by A.A, D.H, S.K, J.L, L.L, R.E.S  

## Efficient Deployment  
### Parallel Computing  
* [GENERATIVE ADVERSARIAL PARALLELIZATION](https://openreview.net/pdf?id=Sk8J83oee) by Daniel Jiwoong Im, He Ma, Chris Dongjoo Kim and Graham W.Taylor. 2016  

## Application   
### Privacy in CPS  
* [Differential Privacy Techniques for Cyber Physical Systems: A Survey](https://arxiv.org/abs/1812.02282) by Muneeb Ul Hassan, Mubashir Husain Rehmani, Jinjun Chen. 2018  

### Privacy in IoT  

### Privacy in Network  
* [NoMoAds: Effective and Efficient Cross-App Mobile Ad-Blocking](https://www.petsymposium.org/2018/files/papers/issue4/popets-2018-0035.pdf) by Anastaisa Shuba, A.Markopoulou and Zubair Shafiq. 2018  
* [Online Tracking: A 1-million-site Measurement and Analysis](http://randomwalker.info/publications/OpenWPM_1_million_site_tracking_measurement.pdf) by Steven Englehardt and Arvind Narayanan. 2016  
* [Third-Party Web Tracking: Policy and Technology](https://jonathanmayer.org/publications/trackingsurvey12.pdf) by Jonathan Mayer and John Mitchell. 2012  

## Politics  


