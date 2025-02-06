# The Goal:
The goal of this project was to 1. predict the remaining useful life (RUL), 2. Detect engine anomalies, 3. Classify enginges by risk

Models used include RF, LSTM, SVM, kNN

# NASAs turbofan dataset


![image](https://github.com/user-attachments/assets/e7527c52-0748-4429-b897-922fd3fdb9ab)




The turbofan dataset consists of 4 separate challenges of increasing difficulty. The engines operate normally in the beginning but develop a fault over time. For each challenge, the engines in the train set are run to failure. The timeseries in the test set end 'sometime' before failure. The goal is to predict the Remaining Useful Life (RUL) of each turbofan engine in the test set. See the table below for a short overview of the challenges.

Dataset	Operating conditions	Fault modes	Train size (nr. of engines)	Test size (nr. of engines)
FD001	1	1	100	100
FD002	6	1	260	259
FD003	1	2	100	100
FD004	6	2	248	249
The notebooks are used to explore the dataset and try various modeling techniques (both Machine Learning and Neural Networks). For the full explanation of the techniques and choices made during model development I recommend reading the blog posts [1].

## Source : https://www.kaggle.com/datasets/behrad3d/nasa-cmaps/data

# Visualizations

![image](https://github.com/user-attachments/assets/25f32bfc-8f4e-4147-956d-a54db638e438)


![image](https://github.com/user-attachments/assets/f350d737-bbcf-4be0-a9e4-0704345aa30f)
