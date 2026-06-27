 The Ghost in the Machine
PRECOG Lab NLP Recruitment Task 2026

 What this project does
Builds a classifier to tell apart human-written text from AI-generated text across three classes:
* Human (Dickens + Austen novels)
* GenericAI (LLM paragraphs on same topics)
* StyleAI (LLM paragraphs mimicking author style)

 Tasks Completed
* Task 0: Built dataset (1500 samples, 3 classes)
* Task 1: Extracted 13 linguistic features (TTR, punctuation, readability etc.)
* Task 2: Trained 3 classifiers - XGBoost (98.3%), Neural Net (99.7%), DistilBERT+LoRA (100%)
* Task 3: SHAP explainability + error analysis
* Task 4: Genetic algorithm reached 84.3% human confidence score

 How to Run
1. Open Precog_NLP_Task.ipynb in Google Colab
2. Install libraries: pip install groq spacy textblob xgboost transformers peft torch shap
3. Get free Groq API key from console.groq.com and add it where indicated
4. Run cells in order top to bottom

 Dependencies
groq, spacy, textblob, nltk, xgboost, transformers, peft, torch, shap, pandas, numpy, matplotlib, seaborn

 Author
Lasya Priya | MCA Final Year | SRM IST 
