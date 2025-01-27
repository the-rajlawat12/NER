# Medical Named Entity Recognition (NER) using spaCy


This project implements a custom Named Entity Recognition (NER) model using spaCy to identify and extract medical entities from unstructured text. It leverages annotated data and demonstrates how to preprocess, train, and evaluate an NER model tailored for the medical domain.

Features:

Data Preparation:

Extracted and processed annotated medical data in JSON format.
Converted annotations into spaCy-compatible training data format with entities tagged as start, end, and label.
Model Training:

Used spaCy's pipeline to preprocess the data and build a blank English model.
Filtered and validated spans for accurate entity alignment.
Trained a custom NER model using spaCy's train command with optimized configurations.
Visualization:

Visualized extracted entities using spaCy's displaCy to display labeled entities in a user-friendly manner.
Medical Entities Extracted:

Examples include DIAGNOSIS, TREATMENT, MEDICATION, and more.
Dataset:
The model was trained on a custom dataset, Corona2.json, which includes annotated examples of medical records.

Prerequisites:

Python 3.8+
spaCy 3.x
Additional Python libraries: numpy, pandas, tqdm, nltk 

