# Final Year Project

### Date Submitted: 5th September 2022
### Degree Title: BSc in Computer Science
### Course: CM3070

*Disclaimer 1
baseline.ipynb is unable to render, hence an additional file called "baseline.pdf" is available for viewing

*Disclaimer 2
Github does not permit the uploading of large or multiple files, hence models generating using HyperBand (hyper-tuning) for deep learning files are not accessible and may affect results (and time taken) when attempting to run the codes.

### baseline.ipynb
This is the file that should be first accessed/read for dataset analysis and exploration. 

Codes to provided analysis for the following points
- Most effective text representation among those identified from Literature Review
- Do emojis have an impact on classification? (Better or Worse)
- Generation of second baseline based on traditional machine learning algorithms
After analysis of points, deep learning models are performed in attempt to further improve upon the second baseline. Each file (bow, tfidf, rnn_lstm and cnn_lstm) contains their own process and models for the ease of easier understanding and prevention of restricted access to the code (due to overly large file) similar to baseline.ipynb.

### bow.ipynb
Generates deep learning models of Multi-Layer Perceptron (MLP) using Bag-of-Words (BoW) as input. 

Compared to the other deep learning models, MP using bag of words is most effective and hence iterated k-fold is performed to further analyze the impact of evauation protocols on the model built. Other files containing deep learning model do not contain said codes.

### tfidf.ipynb
Generates deep learning models of Multi-Layer Perceptron (MLP) using TF-IDF as input.

### word_embed_rnn_lstm.ipynb
Generates deep learning models of RNN-LSTM using Word Embeddings as input.

### word_embed_cnn_lstm.ipynb
Generates deep learning models of CNN-LSTM using Word Embeddings as input.
