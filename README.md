# Applied ML Coursework Skill

A reusable AI skill for applied machine learning, data science, and data mining coursework.

It helps students go from:

**assignment brief → experiment design → notebook implementation → model evaluation → report writing → final submission check**

---

## Features

This skill can help with:

* Reading and understanding assignment briefs
* Identifying required tasks, algorithms, metrics, and deliverables
* Planning Jupyter Notebook structure
* Exploratory data analysis
* Data preprocessing and feature engineering
* Data leakage checks
* Classification
* Regression
* Clustering
* Association Rule Mining
* Text Mining
* Time Series Prediction
* Model evaluation and comparison
* Result interpretation
* Academic report writing
* Final submission checking

---

## Key Principle

### Do Not Invent Results

The skill only uses actual outputs from the user's:

* dataset
* notebook
* screenshots
* experiment results
* provided files

It should never fabricate:

* Accuracy
* Precision / Recall / F1-score
* Confusion matrix values
* Clustering results
* Association rules
* Dataset details
* References or citations

If a result is missing, the user should run the notebook first.

---

## Workflow

```text
Assignment Brief
      ↓
Requirement Analysis
      ↓
Dataset Inspection
      ↓
Data Leakage Check
      ↓
EDA
      ↓
Preprocessing
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Evaluation
      ↓
Result Interpretation
      ↓
Report Writing
      ↓
Final Submission Check
```

---

## Supported Tasks

### Classification

Supports workflows including:

* train/test split
* multiple model comparison
* accuracy
* precision
* recall
* F1-score
* confusion matrix
* error analysis

For multi-class problems, macro and weighted metrics can be compared.

### Regression

Supports:

* MAE
* MSE
* RMSE
* R²
* prediction error analysis

### Clustering

Supports:

* K-Means
* cluster interpretation
* Elbow Method
* cluster visualization
* selection of suitable `k`

### Association Rule Mining

Supports:

* transaction preparation
* frequent itemsets
* support
* confidence
* lift
* rule interpretation

### Text Mining

Supports simple workflows using:

* text cleaning
* TF-IDF
* TruncatedSVD
* classification or clustering

---

## Installation

Clone this repository:

```bash
git clone https://github.com/your-username/applied-ml-coursework-skill.git
```

Then copy the skill file into the skill directory used by your AI coding or agent environment.

For example:

```text
skills/
└── applied-ml-coursework/
    └── SKILL.md
```

The exact installation method depends on the AI agent or coding environment you are using.

---

## Usage

Once the skill is installed, provide your coursework materials to the AI assistant.

For example:

```text
Please use the Applied ML Coursework Skill.

Here is my assignment brief and dataset.

First, analyse the assignment requirements and tell me:
1. What tasks I need to complete
2. Which algorithms are required
3. Which evaluation metrics I should use
4. How I should structure my notebook
```

You can also use it later in the workflow:

```text
Review my notebook and check whether there is any data leakage.
```

```text
Interpret these classification results and help me write the Results section.
```

```text
Check my final report against the assignment requirements.
```

---

## Example

Suppose an assignment requires students to compare three classification algorithms.

The skill may structure the work as:

```text
1. Understand the dataset
2. Identify features and target
3. Remove leakage columns
4. Perform focused EDA
5. Split train/test data
6. Apply preprocessing
7. Train three classifiers
8. Calculate Accuracy, Precision, Recall and F1
9. Generate confusion matrices
10. Compare models
11. Explain the best-performing model
12. Write Results and Discussion
```

The skill does not generate fake performance numbers.

It waits for real notebook outputs before interpreting the results.

---

## Suggested Project Structure

```text
applied-ml-coursework-skill/
│
├── README.md
├── SKILL.md
├── LICENSE
│
└── examples/
    ├── classification-example.md
    ├── clustering-example.md
    └── association-rule-mining-example.md
```

---

## Example Prompts

### Assignment Analysis

```text
Read this assignment brief and identify all required tasks, algorithms, metrics and deliverables.
```

### Notebook Planning

```text
Design a clean Jupyter Notebook structure for this coursework.
```

### Data Leakage

```text
Review these dataset columns and identify possible data leakage.
```

### Model Evaluation

```text
Compare these model results using accuracy, macro precision, macro recall and macro F1-score.
```

### Report Writing

```text
Use my actual notebook results to draft the Results and Discussion section in simple academic English.
```

### Final Check

```text
Check whether my notebook and report satisfy all assignment requirements.
```

---

## Design Philosophy

This skill is designed around three principles:

**1. Coursework-first**

Focus on assignment requirements instead of unnecessary modelling complexity.

**2. Evidence-based**

Only interpret real experiment outputs.

**3. Simple academic writing**

Prefer clear and understandable explanations over overly complex or generic AI-generated language.

---

## Limitations

This skill does not replace:

* running experiments
* understanding the dataset
* checking university academic integrity requirements
* reviewing final results manually

Different universities and modules may also have different requirements, so the assignment brief and rubric should always take priority.

---

## Roadmap

Possible future improvements:

* Automatic rubric checking
* Notebook quality review
* Report consistency checking
* Experiment reproducibility checks
* Automatic figure and table checklist
* Citation verification
* Support for more ML coursework templates

---

## Contributing

Contributions are welcome.

You can contribute by:

* improving the workflow
* adding examples
* adding support for new ML tasks
* improving report-writing guidance
* adding notebook review rules

Feel free to open an Issue or Pull Request.

---

## License

MIT License

---

## Disclaimer

This project is intended as a learning and coursework support tool.

Users should follow their university's academic integrity and AI usage policies.
