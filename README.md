# Contents

## Project Title
Uncovering Patterns in UFO Sightings: Topic Modeling and Network Analysis of Encounter Descriptions

## Dataset
- **Name**: UFO Sightings Reports
- **Description**: Thousands of real eyewitness reports with a rich `description` column and `ufo_shape` label.
- **File**: `data/ufo_sightings.csv`
- **Source**: Public NUFORC dataset

## Methods

### 1. Text Preprocessing
- Lowercasing
- Removal of punctuation and numbers
- Stopword removal
- Lemmatization

### 2. Topic Modeling
- Used Latent Dirichlet Allocation (LDA) to discover recurring patterns of co-occurring words
- Identified 8 main topics such as bright lights, triangular objects, and emotional descriptions

### 3. Network Analysis
- Built a word co-occurrence network to show how words are connected in the reports
- Visualized important word relationships

### 4. Machine Learning
- Predicted `ufo_shape` from description text using TF-IDF + Logistic Regression
- Evaluated with classification report and confusion matrix

## Visualizations
All visualizations were created using Altair as taught in class:
- Top words bar chart
- Topic word distributions
- Word co-occurrence network
- Sentiment and topic comparison charts

## Results
- Clear themes discovered through topic modeling
- Strong word connections shown in the network
- Machine learning model successfully classified UFO shapes from text

## How to Run the Project
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebooks in Google Colab or Jupyter
4. Run the notebooks in order (01 → 04)

## Files Included
- `data/ufo_sightings.csv` – Raw dataset
- Notebooks with step-by-step comments
- `results/` – Output files and prediction CSV
- `visualizations/` – Altair charts
- `poster/final_poster.pdf` – Final poster
