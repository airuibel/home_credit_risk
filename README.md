# home_credit_risk

### Feature Engineering (data.ipynb)——PAN

- Continuous variables: mean, min, max, std
- Categorical variables: ratio of each value
- Table of number of generated features.

### Feature Selection (becnhmark.ipynb)——GAN

- WOE and IV: select features with IV larger than 0.02
- Feature Importance: using median to filter features 
- Table of number of selected features.

### Data Processing (model.ipynb)——Meng

- fill in missing values: 0xdeadbeef
- split dataset into training set and validation set (8:2)

### Modeling (model.ipynb)——Yuan & Zheng

- Random Forest (Benchmark,introduction)
- LightGBM (introduction)
- Tuning parameters: cross validation (3 fold) RandomizedsearchCV
- Top-N important features
- Evaluation: AUC, KS (2 x 2 Pictures, table)

### Conclusion——Meng
