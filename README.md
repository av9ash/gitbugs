# GitBugs
[![DOI](https://zenodo.org/badge/DOI/10.48550/arXiv.2504.09651.svg)](https://doi.org/10.48550/arXiv.2504.09651)




## License and Citation
This project is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.  
Any use or reuse of this work please cite the following:

```
@INPROCEEDINGS{10512000,
  author={Patil, Avinash and Han, Kihwan and Jadon, Aryan},
  booktitle={2024 11th International Conference on Signal Processing and Integrated Networks (SPIN)}, 
  title={A Comparative Analysis of Text Embedding Models for Bug Report Semantic Similarity}, 
  year={2024},
  volume={},
  number={},
  pages={262-267},
  keywords={Training;Analytical models;Limiting;Databases;Computer bugs;Semantics;Software systems;ADA;BERT;Bug Reports;Defect Reports;Duplicate Detection;Embeddings;FastText;Gensim;GPT3;GPT3.5;Information Retrieval;Large Language Models;LLM;Natural Language Processing;Sentence Textual Similarity;Similarity Search},
  doi={10.1109/SPIN60856.2024.10512000}}
```

For more details on the license, visit [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).


## Bug Report Datasets: Bugs from some popular open source projects.

## Column Description
**Summary:** Short description of the issue.

**Issue ID:** Unique identifier.

**Status:** The current state of the issue (e.g., Open, Resolved).

**Priority:** The assigned importance level (e.g., Blocker, Critical).

**Resolution:** The outcome of the issue (e.g., Fixed, Duplicate). Some values are missing.

**Created:** The timestamp when the issue was created.

**Resolved:** The timestamp when the issue was resolved. Many are missing.

**Affects Version/s:** The Hadoop version(s) impacted by the bug.

**Description:** A detailed description of the bug. Some values are missing.


| Project          |              Total Bug Reports |              Duplicates |
| :--------------- | -----------------------: | -----------------------: |
| Cassandra     | 4,612 | 300 | 
| Firefox          |  28824 |    6255|
| Hadoop      |   2503 |   128 |   
| Hbase |   5403 |   108 |
| Mozilla Core              |   85673 |    17899 |
| VS Code            |    32829 |    9272 |
| Seamonkey           |       1076 |        120 |
| Spark        |        20275 |        497 |
| Thunderbird             |     15192 |      4200 |





## More information copied from Logpai/Bugrepo


# BugRepo

BugRepo maintains a collection of bug reports that are publicly available for research purposes. Bug reports are a main data source for facilitating NLP-based research in software engineering. We categorize the datasets into the following research directions.

**Newer Publications**
+ [**I2CT'23**] Avinash Patil, Aryan Jadon. [Auto-labelling of bug report using natural language processing](https://ieeexplore.ieee.org/document/10126470), *IEEE 8th International Conference for Convergence in Technology (I2CT)*, 2023.
+ [**SPIN'24**] Avinash Patil, Kihwan Han, Aryan Jadon. [A comparative analysis of text embedding models for bug report semantic similarity](https://ieeexplore.ieee.org/document/10512000), *11th International Conference on Signal Processing and Integrated Networks (SPIN)*, 2024.
+ [**Authorea'24**] Avinash Patil, Aryan Jadon. [Next-Generation Bug Reporting: Enhancing Development with AI Automation](https://www.techrxiv.org/doi/full/10.36227/techrxiv.173014394.42883558), *Authorea Preprints*, 2024.
+ [**arXiv'25**] Avinash Patil, Aryan Jadon. [English Please: Evaluating Machine Translation for Multilingual Bug Reports](https://arxiv.org/abs/2502.14338), *arXiv preprint*, 2025.


**Previous Publications**
+ [**ICSE'07**] Per Runeson, Magnus Alexandersson, Oskar Nyholm. [Detection of Duplicate Defect Reports Using Natural Language Processing](https://ieeexplore.ieee.org/document/4222611/), *International Conference on Software Engineering (ICSE)*, 2007.
+ [**ICSE'10**] Chengnian Sun, David Lo, Xiaoyin Wang, Jing Jiang, Siau-Cheng Khoo. [A Discriminative Model Approach for Accurate Duplicate Bug Report Retrieval](https://ieeexplore.ieee.org/document/6062072/), *International Conference on Software Engineering (ICSE)*, 2010.
+ [**ASE'11**] Chengnian Sun, David Lo, Siau-Cheng Khoo, Jing Jiang. [Towards More Accurate Retrieval of Duplicate Bug Reports](https://ieeexplore.ieee.org/document/6100061), *IEEE/ACM International Conference on Automated Software Engineering (ASE)*, 2011.
+ [**ASE'12**] Anh Tuan Nguyen, Tung Thanh Nguyen, Tien N. Nguyen, David Lo, Chengnian Sun. [Duplicate Bug Report Detection With a Combination of Information Retrieval and Topic Modeling](http://www.comp.nus.edu.sg/~specmine/suncn/papers/ase12.pdf), *IEEE/ACM International Conference on Automated Software Engineering (ASE)*, 2012.
+ [**ISSRE'16**] Xinli Yang, David Lo, Xin Xia, Lingfeng Bao, Jianling Sun. [Combining Word Embedding with Information Retrieval to Recommend Similar Bug Reports](https://ieeexplore.ieee.org/document/7774514/), *IEEE International Symposium on Software Reliability Engineering (ISSRE)*, 2016.
+ [**TSE'17**] Mohamed Sami Rakha, Cor-Paul Bezemer, Ahmed E. Hassan. [Revisiting the Performance Evaluation of Automated Approaches for the Retrieval of Duplicate Issue Reports](https://ieeexplore.ieee.org/document/8048025/), *IEEE Transactions on Software Engineering (TSE)*, 2017.
+ [**ICSE'18**] Amar Budhiraja, Raghu Reddy, Manish Shrivastava. [LWE: LDA Refined Word Embeddings for Duplicate Bug Report Detection](https://dl.acm.org/citation.cfm?id=3195078), *International Conference on Software Engineering (ICSE)*, 2018.
+ [**ICSE'18**] Amar Budhiraja, Kartik Dutta, Raghu Reddy, Manish Shrivastava. [DWEN: Deep Word Embedding Network for Duplicate Bug Report Detection in Software Repositories](https://dl.acm.org/citation.cfm?id=3183440.3195092), *International Conference on Software Engineering (ICSE)*, 2018.

### 2. Bug localization

Bug localization is a process to map a bug report to the corresponding buggy source file. This dataset contains bug reports, commit history, and API descriptions of six open source Java projects including Eclipse Platform UI, SWT, JDT, AspectJ, Birt, and Tomcat. The dataset is currently available [here](http://openscience.us/repo/issues/bugfiles.html).

| Project  | Timespan                | #Bugs mapped |
| :-------- | -----------------------: | --------------: |
| AspectJ  | 2002-03-13 ~ 2014-01-10 | 593            |
| Birt     | 2005-06-14 ~ 2013-12-19 | 4,178           |
| Eclipse  | 2001-10-10 ~ 2014-01-17 | 6,495           |
| JDT      | 2001-10-10 ~ 2014-01-14 | 6,274           |
| SWT      | 2002-02-19 ~ 2014-01-17 | 4,151           |
| Tomcat   | 2002-07-06 ~ 2014-01-18 | 1,056           | 

**Publications**

+ [**FSE'14**] Xin Ye, Razvan C. Bunescu, Chang Liu. [Learning to Rank Relevant Files for Bug Reports using Domain Knowledge](http://ace.cs.ohiou.edu/~razvan/papers/fse14.pdf), *ACM SIGSOFT International Symposium on Foundations of Software Engineering (FSE)*, 2014.
+ [**TSE'16**] Xin Ye, Razvan C. Bunescu, Chang Liu. [Mapping Bug Reports to Relevant Files: A Ranking Model, a Fine-Grained Benchmark, and Feature Evaluation](https://ieeexplore.ieee.org/document/7270328/), *IEEE Transactions on Software Engineering (TSE)*, 2016.
+ [**ICSE'16**] Xin Ye, Hui Shen, Xiao Ma, Razvan C. Bunescu, Chang Liu．[From Word Embeddings to Document Similarities for Improved Information Retrieval in Software Engineering](https://ieeexplore.ieee.org/document/7886921/), *International Conference on Software Engineering (ICSE)*, 2016.
+ [**IJCAI'16**] Xuan Huo, Ming Li, Zhi-Hua Zhou. [Learning Unified Features from Natural and Programming Languages for Locating Buggy Source Code](https://www.ijcai.org/Proceedings/16/Papers/230.pdf), *International Joint Conference on Artificial Intelligence (IJCAI)*, 2016.
+ [**IJCAI'17**] Xuan Huo, Ming Li. [Enhancing the Unified Features to Locate Buggy Files by Exploiting the Sequential Nature of Source Code](https://www.ijcai.org/proceedings/2017/0265.pdf), *International Joint Conference on Artificial Intelligence (IJCAI)*, 2017.


### 3. Bug triaging

Given a software bug report, bug triaging is the process to identify an appropriate developer who could fix the bug. Automatic bug triaging algorithm can be formulated as a classification problem, which takes the bug title and description as the input, mapping it to one of the available developers (class labels). The dataset is currently available [here](http://bugtriage.mybluemix.net/).

| Project      | \#Bugs  | \#Bugs for classifier |
| :------------ | -------: | ---------------------: |
| Chromium     | 383,104 | 118,643               |
| Mozilla Core | 314,388 | 128,215               |
| Firefox      | 162,307 | 24,214                |

**Publications**

+ Senthil Mani, Anush Sankaran, Rahul Aralikatte. [BugTriage: Exploring the Effectiveness of Deep Learning for Bug Triaging](http://bugtriage.mybluemix.net/paper/DeepTriage.pdf), *Arxiv*, 2018.


### 4. Bug-fixing time estimation
The bug report datasets hosted in this repository contain detailed information about bug fixing time tracking, which can thus be used for research on bug-fixing time estimation.

**Publications**

+ [**ICSE'13**] Hongyu Zhang, Liang Gong, Steven Versteeg. [Predicting Bug-fixing Time: an Empirical Study of Commercial Software Projects](https://www.researchgate.net/publication/261314373_Predicting_bug-fixing_time_An_empirical_study_of_commercial_software_projects), *International Conference on Software Engineering (ICSE)*, 2013.
+ [**MSR'11**] Pamela Bhattacharya, Iulian Neamtiu. [Bug-fix Time Prediction Models: Can We Do Better?](http://alumni.cs.ucr.edu/~pamelab/bugfixtime.pdf), *International Working Conference on Mining Software Repositories (MSR)*, 2011.

### 5. Bug information mining
Lamkanfi et al. [MSR'13] contributed a dataset with over 200.000 reported bugs extracted from the Eclipse and Mozilla projects. Besides providing a single snapshot of a bug report, they also include all the incremental modifications as performed during the lifetime of the bug report. The dataset is currently available [here](https://github.com/ansymo/msr2013-bug_dataset).

| Project          | \#Components | \#Bugs |
| :---------------- | ------------: | ------: |
| Eclipse Platform | 22           | 24,775 |
| JDT              | 6            | 10,814 |
| CDT              | 20           | 5,640  |
| GEF              | 5            | 5,655  |
| Mozilla Core     | 137          | 74,292 |
| Firefox          | 47           | 69,879 |
| Thunderbird      | 23           | 19,237 |
| Bugzilla         | 21           | 4,616  |

**Publications**

+ [**MSR'13**] Ahmed Lamkanfi and Javier Perez and Serge Demeyer. The Eclipse and Mozilla Defect Tracking Dataset: a Genuine Dataset for Mining Bug Information. *International Working Conference on Mining Software Repositories (MSR)*, 2013.



