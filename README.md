# Motivation
Fake News is a major controversial issue right now. World is facing troubles to resolve this issue. So, this is right time for data scientist to come up with solution. I tried to address this. Obviously, some great solution is coming on the way.

# Objectives
- Detect fake news or not
- Avoid biasness

# Steps
1. Explore Fake and true dataset
2. Clean Data(Remove word and punctuation which does not make any sense)
3. Visualize to see most frequent words(Remove those to avoid biasness)
4. Preprocess Data( word2vec, embedding, text to sequences)
5. Building Deep Learning Model
6. Evaluate results
<p align="left">
    <img src='https://raw.githubusercontent.com/Shaon2221/Fake-News-Detection-using-LSTM/master/Fake_words_cloud.jpg' height=300 width=400>
</p>

# Tools Used
### Python, Pandas, Matplotlib, Seaborn, NLTK, word2vec, embedding layer, LSTM
# Challenge and Drawbacks
99% Accuracy looks like unusual. But model is developed carefully to avoid overfitting. As well as, removed some specific word to avoid biasness(Reuters..). I think, it's the problem of dataset which may have some indicator which leads to high accuracy. So, it's not guranteed that this model may not work up to the marks for another new dataset.

**Important Notes**
Datasete is collected from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset/download)  <br>
Model is developed based on kernel of [Atish Adhikari](https://www.kaggle.com/atishadhikari/)
