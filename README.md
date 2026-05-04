# Contents

## Project Title
Uncovering Patterns in UFO Sightings: Topic Modeling and Network Analysis of Encounter Descriptions

## Dataset
- **Name**: UFO Sightings Reports  
- **Description**: Over 80,000 real eyewitness reports with detailed description text and ufo_shape labels.  
- **File**: `data/ufo_sightings.csv`  
- **Source**: Tidytuesday NUFORC dataset

## Methods

### Text Preprocessing
- Lowercasing, removal of punctuation and numbers  
- Stopword removal  
- Lemmatization

### Topic Modeling
- Used Latent Dirichlet Allocation (LDA) to discover 8 main themes

### Network Analysis
- Built a word co-occurrence network to show connections between words

### Rationale for Choosing These Methods
Topic Modeling helps discover the main hidden themes.  
Network Analysis shows how words are connected to each other.  
These two methods work well together and give both broad insights and detailed relationships.

### Machine Learning
- Predicted `ufo_shape` from description text  
- Used TF-IDF + Logistic Regression  
- Evaluated with classification report and confusion matrix

## Visualizations
- Top words bar chart (Altair)  
- Word Network graph  
- Confusion Matrix

## Results and Insights
- Topic Modeling revealed common themes such as bright lights and triangular objects.  
- Network Analysis showed strong connections between words like “light”, “sky”, and “bright”.  
- The machine learning model achieved 55% accuracy predicting UFO shapes from text.

## How to Reproduce
1. Clone the repository  
2. Install dependencies: `pip install -r requirements.txt`  
3. Run the notebooks in order

## Files Included
- `data/ufo_sightings.csv`  
- `notebooks/` – Annotated analysis notebooks  
- `results/` – Generated figures and outputs  
- `poster/final_poster.pdf`

## Links
- **GitHub Repository**: https://github.com/diemacedo12/final-project/
- **Dataset**: Included in the repository
