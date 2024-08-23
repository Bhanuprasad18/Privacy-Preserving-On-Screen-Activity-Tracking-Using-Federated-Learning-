# Privacy-Preserving-On-Screen-Activity-Tracking-Using-Federated-Learning-
Tracking the User On-Screen Activity Using Machine Learning Algorithms By Implementing the Federated Learning
Project Title: Privacy-Preserving On-Screen Activity Tracking Using Federated Learning.
Description: In today's e-learning realm, demand for personalized experiences surges, necessitating adaptive platforms. However, traditional activity tracking methods pose privacy concerns. This project introduces a novel solution: Privacy-Preserving On-Screen Activity Tracking using Federated Learning. Leveraging advanced algorithms to analyze user engagement without compromising privacy, it ensures secure data handling. Federated learning facilitates collaborative model training across devices, preserving sensitive information. This initiative seeks to revolutionize e-learning by fostering adaptability while safeguarding user privacy, and contributing to ethical technological integration in education.

Requirements: 
  A. User Requirements:
     	1. PC, Mac or laptop with x86-64 (64-bit) compatible processors.
          A 2 GHz or better processor is recommended.
 	    2. At least 512 MB of free RAM should be available for the application.
      3. An Internet connection is required to detect URLs.
	    4. Microsoft Windows specific requirements:
          a. Microsoft Windows 7 / 8 / 10 / 11.
          b. Microsoft .NET Framework 4.5 or newer (for .NET components usage).
          c. One of the following development environments for application development:
              •	Microsoft Visual Studio 2012 or newer (for application development under C/C++, C#, Visual Basic .Net)
              •	Python IDLE
              •	Anaconda
  	  5. macOS specific requirements:
          a. macOS 10.13 or newer.
          b. XCode 9.3 or newer (for application development)
          c. GNU Make 3.81 or newer (to build samples and tutorials development)
          d. Anaconda
 	    6. Linux specific requirements:
          a. Linux 3.10 kernel or newer
          b. glibc 2.17 library or newer
          c. gcc 4.8 or newer (for application development)
          d. GNU Make 3.81 or newer (for application development)
          e. Anaconda
  B. Software Requirements:
 	    1. Python IDE: There are lots of IDEs for python. Some of them are PyCharm,   Thonny, Ninja, Spyder, anaconda etc. Ninja and Spyder both are very excellent and free but we used Spyder as it feature- rich             than ninja. Anaconda is used for our present system.
 	    2. ML Packages: NumPy, Pandas, sci-kit learn, Matplotlib, Seaborn, Flask, Pymysql.
 	    3. ML Libraries: whois, xgboost, favicon, beautiful soup, google search.
 	    4. ML Algorithms: Linear Regression, Decision Trees, Random Forest, Support Vector Machine, Naïve Bayes, Gradient Boosting Classifier.
  C. Hardware Components:
      1. Processor – i3
 	    2. Hard Disk – 5 GB
 	    3. Memory – 1GB RAM

Implementation:
In the dynamic landscape of e-learning, the demand for personalized and adaptive learning experiences has grown exponentially. As educational platforms incorporate sophisticated technologies to enhance user engagement and tailor content delivery, concerns about user privacy have become increasingly prominent. Traditional on-screen activity tracking methods often compromise user privacy, raising ethical and legal issues. This project introduces a groundbreaking solution — Privacy-Preserving On-Screen Activity Tracking and Classification in E-Learning using Federated Learning. The primary goal of this project is to develop a robust system that seamlessly integrates on-screen activity tracking and classification mechanisms into e-learning platforms while prioritizing user privacy through the implementation of federated learning. Federated learning is a decentralized machine learning approach that enables model training across multiple devices or servers without exchanging raw data. By adopting this paradigm, our system ensures that sensitive user information remains localized and secure on individual devices.
The proposed system leverages advanced machine learning algorithms to analyze on-screen activities, including mouse movements, keyboard inputs, and other relevant metrics, to understand user engagement and learning patterns. Through federated learning, these algorithms are trained collectively without exposing individual data points, preserving the privacy of each learner. This innovative approach not only enhances the adaptability of e-learning content but also addresses the critical concerns surrounding data privacy in educational technology. The project aims to contribute to the broader discourse on the responsible integration of technology in education by providing a privacy-centric solution for on-screen activity tracking. In doing so, it seeks to strike a balance between the benefits of personalized learning experiences and the imperative to protect user privacy. As the educational landscape continues to evolve, this research initiative holds the promise of shaping the future of e-learning, making it more secure, adaptive, and respectful of individual privacy.
E-learning, which leverages electronic technologies such as computers, mobile devices, and the Internet for education, has seen a substantial increase in adoption and usage in recent years. While it has the potential to reach every corner of the globe, it also creates an opportunity for time and resource wastage. This is because students often use the same device for both studying and entertainment purposes. With ever-addicting social media just a click away, it becomes challenging for students to stay focused on their studies and not waste time on digital devices. This issue is particularly significant given the increasing prevalence of online education. Despite this, the detection of students' on-screen activity remains an underexplored area of research. Moreover, to the best of our knowledge, no research considers the protection of their privacy.  
Therefore, this research proposes a privacy-preserving architecture to detect whether students are utilizing their time on their computers effectively or wasting it. The user’s privacy is protected with federated learning, a machine learning approach that allows for data analysis and model building without sharing raw data. The researchers used a dataset containing over 4000 screenshots of different activities of students. These screenshots were classified using several pre-trained models.
This project is a significant contribution to the underexplored area of on-screen activity detection in e-learning, with a strong emphasis on privacy preservation. It opens up new avenues for ensuring the effective utilization of time and resources in e-learning environments while safeguarding the privacy of the users. Understanding the Privacy Conundrum in E-Learning: Data Breaches: Student data, including browsing history, time spent on specific materials, and interaction patterns, holds tremendous potential for personalization. However, collecting and analyzing this data raises the risk of security breaches. Hackers could exploit vulnerabilities and expose sensitive information, leading to identity theft or exploitation. Misuse of Data: There is a risk that collected data could be used for purposes beyond educational objectives. Targeted advertising or profiling based on learning habits are potential concerns. Student Surveillance: Excessive tracking can create a sense of being constantly watched. This can lead to anxiety and a reluctance to explore freely within the platform, ultimately hindering the learning process. These concerns can create a climate of distrust, hindering the adoption of personalized learning techniques.    
Here's how federated learning works in our project:
Local Learning: Instead of sending raw student data to a central server, federated learning allows on-screen activity to be analyzed directly on the student's device. This anonymizes the data at the source, significantly enhancing privacy.
Model Updates: The device utilizes a machine learning model to classify the activity (reading, watching a video, taking notes, etc.). The model learns from the data and updates its parameters to improve its classification accuracy. However, only these updated model parameters, not the raw student data itself, are sent to a central server.
Privacy Preservation: These model updates are anonymized and aggregated with updates from other devices. This aggregated information is used to improve the overall model across the entire platform without revealing any individual student data.    
The possibilities with federated learning extend far beyond these examples. As technology evolves, we can envision a future where e-learning platforms become true partners in the learning journey, offering personalized guidance and support while safeguarding student privacy. This collaborative and privacy-centric approach has the potential to revolutionize education, making it more effective, engaging, and accessible for all. Our project, "Privacy-Preserving On-Screen Activity Tracking and Classification in E-Learning Using Federated Learning," represents a crucial first step in this journey. By laying the foundation for privacy-preserving learning analytics, we pave the way for a future where personalized learning flourishes alongside robust data security. This is a future where students can learn fearlessly, explore freely, and reach their full potential without compromising their privacy.         
The surge in remote learning necessitates effective monitoring of student engagement without compromising privacy. "Privacy-Preserving On-Screen Activity Tracking and Classification in E-Learning Using Federated Learning" introduces a novel solution to this challenge. Leveraging Federated Learning, our approach ensures stringent privacy protection while accurately classifying on-screen activities. By combining deep learning models with decentralized data processing, we aim to revolutionize e-learning monitoring. This paper outlines our pioneering strategy, poised to enhance educational outcomes while safeguarding user privacy. 
 Feature generation process. 
The feature generation process in the project “Privacy-Preserving On-Screen Activity Tracking and Classification in E-Learning Using Federated Learning” involves several steps:
Data Collection: The first step is data collection, where over 4000 screenshots of different activities of students are collected.
Pre-processing: The collected data is then pre-processed. This could involve steps like resizing the images, normalizing the pixel values, and other necessary transformations to prepare the data for the model.
Feature Extraction: The pre-processed data is then fed into several pre-trained models for feature extraction. These models, which could include Convolutional Neural Networks (CNNs), are capable of automatically extracting relevant features from the images.
Model Training: The extracted features are then used to train the proposed model, DT, LDA, CNN. These models are trained to classify the on-screen activities of students into different categories.
Prediction: Once the model is trained, it can be used to predict the category of new, unseen on-screen activities.
Result Generation: Finally, the results of the prediction are generated and can be viewed by the user.
This process ensures that the model is capable of accurately classifying on-screen activities while preserving the privacy of the user. The use of federated learning ensures that the raw data does not need to be shared, thus preserving privacy.

