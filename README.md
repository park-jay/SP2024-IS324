# SP2024-IS324 Social Network Analysis
School of Information Science, University of Illinois at Urbana-Champaign \
Jaihyun Park \
Office Hours: TBD 

This GitHub repository contains contents (Python scripts and data for the lab session) for Spring 2024 IS 324 Social Network Analysis. 

The network of social beings can come in a variety of forms and structures. We communicate and leave evidence of our interactions in various forms of data. For example, we leave traces of our interactions in the form of text messages, emails, and social media posts. We also leave traces of our interactions in the form of physical proximity, such as co-location and co-attendance. These traces of interactions can be transformed into a network structure. However, the network structure is not always visible and straightforward. In addition, it is not always provided in a structured format (e.g., a list of nodes and edges).
Therefore, to study social networks, it is important to start building a network structure from unstructured data (i.e., text data) and excavate the underlying structure of the network. Processing text data and transforming it into a network structure is the fundamental step in social network analysis. This course will introduce students to hands-on experience with social network analysis (SNA) and its applications in various fields. Students will learn (1) fundamental concepts and theories of SNA, (2) how to build a network structure from unstructured data, (3) how to analyze the network structure, and (4) how to interpret the results of the analysis. Students will also learn how to apply SNA to various fields, such as information science, and social science. This course will use Python as a (1) pre-processing tool, (2) network analysis tool, and (3) visualization tool. Students will learn practical skills in Python, such as data cleaning, data transformation, and data visualization for SNA. Combining theories and practical skills, students will learn how to apply SNA to various fields. 

