

![Logo](https://www.pcimembranes.com/wp-content/uploads/2022/03/potable-water-treatments-1-scaled.jpg)




# Water Potability Prediction
This program analyzes water quality data to determine if the water is safe to drink or not. We've trained a combination of Random Forest and Decision Tree models for this purpose, expecting better output by merging these models. The user input interface is facilitated through Gradio services.
: 
```bash
https://www.kaggle.com/datasets/adityakadiwal/water-potability/data 
```

## 🛠 Skills
Data Analysis, Python.


## Running 

```bash
  Run in Python + IDE / Google Colab / JupyterNotebook
```


## Optimizations

Decision Tree modeling still has a poor level of accuracy, therefore optimization is needed using GridSearchCV & RepeatedStratifiedKFold.

```bash
 from sklearn.model_selection import GridSearchCV, RepeatedStratifiedKFold
```


## Roadmap

- Data Collection
- Data Cleaning
- EDA (Exploration Data Analysis)
- Pre and Post Data Cleaning
- Model Building
- Evaluation Model
- Validation Model
- Testing Model using Gradio

