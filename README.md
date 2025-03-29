# A-Machine-Learning-Based-Classification-and-Prediction-Technique-for-DDoS-Attacks
Distributed network attacks are referred to, usually, as Distributed Denial of Service (DDoS) attacks. These attacks take advantage of specific limitations that apply to any arrangement asset, such asthe framework of the authorized organizations site. In the existing research study, the author worked on an old KDD dataset. It is necessary to work with the latest dataset to identify the current state of DDoS attacks. This paper, used a machine learning approach for DDoS attack types classification and prediction.For this purpose, used Random Forest and XGBoost classi cation algorithms. To access the research proposed a complete framework for DDoS attacks prediction.

# Introduction
Distributed network attacks are referred to, usually, as Distributed Denial of Service (DDoS) attacks. These attacks take advantage of specific limitations that apply to any arrangement asset, such as the framework of the authorized organizations website. A DDoS attack sends different requests (with IP spoong) to the target web assets to exceed the sites ability to handle various requests, at a given time, and makethesite unable to operate effectively and efficiently even for the legitimate users of the network. Typically, the target of various DDoS attacks are web applications and business websites and the attacker may have different goals.

# Types of DDoS Attacks
The SYN Flood abuses the shortcomings in TCP association packets, which is called a three-way handshake. The host obtains a synchronization (SYN) message to initiate a ``handshake''. The UDP is a kind of denial-of-service attacks in which numerous User Datagram Protocol (UDP) packets are forwarded to a computer server (targeted) in order to exhaust that server's capability to execute and reply requests. The HTTP flood is an attack type in which the attacker seemingly exploits even the legitimate HTTP GET or POST requests in order to attack a web application or a web server.

# Motivation for Machine Learning
The authors proposed different algorithms for classification because the current algorithms have a lot of laws and drawbacks. First, they cannot work with irrelevant values and feature engineering because the confusion matrix results are not accurate. Some labeled results are zero that means algorithms do not work well. So, this is important to train the model precisely. Another problem is that some results show (Null) that means missing values also included in data that was not computed. Similarly, we need to justify existing algorithms with an advanced algorithm to find out the fastest and sufficient model. They also showed that random forest is not better than the KNN model because the result is less for the KNN model. In CNN and RNN both are two different algorithms that can be used for different purposes.

# Contribution
There are many research works being proposed for DDOS attacks detection and prevention; however, the main problem is that all the researcher worked with old datasets, in particular, KDDCUP. Therefore, this is very important to work with the latest datasets where we can examine the current state of the DDOS attacks detection and prevention.

# Related Work
The latest research papers of the past two years for this research work and also Gozde Karatas proposed a machine learning approach for attacks classification. They used different machine learning algorithms and found that the KNN model is best for classification as compared to other research work. Nuno Martins proposed intrusion detection using machine learning approaches. They used the KDD dataset which is available on the UCI repository. They performed different supervised models to balance unclassification algorithm for better performance. Laurens D’hooge proposed a systematic review for malware detection using machine learning models. They compared different malware datasets from online resources as well as approaches for the dataset. They found that machine learning supervised models are very effective for malware detection to make a better decision in less time. Xianwei Gao et al proposed a comparative work for network traffic classification. They used machine learning classifiers for intrusion detection. The dataset is taken is CICIDS and KDD from the UCI repository. They found support vector machine SVM one of the best algorithms as compare to others.

# Objective
Develop and implement a machine learning-based system that can accurately classify and predict Distributed Denial of Service (DDoS) attacks in real-time, with a primary focus on reducing false positives and ensuring rapid response to mitigate the impact of such attacks.

# Conclusion
In this project, I proposed a complete systematic approach for detection of the DDOS attack. First, I selected the UNSW-nb15 dataset from the GitHub repository that contains information about the DDOS attacks. This dataset was provided by the Australian Centre for Cyber Security(ACCS). Then, Python and jupyter notebook were used to work on data wrangling. Secondly, I divided the dataset into two classes i.e. the dependent class and the independent class. Moreover, I normalized the dataset for the algorithm. After data normalization, I applied the proposed, supervised, machine learning approach. The model generated prediction and classification outcomes from the supervised algorithm. Then, I used Random Forest and XG Boost classification algorithms. In the first classification, I observed that both the Random Forest Precision (PR) and Recall (RE) are approximately 89% accurate. Furthermore, we noted approximately 89% average Accuracy (AC) for the proposed model that is enough good and extremely awesome. Note that the average Accuracy illustrates the F1 score as 89%. For the second classification, I noted that both the XG Boost Precision (PR) and Recall (RE) are approximately 90% accurate. I noted approximately 90% average Accuracy (AC) of the suggested model that is wonderful and extremely brilliant. Again, the average Accuracy illustrates the F1 score as 90%. By comparing the proposal to existing research works, the defect determination accuracy of the existing research which was 85% and 79% were also significantly improved. Looking to the future, for functional applications, it is important to provide a more user-friendly, faster alternative to deep learning calculations, and produce better results with a shorter burning time. It is important to work on unsupervised learning toward supervised learning for unlabeled and labeled datasets. Moreover, I will investigate how non supervised learning algorithms will affect the DDOS attacks detection in particular, I non-labeled datasets are taken into account.
