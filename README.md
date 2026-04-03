# Employee-Attrition-prediction-XGBoost
​"Employee Attrition Prediction using XGBoost with 91.89% Accuracy. This project identifies key factors like Overtime that drive employee turnover."

# 👔 Employee Attrition Prediction Analysis (XGBoost)
# 👔 تحليل والتنبؤ باستقالة الموظفين باستخدام XGBoost

<div align="center">
  <img src="https://img.shields.io/badge/Accuracy-91.89%25-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Model-XGBoost-blue?style=for-the-badge" />
</div>

---

## 📌 1. Project Overview | نظرة عامة على المشروع
This project aims to solve a critical HR challenge: **Employee Turnover**. By analyzing historical data and using the **XGBoost** algorithm, we developed a predictive model that identifies which employees are likely to leave and why, achieving an accuracy of **91.89%**.

يهدف هذا المشروع إلى حل واحدة من أهم مشاكل الموارد البشرية وهي **دوران الموظفين**. من خلال تحليل البيانات التاريخية واستخدام خوارزمية **XGBoost**، قمنا بتطوير نموذج تنبؤي يحدد الموظفين المحتمل استقالتهم والأسباب الكامنة وراء ذلك، بدقة تصل إلى **91.89%**.

---

## ⚙️ 2. Data Preprocessing | معالجة البيانات
To ensure the highest model performance, the following steps were taken:
* **Feature Encoding:** Converted categorical columns like 'Business Travel' and 'Department' into numerical values using proper encoding techniques.
* **Outlier Handling:** Managed logical inconsistencies and extreme outliers that could negatively impact model accuracy.
* **Feature Scaling:** Standardized data to ensure all features contribute equally to the prediction.
لضمان أعلى أداء للنموذج، تم اتباع الخطوات التالية:
* **تحويل الأعمدة النصية (Encoding):** تحويل الأعمدة النصية مثل (نوع القسم، السفر للعمل) إلى أرقام لتسهيل معالجتها برمجياً.
* **التعامل مع القيم المتطرفة (Outliers):** التعامل مع أي بيانات غير منطقية أو قيم متطرفة قد تؤثر سلباً على دقة النموذج.
* **تحجيم البيانات (Scaling):** توحيد مقاييس البيانات لضمان دقة الحسابات الرياضية للموديل.

---

## 🧠 3. Model Architecture | بناء النموذج
We utilized **XGBoost (Extreme Gradient Boosting)**, a powerful ensemble learning method, optimized for speed and performance. The model was fine-tuned to balance precision and recall, especially given the imbalanced nature of attrition data.

تم استخدام خوارزمية **XGBoost**، وهي واحدة من أقوى تقنيات التعلم الجمعي (Ensemble Learning)، وتم تحسينها لضمان التوازن بين الدقة (Precision) والاستدعاء (Recall)، خاصة مع طبيعة بيانات الاستقالة غير المتوازنة.

---

## 📊 4. Model Performance & Results | أداء النموذج والنتائج

### 🟢 Confusion Matrix | مصفوفة الارتباك
![Confusion Matrix](<  <img width="546" height="455" alt="convfusion Matrix" src="https://github.com/user-attachments/assets/c0d28440-a4c6-4397-ab77-24caf3348305" />
   >)

​📊 Model Evaluation: Confusion Matrix Analysis

​The Confusion Matrix provides a detailed breakdown of our XGBoost model's performance in predicting employee turnover:
​True Negatives (Stayed): 232 employees were correctly predicted to stay.
​True Positives (Left): 15 employees were correctly predicted to leave.
​Key Insight: The model shows high reliability in identifying employees who will stay, helping HR focus on retention strategies where they are most needed.

​بالعربي

​تحليل مصفوفة الارتباك (Confusion Matrix):
توضح هذه المصفوفة دقة توقعات خوارزمية XGBoost؛ حيث نجح النموذج في تحديد 232 موظفاً سيستمرون في العمل بشكل صحيح، مما يعكس قدرة النموذج على تصنيف الحالات بدقة عالية ودعم اتخاذ القرارات الإدارية.

---

## 🛠️ 5. Tech Stack | التقنيات المستخدمة
* **Programming:** Python
* **Library:** XGBoost, Scikit-learn
* **Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
*
## 👤 Author
**[MOHAMED BELAL]** *Deep Learning & Data Engineering Enthusiast*

MY PHONE [01018689118]

