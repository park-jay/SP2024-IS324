# SP2024-IS324 Social Network Analysis
School of Information Sciences, University of Illinois at Urbana-Champaign \
Instructor: Jaihyun Park \
TA: Jinmo Kim \
Office Hours: Wednesdays 9:00-9:50 am (Zoom) 

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
    - Barlett et al. (2018). "The locus of legitimate interpretation in Big Data sciences: Lessons for computational social science from -omic biology and high-energy physics." *Big Data & Society*, 5(1), 1-15. [paper](https://journals-sagepub-com.proxy2.library.illinois.edu/doi/full/10.1177/2053951718768831) 
    - Lightning AI. "Jupyter Notebooks vs Python projects: Learn when when to use which | Ep1" [video](https://www.youtube.com/watch?v=JGnoTN1OnWY)
- Lab materials:
    - VS code. [link](https://code.visualstudio.com/)
    - Git. [link](https://github.com/git-guides/install-git#install-git)
    - Github. [link](https://github.com/)

Week 2: Anatomy of Network Analysis and Social Network Theories
- Basic constituents of a network: nodes, edges, and attributes 
- Types of networks: directed, undirected, weighted, and unweighted 
- Network measures: degree, betweenness, closeness, and eigenvector centrality 
- Social network theories: homophily, cognitive dissonance, echo chamber
- Discussion of transformation to a network structure of real-world scenarios 
- Discussion of network measures of real-world scenarios 
- Introduction to the Python environment (Anaconda), libraries for network analysis (Pandas, NetworkX, and Matplotlib)
- Lab Practice: Basic Python, Git and GitHub / Introduction to Pandas library
- Readings: 
    - Borgatti et al. (2009). "Network analysis in the social sciences." *Science*, 323(5916), 892-895. [paper](https://www.science.org/doi/full/10.1126/science.1165821?casa_token=JPDFoDdpKu8AAAAA%3Ao1DANHfT-4yRx1B_NEa7_1IrbSdAaSaOrHbplwO-GDzQvCUj8GU5ioRlC2_oGxCg19IQUdXyl44EPw)
    - Scott, J. (2017). "What is Social Network Analysis?" *The SAGE Handbook of Social Network Analysis*, 1-10. [paper](https://methods-sagepub-com.proxy2.library.illinois.edu/book/social-network-analysis-4e/i317.xml) 
    - Yang, S. et al. (2018). "Basics of Social Science Analysis." *The SAGE Handbook of Social Network Analysis: Methods and Examples*, 3-25. [paper](https://methods-sagepub-com.proxy2.library.illinois.edu/book/social-network-analysis-1e/i173.xml) 
    - Yang, S. et al. (2018). "Descriptive Methods in Social Network Analysis." *The SAGE Handbook of Social Network Analysis: Methods and Examples*, 54-85. [paper](https://methods-sagepub-com.proxy2.library.illinois.edu/book/social-network-analysis-1e/i328.xml) 
    - McPherson, M., Smith-Lovin, L., & Cook, J. M. (2001). Birds of a feather: Homophily in social networks. Annual review of sociology, 27(1), 415-444. [paper](https://www.annualreviews.org/doi/full/10.1146/annurev.soc.27.1.415?casa_token=fusufNevercAAAAA%3ACwOvY9hCbAjO795TJBB14c-JGljWqEz2p1M4AaEWG4oQOrXAqxc_ZYdba7cYsgDa3Q0YJKUReoQ4)
    - Festinger, L. (1962). Cognitive dissonance. Scientific American, 207(4), 93-106. [paper](https://www.jstor.org/stable/24936719?casa_token=NuPH_CGOIo4AAAAA%3AgFL4u5Aqgf6xSCjBqyaogKOroNWQcApz08LS8BMDiBXLuq4lrLd4GExX92AsiE1SzqEE1hKUrsiaOoINGDj1djvBbOZ-7q77leHSv86LJXuQVXLL9ik)
    - Jeong, M., Zo, H., Lee, C. H., & Ceran, Y. (2019). Feeling displeasure from online social media postings: A study using cognitive dissonance theory. Computers in Human Behavior, 97, 231-240. [paper](https://www.sciencedirect.com/science/article/pii/S0747563219300792?casa_token=0HSAkoYaP5kAAAAA:47vDFmYV9i6q7S_dL7HIOaqzVwMuc01Il4r1nk0n3INbHKAvhdwvjH0bGmGbrMb8LGBiMRdJGQ)

- Lab materials:
    - Python for Everybody (PY4E) [link](https://www.py4e.com/)
    - Pandas Cookbook [link](https://pandas.pydata.org/docs/user_guide/cookbook.html#cookbook)

<!--HW 1 Announcement: Due TBD-->

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
    - Ng, L. H. X., Cruickshank, I. J., & Carley, K. M. (2022). Cross-platform information spread during the january 6th capitol riots. Social Network Analysis and Mining, 12(1), 133. [paper](https://link-springer-com.proxy2.library.illinois.edu/article/10.1007/s13278-022-00937-1)
    - Stewart, L. G., Arif, A., & Starbird, K. (2018, February). Examining trolls and polarization with a retweet network. In Proc. ACM WSDM, workshop on misinformation and misbehavior mining on the web (Vol. 70). [paper](http://faculty.washington.edu/kstarbi/examining-trolls-polarization.pdf)
    - Garimella, K., Morales, G. D. F., Gionis, A., & Mathioudakis, M. (2018). Quantifying controversy on social media. ACM Transactions on Social Computing, 1(1), 1-27. [paper](https://dl.acm.org/doi/pdf/10.1145/3140565?casa_token=7mNQ97pvoTIAAAAA:NegRKeJJJfJCtaCyQFkaLSjWGm02CsjqKTVcKJ7LkINajczTfQr1cWOop4RB_T8NXCpHXvxy5mET)
- Useful sources: Regex Cheat Sheet, Regex Tester

Week 4: Email Network Analysis
- Affordances of email data for network analysis: sender, receiver, and cc
- Discussion of transformation to a network structure of email data
- Discussion of network measures of email data
- Lab Practice: Email network analysis (sender, receiver, and cc)
- Lab Practice: Transformation of email data to a network structure
- Readings: 
    - Park, J., Seo, J., & Lee, J. Y. (2023). Exploring an Online Community of Blind Programmers by Using Topic Modeling and Network Analysis. Proceedings of the Association for Information Science and Technology, 60(1), 1096-1098. [paper](https://asistdl-onlinelibrary-wiley-com.proxy2.library.illinois.edu/doi/full/10.1002/pra2.956)
- Useful sources: Harvard Dataverse, Zenodo, data.world (e.g., [Enron email dataset](https://data.world/brianray/enron-email-dataset))

HW 1 Due: Essay

Week 5: Text Reprint Network Analysis  
- Affordances of text data for network analysis: co-occurrence of words
- Discussion of transformation to a network structure of text data
- Discussion of bias in digitized text data
- Lab Practice: N-gram analysis for text data
- Readings: 
    - Smith, D. A., Cordell, R., Dillon, E. M., Stramp, N., & Wilkerson, J. (2014, September). Detecting and modeling local text reuse. In IEEE/ACM Joint Conference on Digital Libraries (pp. 183-192). IEEE [paper](https://ieeexplore.ieee.org/abstract/document/6970166?casa_token=hM_6Ui1E00IAAAAA:btt1A3g4lerzn2pOWreQrJQZpAhvt2h741jzf7aEdhfZN-gBz4RTYu9gEfIyko5PTUSD_gl_Aw)
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
<!-- - Readings: TBD-->

HW 2 Due: Regular Expression

Week 7: Social Media Network Analysis with NextworkX (Connects back to Week 3)
- Transformation of social media data to a network structure in NetworkX
- Calculation of network measures of social media data in NetworkX
- Lab Practice: NetworkX library for representing social media data
- Lab Practice: NetworkX library for calculating network measures of social media data
<!-- - Readings: TBD-->

Week 8: Email Network Analysis with NextworkX (Connects back to Week 4)
- Transformation of email data to a network structure in NetworkX
- Calculation of network measures of email data in NetworkX
- Lab Practice: NetworkX library for representing email data
- Lab Practice: NetworkX library for calculating network measures of email data
<!-- - Readings: TBD -->

Week 9: Spring Break

Week 10: Text Reprint Network Analysis with NextworkX (Connects back to Week 5)
- Transformation of text data to a network structure in NetworkX
- Calculation of network measures of text data in NetworkX
- Lab Practice: NetworkX library for representing text data
- Lab Practice: NetworkX library for calculating network measures of text data
<!-- - Readings: TBD -->

HW 3 Due: NetworkX objects

<!--Week 11: Network Visualization (Connects back to Week 2)-->
<!--- Readings: TBD-->

Week 11: Group Project Proposal
- Group Project Proposal (15 mins + 5 mins Q&A)

Week 12: Social Media Network Visualization (Connects back to Week 3)
- Introduction to Matplotlib library
- Visualization of a network structure in Matplotlib
- Visualization of social media data in Matplotlib
- Lab Practice: Matplotlib library for visualizing a network structure
- Lab Practice: Matplotlib library for visualizing social media data
<!-- - Readings: TBD -->

Week 13: Email Network Visualization (Connects back to Week 4)
- Visualization of email data in Matplotlib
- Lab Practice: Matplotlib library for visualizing email data
<!-- - Readings: TBD -->

<!--Week 14: Text Reprint Network Visualization (Connects back to Week 5)
- Visualization of text data in Matplotlib
- Lab Practice: Matplotlib library for visualizing text data
- Readings: TBD
-->
HW 4 Due: TBD & GitHub Classroom (Network Visualization)

Week 14: Final Group Help Session

Week 15: Final Group Project Presentation 
- Final Project Presentation (25 mins + 5 mins Q&A)

Week 16: Final Group Project Presentation
- Final Project Presentation (25 mins + 5 mins Q&A)

## Course Requirements
- Attendance and participation (20%)
- Homework assignments (40%)
- Group project proposal (10%)
- Group project (30%)
- Students peer review for final project (Earn extra credit)

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
- Homework 1: Write an essay on the application of social network analysis to your research interest. The essay should include (1) a brief description of your research interest, (2) a brief description of the application of social network analysis to your research interest, and (3) a brief description of the data that you will use for the application of social network analysis to your research interest. The essay should be no longer than 5 pages (double-spaced, 12-point font, 1-inch margin).

- Homework 2: Practice regular expression with a given dataset (e.g., email data, social media data, and text data). In this assignment, students will be given a random type of dataset (e.g., email data, social media data, and text data) and will use regular expression to extract nodes and transform the dataset into pandas data frame. Document the process of extracting nodes and transforming the dataset into pandas data frame in a Jupyter notebook. The Jupyter notebook should include (1) a brief description of the dataset, (2) a brief description of the process of extracting nodes and transforming the dataset into pandas data frame, and (3) a brief description of the pandas data frame. The assignment should be submitted as a Jupyter notebook file (.ipynb) and a html file (.html).

- Homework 3: Create a networkX object from a given dataset (e.g., email data, social media data, and text data). In this assignment, students will be given a random type of dataset (e.g., email data, social media data, and text data) and will use regular expression to extract nodes and transform the dataset into pandas data frame. Then, students will use networkX library to create a networkX object. The networkX object should include (1) nodes, (2) edges, and (3) attributes for nodes and edges. Document the process of creating the networkX object in a Jupyter notebook. The Jupyter notebook should include (1) a brief description of the dataset, (2) a brief description of the process of creating the networkX object, and (3) a brief description of the networkX object. The assignment should be submitted as a Jupyter notebook file (.ipynb) and a html file (.html). 

- Homework 4: Visualize a network structure with a given dataset (e.g., email data, social media data, and text data). In this assignment, students will be given a random type of dataset (e.g., email data, social media data, and text data) and will use regular expression to extract nodes and transform the dataset into pandas data frame. Then, students will use networkX library to create a networkX object. Finally, students will use Matplotlib library to visualize the network structure. The visualization should include (1) nodes, (2) edges, and (3) attributes for nodes and edges. Document the process of visualizing the network structure in a Jupyter notebook. The Jupyter notebook should include (1) a brief description of the dataset, (2) a brief description of the process of visualizing the network structure, and (3) a brief description of the visualization. The assignment should be submitted as a Jupyter notebook file (.ipynb) and a html file (.html).

## Final Project Proposal
- Final Project Proposal: Students will propose a final project. Students will propose a dataset and a research question. The final project proposal should include (1) social theory that you will use for the final project, (2) where you will get the data, (3) how you will transform the data into a network structure, (4) how you will analyze the network structure, and (5) how you will visualize the network structure. The final project proposal should be submitted as a Word file (.docx) with no more than 10 pages (double-spaced, 12-point font, 1-inch margin) and the proposal presentation should be no longer than 15 minutes (10 minutes presentation + 5 minutes Q&A).

## Final Project
- Final Project: Students will work in groups of 2-3 to complete a final project. The final project should include (1) a brief description of the dataset, (2) a brief description of the process of extracting nodes and transforming the dataset into pandas data frame, (3) a brief description of the process of creating the networkX object, (4) a brief description of the process of visualizing the network structure, and (5) a brief description of the visualization. The final project should be submitted as a Jupyter notebook file (.ipynb) and a html file (.html). The final project presentation will also include what you have learned from the network analysis of the dataset. The final project presentation should be no longer than 25 minutes (20 minutes presentation + 5 minutes Q&A).



