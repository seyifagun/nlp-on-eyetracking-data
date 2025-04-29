# NLP on Eye-Tracking Data - A Machine Learning Approach for Detecting Behavioral Patterns

This project explores the integration of Natural Language Processing (NLP) techniques with eye-tracking data and to use eye-tracking data and machine learning to classify cognitive states. 
The goal is to enhance learning experiences for neurodiverse students by analyzing reading patterns, attention, and cognitive load through gaze behavior.

## Objectives

- Combine NLP models with eye-tracking data to detect reading difficulty, fatigue, or distraction.
- Determine the accuracy of the model
## Dataset
- Data was from the Tsukuba Eye-Tracking Corpus (TECO)
- Features include:
  Fixation durations | Pupil dilation | Fixation | Confidence rating on reading skills, speed.
Note: For privacy, the actual dataset is not included here.

## Key Technologies

- Python & Jupyter Notebook
- Natural Language Processing (spaCy, Transformers)
- Eye-tracking datasets (CSV/JSON formats)
- Pandas, NumPy, Seaborn, Matplotlib
- Machine Learning (scikit-learn)

## Methods
Preprocessing: Removal of redundant columns | Missing value treatment

Modeling: Trained a Random Forest Classifier | Split data: 80% training / 20% testing

Evaluation: Accuracy: ~88.5%

## Outcomes
- Achieved strong classification performance (~88% accuracy) in detecting states or groups from eye movement data.
- Identified key biometric indicators (e.g., fixation duration) that may correlate with cognitive load.

## Future Work
This project forms Module 1 of a broader system to integrate:
- Speech-to-text and NLP analysis
- Multimodal AI fusion (text + eye signals)
- Explainability tools for ethical deployment in legal settings
- Note: This section is under constant reveal.
  
## How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/seyifagun/nlp-on-eyetracking-data.git
   cd nlp-on-eyetracking-data
   
2.  run jupyter notebook eye_data_optimised.ipynb

Notes
1.  For emphasis sake, datasets are not publicly included due to privacy/ethical considerations.
2.  Future work will include model serving with FastAPI and integration with correlating platforms.
