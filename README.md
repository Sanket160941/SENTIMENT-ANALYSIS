# SENTIMENT-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SANKET MITHBAVKAR

*INTERN ID*: 556BDB3B1676F398

*DOMAIN*: DATA ANALYTICS

*DURATION*: 12 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION ABOUT THIS TASK*:
Sentiment analysis was performed on textual data using Natural Language Processing (NLP) techniques to understand and classify emotions expressed in written content. Sentiment analysis is an important application of NLP that helps determine whether a piece of text conveys a positive or negative opinion. This task focused on analyzing real-world textual data such as movie reviews and building machine learning models that can automatically predict sentiment based on the text content. For this task, a publicly available IMDB movie reviews dataset was used. The dataset consists of two main columns: the textual review and its corresponding sentiment label (positive or negative). Even though the dataset contains only two columns, it is well-suited for sentiment analysis because the core objective of NLP tasks is to extract meaning from text rather than relying on many structured features. This allowed the dataset to remain representative and practical for analysis.

The entire implementation was carried out using Visual Studio Code (VS Code) as the primary development platform along with Jupyter Notebook support. VS Code provided a flexible and efficient environment for writing Python code, organizing notebook cells, and executing NLP workflows step by step. This setup closely resembles real-world industry practices, making the task more practical. The first stage of the task involved data preprocessing, which is one of the most critical steps in Natural Language Processing. Raw textual data often contains noise such as punctuation, special characters, stopwords, and inconsistent capitalization. To address this, several NLP preprocessing techniques were applied. These included converting text to lowercase, removing punctuation and unnecessary symbols using regular expressions, eliminating stopwords using the NLTK library, and applying lemmatization to convert words into their base forms. These steps helped standardize the text and reduce complexity, allowing the models to focus on meaningful words rather than irrelevant noise. After preprocessing, the cleaned text data was converted into numerical form using the TF-IDF (Term Frequency–Inverse Document Frequency) technique. Since machine learning models cannot work directly with text, TF-IDF was used to transform words into numerical features based on their importance across the dataset. This feature extraction step enabled the models to understand which words contribute more strongly to determining sentiment.

In the model implementation phase, multiple machine learning algorithms were trained and evaluated. A Logistic Regression model was used as the primary classifier due to its effectiveness in binary classification problems like sentiment analysis. In addition, a Multinomial Naive Bayes model was implemented to compare performance and demonstrate alternative approaches for text classification. The dataset was split into training and testing sets to ensure fair evaluation on unseen data. Model performance was measured using metrics such as accuracy, precision, recall, F1-score, and confusion matrices. Beyond basic model training, additional insights were derived by testing the trained models on custom, real-world text inputs. This demonstrated how the sentiment analysis system can be used in practical scenarios such as predicting the sentiment of new reviews, comments, or feedback. Extra exploratory analysis, such as examining review length distribution and sentiment patterns, further enhanced the depth of the task.

This task has strong real-world applicability in areas such as customer feedback analysis, social media monitoring, brand reputation management, and recommendation systems. Companies use sentiment analysis to understand user opinions, improve products, and make data-driven decisions. By completing this task, a complete end-to-end NLP pipeline was demonstrated, including preprocessing, feature extraction, model implementation, evaluation, and insight generation, making it a comprehensive and valuable project.

*OUTPUTS*:
