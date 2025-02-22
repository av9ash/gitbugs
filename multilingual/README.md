<a href="https://doi.org/10.48550/arXiv.2502.14338"><img src="https://zenodo.org/badge/DOI/10.48550/arXiv.2502.14338.svg" alt="DOI"></a>

## Usage Instructions
Follow these steps to generate and evaluate results:

1. **Run the Exploratory Data Analysis (EDA):**  
   Execute `multilingual_eda.ipynb` to generate the EDA based on the paper for this dataset.

2. **Evaluate Translations:**  
   Run `translation_evaluation.ipynb` to generate evaluation results.  
   - The results are stored as JSON files in their respective directories.

3. **Visualize Results:**  
   Execute `translation_result_graphs.ipynb` to generate:  
   - Evaluation results  
   - Confusion matrix  
   - Violin plots for further analysis

Ensure all dependencies are installed before running the notebooks.

## License and Citation
This project is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.  
Any use or reuse of this work must cite the following:

```bibtex
@misc{patil2025englishpleaseevaluatingmachine,
      title={English Please: Evaluating Machine Translation for Multilingual Bug Reports}, 
      author={Avinash Patil and Aryan Jadon},
      year={2025},
      eprint={2502.14338},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2502.14338}, 
}
```
For more details on the license, visit [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
