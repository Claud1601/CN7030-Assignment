# Contributors - Group 22
## CN7030 Machine Learning on Big Data (T3) - Forest CoverType Prediction

---

## Team Members

### 1. **Silakshana Dinesh** (3263086)
- **Role:** Lead Data Preprocessing & Analysis
- **Responsibilities:**
  - Dataset loading and exploration
  - Missing value and duplicate analysis
  - Class distribution analysis and visualization
  - Data quality checks
  
---

### 2. **Hemanth Sai Gude**
- **Role:** Model Implementation & Evaluation
- **Responsibilities:**
  - Decision Tree baseline model implementation
  - Random Forest classifier development
  - Model evaluation metrics (Accuracy, Precision, Recall, F1-Score)
  - Confusion matrix generation
  
---

### 3. **Vishal Bhai**
- **Role:** Hyperparameter Optimization & Testing
- **Responsibilities:**
  - Hyperparameter tuning using GridSearchCV/ParamGridBuilder
  - Cross-validation implementation
  - Model performance comparison
  - Repeated experiments and statistical analysis
  
---

### 4. **Priya**
- **Role:** Feature Engineering & Analysis
- **Responsibilities:**
  - Feature importance analysis
  - Feature scaling considerations
  - Handling class imbalance strategies
  - LSEP (Legal, Social, Ethical, Professional) analysis
  
---

## Project Structure

```
CN7030-Assignment/
├── Group_22_CRWK_CN7030_Forest_CoverType.ipynb  (Main notebook)
├── CONTRIBUTORS.md                              (This file)
├── README.md                                    (Project overview)
└── results/                                     (Output folder for results)
    ├── model_performance.csv
    ├── confusion_matrix.png
    └── feature_importance.png
```

---

## Task Breakdown

| Task | Marks | Primary Owner | Contributors |
|------|-------|---------------|--------------|
| Task 1: Data & Research Objectives | 10 | Silakshana | All |
| Task 2: Data Loading & Preprocessing | 15 | Silakshana, Priya | Hemanth, Vishal |
| Task 3: Model Selection & Implementation | 15 | Hemanth | Vishal, Silakshana |
| Task 4: Model Evaluation & Comparison | 20 | Hemanth, Vishal | Priya |
| Task 5: Hyperparameter Optimization | 15 | Vishal | Hemanth |
| Task 6: LSEP Analysis | 15 | Priya | All |
| Task 7: Final Report | 10 | All | All |

---

## Communication Guidelines

- **Daily Updates:** Brief status in comments section of notebook
- **Code Changes:** Always use meaningful commit messages
- **Conflicts:** Tag all team members in comments if issues arise
- **Review:** Before final submission, all cells should be reviewed by at least 2 team members

---

## Important Dates & Deadlines

- **Code Development:** By [DATE]
- **Testing & Validation:** By [DATE]
- **Final Report Writing:** By [DATE]
- **Final Submission:** [SUBMISSION DATE]

---

## Key Deliverables Checklist

- [ ] Dataset loaded and explored
- [ ] Missing values & duplicates verified (0 found)
- [ ] Class distribution analyzed
- [ ] Features vectorized using VectorAssembler
- [ ] 80/20 train-test split completed
- [ ] Decision Tree baseline trained & evaluated
- [ ] Random Forest classifier trained & evaluated
- [ ] Hyperparameters optimized
- [ ] All evaluation metrics computed
- [ ] Confusion matrix generated
- [ ] Feature importance extracted
- [ ] Reproducibility metrics reported (mean ± std dev)
- [ ] LSEP analysis completed
- [ ] Final report written

---

## References & Resources

- **Dataset:** Forest CoverType Dataset (UCI ML Repository)
- **Framework:** Apache Spark 4.0.4 with PySpark ML
- **Tools:** Google Colab, Jupyter Notebook
- **Documentation:** [PySpark ML Documentation](https://spark.apache.org/docs/latest/ml-guide.html)

---

## Notes

- All models use seed=42 for reproducibility
- No feature scaling applied to tree-based models
- Class weighting implemented to handle imbalanced data
- All results should include mean performance ± standard deviation from multiple runs

---

**Last Updated:** August 21, 2026
**Status:** Active Development
