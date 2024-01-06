# fake-news-detection-using-lstm

In today's digital age, the rapid proliferation of information through online platforms has revolutionized the way we consume news and engage with current events. However, this unprecedented accessibility to information has also given rise to a concerning phenomenon—fake news. Fake news, characterized by false or misleading information presented as factual news, has become a pervasive issue with far-reaching consequences. Its impact spans from influencing public opinion and elections to inciting social discord and undermining trust in credible sources.


The approach for this project involves a fusion of TF-IDF methodology with LSTM (Long Short-Term Memory) and Bidirectional LSTM (BiLSTM) models for the detection of fake news. Initially, the FakeNewsNet and ISOT datasets are merged to create a comprehensive corpus of labeled news content. Following this, the text data undergoes preprocessing, including cleaning, tokenization, and normalization, ensuring uniformity across articles. The key pivot lies in the TF-IDF representation, where the text data is transformed into TF-IDF vectors to highlight the importance of specific terms within each article, emphasizing crucial words in the context of individual documents. Finally the model is trained and evaluated.
