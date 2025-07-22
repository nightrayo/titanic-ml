### **titanic-ml**

This project is a solution to a classification problem: to predict whether a Titanic passenger survived based on characteristics such as gender, age, ticket class, and others.

#### 🚀 technologies used

- **Python**
- **Libraries**
  - **scikit-learn**
  - **pandas**

#### 🧠 Goal

Learn to apply Ml algorithms to a practical problem, including:
- Data preprocessing
- Feature engineering
- Model training and evaluation

#### 🏆 Results

| Model                  | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| LogisticRegression     | 0.94     | 0.91      | 0.93   | 0.92     |
| GradientBoosting       | 0.89     | 0.89      | 0.80   | 0.84     |
| RandomForest           | 0.86     | 0.81      | 0.80   | 0.81     |

The LogisticRegression model achieved the highest accuracy (94%) and balanced performance across all metrics.

#### Formulas

Accuracy - доля верных ответов модели от общего числа примеров.

$$\text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN}$$

где:  
- TP - True Positive (правильные положительные предсказания)  
- TN - True Negative (правильные отрицательные предсказания)  
- FP - False Positive (ложноположительные предсказания)  
- FN - False Negative (ложноотрицательные предсказания)

---

Precision - метрика, которая показывает, какая доля объектов, предсказанных как положительные, действительно являются положительными.

$$\text{Precision} = \frac{TP}{TP + FP}$$

Где:
- TP - True Positive (истинно положительные)
- FP - False Positive (ложноположительные)

---

Recall показывает, какую долю настоящих положительных объектов модель смогла правильно предсказать.

$$\text{Recall} = \frac{TP}{TP + FN}$$

Где:
- TP - True Positive (истинно положительные)
- FN - False Negative (ложноотрицательные)

---

F1 Score — это гармоническое среднее между Precision и Recall. Он используется, когда важно учитывать как ложноположительные, так и ложноотрицательные ошибки, особенно при несбалансированных классах.

$$\text{F1} = 2 \cdot \frac{\text{Precision} \cdot \text{Recall}}{\text{Precision} + \text{Recall}}$$

---

MSE — это среднеквадратичная ошибка, одна из ключевых метрик в задачах регрессии. Она измеряет среднее значение квадратов ошибок между предсказанными и истинными значениями.

$$\text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$$

где:
- y_i — истинное значение,
- ŷ_i — предсказанное значение,
- n — количество наблюдений.
