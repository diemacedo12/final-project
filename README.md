# Contents

## Project Title
Uncovering Patterns in UFO Sightings: Topic Modeling and Network Analysis of Encounter Descriptions

## Dataset
- **Name**: UFO Sightings Reports  
- **Description**: Thousands of real stories written by people who saw UFOs. Each report has a long description and a shape label.  
- **File**: `data/ufo_sightings.csv`  
- **Source**: Public NUFORC dataset

## Methods

### 1. Text Preprocessing
- Made all letters small  
- Removed punctuation and numbers  
- Removed common words (stopwords)  
- Changed words to simple form (lemmatization)

### 2. Topic Modeling
- Used LDA to find groups of words that often appear together  
- Found 8 main topics (such as bright lights and triangular objects)

### 3. Network Analysis
- Built a word network to show which words appear together often  
- Visualized how words are connected

### Why I Chose These Two Methods
I picked Topic Modeling to discover the main themes in the reports.  
I picked Network Analysis to see how the words are connected to each other.  
These two methods work well together and help us understand the stories better.

### 4. Machine Learning
- Tried to predict the UFO shape from the description text  
- Used TF-IDF and Logistic Regression  
- Checked the results with a classification report and confusion matrix

## Visualizations
I created all charts using Altair:
- Top words bar chart
- Word network graph
- Topic word lists
- Confusion matrix

## Results and Main Insights
- Topic Modeling showed common themes like bright lights, triangles, and fast-moving objects.  
- Network Analysis showed strong connections between words like “light”, “sky”, and “object”.  
- The machine learning model was able to predict some UFO shapes from the text.  
- Text mining helps us find useful patterns in many UFO stories.

## How to Run the Project
1. Clone (download) the repository  
2. Install packages: `pip install -r requirements.txt`  
3. Open the notebooks in Google Colab  
4. Run the notebooks in order

## Files Included
- `data/ufo_sightings.csv` – The raw data  
- `notebooks/` – All analysis notebooks with explanations  
- `results/` – Charts and output files  
- `poster/final_poster.pdf` – Final poster
