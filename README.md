# 🌾 Smart Agriculture using Machine Learning for Enhanced Crop Recommendation
![Screenshot 2025-06-11 232159](https://github.com/user-attachments/assets/00c1de7d-240a-4059-8571-93a135a1b06c)

## 📌 Project Overview

This project presents a Smart Agriculture solution that uses **ensemble machine learning models** to recommend the most suitable crop based on environmental conditions and soil nutrients. The model helps farmers make informed decisions by considering **Nitrogen (N)**, **Phosphorus (P)**, **Potassium (K)**, **temperature**, **humidity**, **pH**, and **rainfall**.  
Built using:
- Random Forest
- Gradient Boosting
- Extra Trees Classifier
- Soft Voting Ensemble

The recommendation system also retrieves **key farming tips** using real-time Google search.

## 📂 Files in This Repository

| File | Description |
|------|-------------|
| `Smart_Agriculture.ipynb` | Jupyter Notebook with code for data cleaning, model training, prediction, and web scraping. |
| `Smart Agriculture using Machine Learning for Enhanced Crop Recommendation.docx` | Full project report detailing methodology, algorithms, results, and references. |
| `README.md` | You’re reading it. |

## 🛠️ Setup Instructions

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/smart-agriculture-ml.git
    cd smart-agriculture-ml
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    *(Manually install if `requirements.txt` is not present: pandas, scikit-learn, beautifulsoup4, requests)*

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Smart_Agriculture.ipynb
    ```

## 🌱 Sample Input and Output

### 🧪 Input

```python
n = 90
p = 42
k = 43
temperature = 20.8797
humidity = 82.0027
ph = 6.50299
rainfall = 202.936
