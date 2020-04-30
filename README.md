# Textual_Analytics_Insights_-From_Markov-concept_to_Machine_translation-
#Task Performed :

#1. Sentiment Analysis of review: I have used unsupervised ML technique(using dictionary of negative and positive words)
         #since our dataset has not labeled column
    
#2. User similarity based on the their review similarity score: used two different ways 
                          # 1. vectorizing using Doc2vec model from gensim module and then finding cosine similarity
                          # 2. vectorizing using counntvectorizer and then cosine similarity
        
#3. clustering the text review using KMeans  into the 5 different clusters based on their semantic simialrity.
         # Then finding the top words from each clusters
    
# 4. Finding the top frequency of ngrams (combination of words) tokens.

#5. Build a machine translation model using seq2seq (encoder decoder) technique.
    # since our dataset has both the english and their similar meaning text in indonesian language
    # so i used the this dataset to build a neural translation model.
        
#6. Textual analytics concepts like tokenization ,lemmitization, cleaning, vectorization, probability distribution ,NLP modules         

#7. Built a   next word prediction model using markov chain concept and n-grams. 

#NOTE:
## Please note that I have used minimum no. of data to reduce the training time because of my poor system compatibilty.
  # so, training data and epochs can be tuned high for higher accuracy anytime.
