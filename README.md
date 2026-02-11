#  Explainable Job Recommendation System

An intelligent content-based job recommendation system that parses resumes, matches them to job descriptions using NLP, and provides detailed explanations including missing skills and match reasons.

## 🎯 Features

- **Text Preprocessing**: Clean and normalize job descriptions and resumes
- **Skill Extraction**: Automatically identify 100+ technical skills across multiple categories
- **Intelligent Matching**: TF-IDF + skill overlap based matching algorithm
- **Explainability**: Detailed match analysis with matched/missing skills and recommendations

## 📊 Dataset

- **2,277 job descriptions** from various tech roles
- Fields: Job Title, Job Description
- Source: `data/raw/job_title_des.csv`
- Data Source: https://www.kaggle.com/datasets/kshitizregmi/jobs-and-job-description

## 🚀 Quick Start

### Installation

```bash
pip install -r requirements.txt
```

### Explore the Data

```bash
jupyter notebook
```

Open `notebooks/01_data_exploration.ipynb` to get started.

### Project Structure

```
sars-job-recommender/
├── data/              # Raw and processed data
├── notebooks/         # Jupyter notebooks for experimentation
├── src/               # Production source code
├── tests/             # Unit tests
└── models/            # Saved ML models
```

## 🔬 Methodology

1. **Preprocessing**: Clean text, remove stopwords, normalize formatting
2. **Skill Extraction**: Pattern-based identification of technical skills
3. **Similarity**: TF-IDF vectorization + cosine similarity
4. **Matching**: Combined scoring (text similarity + skill overlap)
5. **Explainability**: Highlight matched/missing skills with recommendations

## 🛠️ Tech Stack

- Python 3.14
- pandas, numpy
- scikit-learn
- Jupyter Notebooks

## 📈 Results

- Average skill overlap: TBD
- Processing time: TBD
- Match accuracy: TBD

## 📝 Notebooks

1. `01_data_exploration.ipynb` - Understand the dataset
2. `02_text_preprocessing.ipynb` - Build text cleaning pipeline
3. `03_skill_extraction.ipynb` - Extract technical skills
4. `04_job_matching.ipynb` - Build matching algorithm

## 🤝 Contributing

This is a learning project. Feel free to explore and improve!


**Built for learning NLP and recommendation systems** 🎓