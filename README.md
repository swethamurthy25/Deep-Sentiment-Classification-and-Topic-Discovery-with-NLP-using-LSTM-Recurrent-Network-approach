## $\textcolor{red}{Deep\ Sentiment\ Classification\ and\ Topic\ Discovery\ with\ NLP\ using\ LSTM\ NeuralNetwork}$

* Course: Natural Language Processing (NLP)  
* Reference Paper: https://ieeexplore.ieee.org/document/9112671

This paper mainly focuses on the importance of using public opinions and suitable NLP-based computational techniques to understand the issues around Covid-19 and the related decision-making process.
![image](https://github.com/swethamurthy25/Deep-Sentiment-Classification-and-Topic-Discovery-with-NLP-using-LSTM-Recurrent-Network-approach/assets/112581595/6e18b2c8-6108-4678-b1bf-7d4efc86713d)


## $\textcolor{red}{Limitations\ of\ the\ Paper}$

* This research was limited to English-language text, which was considered a selection criterion. Therefore, the results do not reflect comments made in other languages.
* This study and analysis were limited to comments retrieved from January 20, 2020, and March 19, 2020.

## $\textcolor{red}{Why\ the\ implementation\ is\ done\ on\ NLP}$

* NLP can generally handle large amounts of unstructured data, such as user comments on social media platforms, and analyze them in a relatively short time.
* NLP can effectively perform sentiment analysis to identify and categorize opinions and emotions expressed in user comments related to COVID-19.
* NLP can process text in multiple languages making it possible to analyze user comments related to COVID-19 from different parts of the world. This can further provide insights into how the pandemic is affecting people in different regions and help in developing appropriate responses. 
* NLP can be easily integrated with other technologies such as machine learning and data visualization to provide a comprehensive understanding of user comments related to COVID-19.

## $\textcolor{red}{Overall\ Approach}$

* Phases of Project - Data Collection, Data preprocessing, Topic discovery, and model discovery, sentiment classification, model evaluation.

* The first step is to collect many COVID-19-related comments from social media platforms such as Reddit, Twitter, and Facebook.
* Then, the collected data is preprocessed to remove stop words and other irrelevant information.
*  The preprocessed data is then tokenized, stemmed, and lemmatized.
*  The preprocessed data is used to train a deep learning model, such as an LSTM Recurrent Neural Network, to classify the sentiment of each comment as positive, negative, 
   or neutral.
* The performance of the sentiment classification model is evaluated using different metrics such as accuracy and precision.
* In topic discovery, the preprocessed data is further analyzed using topic modeling techniques such as Latent Dirichlet Allocation (LDA) to identify the topics discussed 
  in the comments.
* Based on the results of the model evaluation and topic discovery, the model is refined by tweaking hyperparameters, changing the architecture of the deep learning model, 
  or using a different feature extraction technique.
* The above steps are repeated iteratively until the desired performance of the sentiment classification and topic discovery model is achieved.


## $\textcolor{red}{Step\ 1-\ Data\ Acquisition\ and\ identifying\ data\ sources}$

Data acquisition is the process of collecting and gathering raw data from various sources and transforming it into a format that can be used for analysis or other applications.

* The methodology for collecting data sources for the deliverable will involve several steps to ensure the data is appropriate. First, we have already identified sources of 
  COVID-19 patient comments, posted on Reddit from Kaggle. There was a total of 5,63,079 comments extracted, assessed, and used for this experiment.
* The dataset was collected between January 20, 2020, and March 19, 2020.
* We have then evaluated the data to ensure they contain relevant comments from COVID-19 patients that are suitable for sentiment analysis and topic modeling.
* Some of the NLP techniques that have been incorporated are Topic Modelling – LDA & Gibbs Sampling, Sentiment Analysis / determining the sentiment polarity, Machine 
  learning algorithms for sentiment analysis, and Long-Short Term Model (LSTM).
* We have also considered the ethical implications of collecting and using the data and ensure that all necessary permissions are obtained before data collection begins.
* We have taken measures to protect the privacy and anonymity of the individuals who have made the comments.
* Overall, the methodology for collecting data sources will be rigorous and thorough to ensure that the data used for the deliverables are accurate.

#### The final format for modeling and analysis:

<img width="436" alt="image" src="https://github.com/swethamurthy25/Deep-Sentiment-Classification-and-Topic-Discovery-with-NLP-using-LSTM-Recurrent-Network-approach/assets/112581595/6bc27984-3b03-463c-80b7-3ed6942d7340">

## $\textcolor{red}{Step\ 2-\ Data\ Processing\ and\ Transformation}$

![image](https://github.com/swethamurthy25/Deep-Sentiment-Classification-and-Topic-Discovery-with-NLP-using-LSTM-Recurrent-Network-approach/assets/112581595/c704fac7-23e2-488e-85f3-f2ac7efb602d)

![image](https://github.com/swethamurthy25/Deep-Sentiment-Classification-and-Topic-Discovery-with-NLP-using-LSTM-Recurrent-Network-approach/assets/112581595/9d3697bb-ccd3-44e1-8f99-f0879d067502)


#### Identified Sentiment Polarity
![image](https://github.com/swethamurthy25/Deep-Sentiment-Classification-and-Topic-Discovery-with-NLP-using-LSTM-Recurrent-Network-approach/assets/112581595/ed9699f5-89ea-4865-88a1-ae187682e85f)

#### Formation of Word Cloud
![image](https://github.com/swethamurthy25/Deep-Sentiment-Classification-and-Topic-Discovery-with-NLP-using-LSTM-Recurrent-Network-approach/assets/112581595/94f3d724-bf8c-4ad3-bb8c-50391e4fbf6f)









