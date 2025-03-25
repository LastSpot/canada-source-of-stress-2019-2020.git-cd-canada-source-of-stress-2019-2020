# Stress Factors Analysis 📊

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Latest-orange.svg)](https://matplotlib.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-red.svg)](https://scikit-learn.org/)

## 🔍 Project Overview
This project analyzes the Canadian Health Survey Dataset (2019-2020) to understand the factors influencing stress levels across different demographics. Using statistical analysis and data visualization techniques, we explore correlations between stress and various health, lifestyle, and socioeconomic factors.

## 📚 Dataset Description
The dataset contains anonymized responses from the Canadian Health Survey, providing insights into:

| Category | Information |
|----------|-------------|
| Demographics | Age, gender, marital status, household composition |
| Health Conditions | Chronic illnesses (diabetes, high blood pressure, sleep apnea, etc.) |
| Lifestyle Factors | Smoking, alcohol consumption, physical activity, food security |
| Mental Well-being | Stress levels, anxiety, mood disorders, life satisfaction |
| Healthcare Access | Insurance coverage, access to healthcare services |
| Employment | Work hours, job-related stress, income sources |

📂 **Data Source**: [Kaggle - Healthcare Survey Dataset](https://www.kaggle.com/datasets/aradhanahirapara/healthcare-survey/data)

## 📈 Key Findings

### 🧩 Stress and Gender
Our analysis reveals that stress is not gender-specific. Contrary to common assumptions, stress levels do not show significant bias toward any gender, except within the context of marriage, where some differences were observed.

### 💼 Work and Stress
A notable finding is the relationship between employment and stress levels. The data suggests that having insufficient work is correlated with higher stress levels. This could indicate that:
- ✅ Work may provide a distraction from stressors
- ✅ Employment offers financial security that reduces stress
- ✅ Purposeful activity and social connection at work may serve as stress buffers

### 🔄 Age, Life Satisfaction, and Mental Health
We found positive correlations between stress levels and:
- 👵 **Age**: Older individuals tend to report higher stress levels
- 😊 **Life satisfaction**: Interestingly, people reporting higher life satisfaction also report higher stress levels
- 🧠 **Mental health state**: Better reported mental health correlates with higher stress levels

These counterintuitive findings suggest that as people accumulate more responsibilities and achievements in life (higher life satisfaction), they may also experience increased pressure to maintain their status, resulting in higher stress.

## 🛠️ Technologies Used
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib/Seaborn**: Data visualization
- **Statsmodels**: Statistical modeling and tests
- **Scikit-learn**: Machine learning for predictive modeling

## 🚀 Getting Started

### Prerequisites
- Python 3.11 or higher
- Jupyter Notebook or JupyterLab

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/lastspot/canada-source-of-stress-2019-2020.git
   cd canada-source-of-stress-2019-2020
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows, use: .venv\Scripts\activate
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the dataset:
   - Visit [Kaggle - Healthcare Survey Dataset](https://www.kaggle.com/datasets/aradhanahirapara/healthcare-survey/data)
   - Download the `health_dataset.csv` file
   - Create a directory named `dataset` in the project root
   - Place the downloaded CSV file in the `dataset` directory

### Running the Analysis
1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open the `stress-analysis.ipynb` notebook

3. Run all cells to reproduce the analysis and visualizations

### Key Files
- `stress-analysis.ipynb`: Main Jupyter notebook containing all analysis code
- `dataset/health_dataset.csv`: Input dataset (needs to be downloaded separately)
- `README.md`: Project documentation

## 🔮 Future Work
- 🔍 Further investigation into the relationship between work hours and stress
- 🧪 Analysis of stress management techniques and their effectiveness across demographics
- 📊 More detailed examination of the relationship between life satisfaction and stress