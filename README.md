# Contents

## Project Title
Uncovering Patterns in UFO Sightings: Topic Modeling and Network Analysis of Encounter Descriptions

## Dataset
- **Name**: UFO Sightings Reports  
- **Description**: Thousands of real stories written by people who saw strange things in the sky. Each story has a description and a shape label.  
- **File**: `data/ufo_sightings.csv`  
- **Source**: Public NUFORC dataset

## Methods

### 1. Text Preprocessing
- Made all letters small  
- Removed punctuation and numbers  
- Removed common words  
- Changed words to simple form

### 2. Topic Modeling
- Used LDA to find groups of words that often appear together  
- Found 8 main topics (bright lights, triangles, moving objects, etc.)

### 3. Network Analysis
- Built a word network to show which words appear together  
- Visualized important connections

### Why These Two Methods?
I chose Topic Modeling to discover the main themes.  
I chose Network Analysis to see how the words are connected.  
These two methods work well together and help us understand the reports better than using Sentiment Analysis alone.

### 4. Machine Learning
- Tried to predict the UFO shape from the description text  
- Used TF-IDF + Random Forest  
- Checked results with classification report and confusion matrix

## Visualizations
All charts made with Altair:
- Top words bar chart
- Word network graph
- Confusion matrix

## Results and Main Insights
- Topic Modeling showed common themes like bright lights and triangular shapes.  
- Network Analysis showed strong connections between words like "light", "sky", and "bright".  
- The model could predict some shapes from the text.  
- Text mining helps turn many UFO stories into clear patterns.

## How to Run the Project
1. Clone the repository  
2. Install packages with `pip install -r requirements.txt`  
3. Open notebooks in Google Colab  
4. Run the notebooks in order

## Files Included
- `data/ufo_sightings.csv` – Raw data  
- `notebooks/` – Analysis notebooks with explanations  
- `results/` – Charts and prediction files  
- `poster/final_poster.pdf` – Final poster
