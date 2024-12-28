Thesis Project
Exploring the Effectiveness of Blending Ensemble Learning for Online Hate Speech Detection

Created an application to determine whether a text is classified as hate speech or not. ML models used in this study were the ff: Logistic Regression (as the metamodel), Decision Trees, Gaussian Naive Bayes, K-Nearest Neighbors, Support Vector Machine.
Data was trained using the languages of English, and Filipino from the ff datasets: ETHOS Dataset, Hate Speech and Offensive Language Dataset, and Hate Speech Filipino Dataset. Features used for machine learning were bigrams and tf-idf.

AAA-
model.ipynb is the actual approach used in the study with an imbalanced dataset skewing towards more non-hateful text.
model-balanced.ipynb includes an experimental balanced approach of training the model (50% Hate, 50% Non-Hateful Text)
model-unigram.ipynb includes an experimental approach of training the model using unigrams and TF-IDF as features instead of bigrams and TF-IDF

Data Preprocessing.ipynb is the actual approach used in the data preprocessing stage whereas DP-StopWords includes an experimental addition of stop words for data preprocessing.
FastText was also utilized to categorize text as either belonging to English or Filipino if there were instances of code-mix language use in a given text.

Project included the use of Python (and a variety of Python libraries e.g joblib, sklearn, numpy), Jupyter Notebook, Anaconda, FastText (lid.176.bin model).