## Course Information
Week 1: Introduction 
- Basic concepts and theories of social network analysis 
- Discussion of expectations and goals for the course 
- Discussion of applications of social network analysis 
- Installation of Python, IDE (Preferably VS Code), Anaconda (Jupyter Notebook), and setting up GitHub repository 
- Readings:
    - Lazer D. et al. (2009). "Computational social science." *Science* 323 (5915), 721-723. [paper](https://www.science.org/doi/full/10.1126/science.1167742?casa_token=LPRTTxsd-qoAAAAA:o9zrGUKD7QgYTQYy7PbowP1JpioaWDZrUUev-ynpXJTnWg-ObuJ2Ixbh4A_UJ4ImhS0B06xbt0c_fA)
    - Connolly, R. (2020) "Why computing belongs within the social sciences." 
*communications of the ACM* 63 (8), 54-59. [paper](https://dl-acm-org.proxy2.library.illinois.edu/doi/10.1145/3383444)
    - Zhang, J., Wang, W., Xia, F., Lin, Y. R., & Tong, H. (2020). "Data-driven computational social science: A survey." *Big Data Research*, 21, 100145. [paper](https://www-sciencedirect-com.proxy2.library.illinois.edu/science/article/pii/S2214579620300137?casa_token=w7E-zgChGPUAAAAA:Tbi7HyvUaPvPc2KIjkWjoX7ogAXoTS56pJk0oEG3yMaP07Bm588mmfgZGVyWJm5wQDlbcZ9Fsw)
    - Lightning AI. "Jupyter Notebooks vs Python projects: Learn when when to use which | Ep1" [video](https://www.youtube.com/watch?v=JGnoTN1OnWY)

Week 2: Anatomy of Network Analysis 
- Basic constituents of a network: nodes, edges, and attributes 
- Types of networks: directed, undirected, weighted, and unweighted 
- Network measures: degree, centrality, and betweenness 
- Discussion of transformation to a network structure of real-world scenarios 
- Discussion of network measures of real-world scenarios 
- Introduction to the Python environment (Anaconda)
- Introduction to libraries for network analysis (Pandas, NetworkX, and Matplotlib)
- Lab Practice: Git and GitHub
- Readings: TBD

HW 1 Due: TBD

Week 3: Social Media Network Analysis
- Affordances of social media data for network analysis: mention, retweet, and hashtag
- Discussion of transformation to a network structure of social media data
- Discussion of network measures of social media data
- Lab Practice: Twitter network analysis (mention, retweet, and hashtag)
- Lab Practice: Pandas data frame, Regular Expression
- Lab Practice: Transformation of social media data to a network structure
- Readings: 
    - Kwak, H., Lee, C., Park, H., & Moon, S. (2010). "What is Twitter, a social network or a news media?" In Proceedings of the 19th international conference on World wide web (pp. 591 - 600). [paper](https://dl-acm-org.proxy2.library.illinois.edu/doi/pdf/10.1145/1772690.1772751)
    - Keller, F. B., Schoch, D., Stier, S., & Yang, J. (2020). "Political astroturfing on twitter: How to coordinate a disinformation campaign." *Political communication*, 37(2), 256-280. [paper](https://www.tandfonline.com/doi/full/10.1080/10584609.2019.1661888?casa_token=FG3hReJmDAMAAAAA%3APjYEOFSJOjLzXCyxfQGaQ-sHbrk9kEOVM0DWhn3rTCgFk9eEOETXmDlVKigLgS3AYPEdqrViw11n)
    - Gallacher, J. D., Heerdink, M. W., & Hewstone, M. (2021). "Online engagement between opposing political protest groups via social media is linked to physical violence offline encounters." *Social Media+ Society*, 7(1) [paper](https://journals-sagepub-com.proxy2.library.illinois.edu/doi/full/10.1177/2056305120984445)
    - An, J., Kwak, H., Posegga, O., & Junherr, A. (2019). "Political discussions in homogeneous and cross-cutting communication spaces." In Proceddings of the International AAAI Conference on Web and Social Media (Vol. 13, pp. 68-79). [paper](https://ojs.aaai.org/index.php/ICWSM/article/view/3210)
- Useful sources: Regex Cheat Sheet, Regex Tester

Week 4: Email Network Analysis
- Affordances of email data for network analysis: sender, receiver, and cc
- Discussion of transformation to a network structure of email data
- Discussion of network measures of email data
- Lab Practice: Email network analysis (sender, receiver, and cc)
- Lab Practice: Transformation of email data to a network structure
- Readings: TBD
- Useful sources: Harvard Dataverse, Zenodo

Week 5: Text Reprint Network Analysis from news articles 
- Affordances of text data for network analysis: co-occurrence of words
- Discussion of transformation to a network structure of text data
- Discussion of bias in digitized text data
- Lab Practice: N-gram analysis for text data
- Readings: TBD
- Useful sources: Chronicling America

Week 6: NetworkX library for network analysis (Connects back to Week 2)
- Introduction to NetworkX library
- Transformation of nodes, edges, and attributes to a network structure in NetworkX
- Calculation of network measures in NetworkX
    - Assortativity
    - Clustering
    - Structural holes
    - Community detection (e.g., Louvain method)
- Lab Practice: NetworkX library for representing nodes, edges, and attributes
- Lab Practice: NetworkX library for calculating network measures
- Readings: TBD

HW 2 Due: TBD & GitHub Classroom

Week 7: Social Media Network Analysis with NextworkX (Connects back to Week 3)
- Transformation of social media data to a network structure in NetworkX
- Calculation of network measures of social media data in NetworkX
- Lab Practice: NetworkX library for representing social media data
- Lab Practice: NetworkX library for calculating network measures of social media data
- Readings: TBD

Week 8: Email Network Analysis with NextworkX (Connects back to Week 4)
- Transformation of email data to a network structure in NetworkX
- Calculation of network measures of email data in NetworkX
- Lab Practice: NetworkX library for representing email data
- Lab Practice: NetworkX library for calculating network measures of email data
- Readings: TBD

Week 9: Spring Break

Week 10: Text Reprint Network Analysis with NextworkX (Connects back to Week 5)
- Transformation of text data to a network structure in NetworkX
- Calculation of network measures of text data in NetworkX
- Lab Practice: NetworkX library for representing text data
- Lab Practice: NetworkX library for calculating network measures of text data
- Readings: TBD

HW 3 Due: TBD & GitHub Classroom

Week 11: Network Visualization (Connects back to Week 2)
- Introduction to Matplotlib library
- Visualization of a network structure in Matplotlib
- Lab Practice: Matplotlib library for visualizing a network structure
- Readings: TBD

Week 12: Social Media Network Visualization (Connects back to Week 3)
- Visualization of social media data in Matplotlib
- Lab Practice: Matplotlib library for visualizing social media data
- Readings: TBD

Week 13: Email Network Visualization (Connects back to Week 4)
- Visualization of email data in Matplotlib
- Lab Practice: Matplotlib library for visualizing email data
- Readings: TBD

Week 14: Text Reprint Network Visualization (Connects back to Week 5)
- Visualization of text data in Matplotlib
- Lab Practice: Matplotlib library for visualizing text data
- Readings: TBD

HW 4 Due: TBD & GitHub Classroom

Week 15: Final Group Project Presentation
- Final Project Presentation
- Readings: TBD

Week 16: Final Group Project Presentation
- Final Project Presentation
- Readings: TBD

## Course Requirements
- Attendance and participation (20%)
- Homework assignments (40%)
- Final project (40%)

## Grading
- A+: 97-100
- A: 93-96
- A-: 90-92
- B+: 87-89
- B: 83-86
- B-: 80-82
- C+: 77-79
- C: 73-76
- C-: 70-72
- D+: 67-69
- D: 63-66
- D-: 60-62
- F: 0-59

## Homework Assignments
- Homework 1: TBD
- Homework 2: TBD
- Homework 3: TBD
- Homework 4: TBD

## Final Project
- Final Project: TBD



