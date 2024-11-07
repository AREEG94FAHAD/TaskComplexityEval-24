# TaskComplexity Dataset [👉Read the paper](https://arxiv.org/abs/2409.20189)

This project addresses the challenge of classifying and assigning programming tasks. A novel dataset containing a total of **4,112 programming tasks** was created by systematically extracting tasks from various websites using web scraping techniques.

## Dataset Overview [download](https://github.com/AREEG94FAHAD/TaskComplexityEval-24/blob/main/problems_data.jsonl)

The **TaskComplexity** dataset provides a comprehensive collection of programming problems, each labeled by classification, enabling the development and evaluation of models based on task difficulty.

### Features

Each entry in the dataset includes the following attributes:

- **Task Title**: The name or title of the programming problem.
- **Problem Description**: A detailed description of the programming task.
- **Input/Output Specification**: A breakdown of the expected input and output for the problem.
- **Examples**: Sample cases to clarify the task requirements.
- **Problem Class**: A categorical label indicating the general type of problem.
- **Complexity Score**: A difficulty rating to help classify the problem’s complexity.

<img src="https://github.com/user-attachments/assets/dfbabe65-7788-4892-a692-1360b41f5c75" alt="TaskComplexity Dataset Image" width="500">


### Complexity Levels

The dataset categorizes tasks into three levels of complexity:

- **Easy**
- **Medium**
- **Hard**

### Applications

This dataset is designed to support research and development in:

- **Machine Learning Models**: Building classification models to assign complexity levels to programming tasks.


## Technical Details

- **Total Tasks**: 4,112
- **Number of Classes**: 3 (Easy, Medium, Hard)
- **Data Collection Method**: Web scraping of programming problem websites

## Citation

If you find this work useful for your research, please consider citing the paper:

```bibtex
@article{rasheed2024taskcomplexity,
  title={TaskComplexity: A Dataset for Task Complexity Classification with In-Context Learning, FLAN-T5 and GPT-4o Benchmarks},
  author={Areeg Fahad Rasheed, M. Zarkoosh, Safa F. Abbas, Sana Sabah Al-Azzawi},
  journal={arXiv preprint arXiv:2409.20189},
  year={2024}
  dio={https://arxiv.org/abs/2409.20189}
}
```
