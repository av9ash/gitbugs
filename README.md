# GitBugs
[![DOI](https://zenodo.org/badge/678604821.svg)](https://zenodo.org/badge/latestdoi/678604821)

## License and Citation
This project is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.  
Any use or reuse of this work must cite the following:

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

HOW TO USE

Upload the json zip file to your google drive and change the "%cd /gdrive/MyDrive/Colab\ Notebooks" in the below notebook.

How to Use: Following Notebook will load the original bugs from json, make them into a vectors using TFIDF and search top n neighbors using SKlearn Nearest Neighbors https://colab.research.google.com/drive/1Uc9hTvBAjdF7oalpk2zoq7QJO6q7mzq6?usp=sharing

https://medium.com/@avinash.patil.0909/duplicate-bug-reports-detection-using-ml-925ef6409394

About

The data set has 32829 records. Date Range Oct2015 - Jul2024

## Bug Report Datasets:
Summary: Bugs from some popular projects on github.

Description: A collection of bug reports that are publicly available for research purposes. Bug reports are a main data source for facilitating NLP-based research in software engineering.

1) **multilingual**:  Bug reports from microsoft/vscode repo reported in lanugages other than english (Multilingual Bug Reports).
2) **ms_vscode_bugs**: Bug reports from microsoft/vscode contains all original reports, all duplicate reports and a duplicate to original mapping dictionary.
