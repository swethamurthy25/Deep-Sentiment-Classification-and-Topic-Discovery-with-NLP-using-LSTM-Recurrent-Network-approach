# Deep-Sentiment-Classification-and-Topic-Discovery-with-NLP-using-LSTM-Recurrent-Network-approach

Course: Natural Language Processing (NLP)  

Reference Paper: https://ieeexplore.ieee.org/document/9112671
___________________________________________________________________________________________

This paper mainly focuses on the importance of using public opinions and suitable NLP-based computational techniques to understand the issues around Covid-19 and the related decision-making process.
![image](https://github.com/swethamurthy25/Deep-Sentiment-Classification-and-Topic-Discovery-with-NLP-using-LSTM-Recurrent-Network-approach/assets/112581595/6e18b2c8-6108-4678-b1bf-7d4efc86713d)

<span style="color:#007bff;">Limitations of the Paper:</span>
<span style="color: red"> Some green text </span>

-- This research was limited to English-language text, which was considered a selection criterion. Therefore, the results do not reflect comments made in other languages.

-- This study and analysis were limited to comments retrieved from January 20, 2020, and March 19, 2020.

__________________________________________________________________________________________________________________


## Why should we use NLP for this project

-- NLP can generally handle large amounts of unstructured data, such as user comments on social media platforms, and analyze them in a relatively short time.

-- NLP can effectively perform sentiment analysis to identify and categorize opinions and emotions expressed in user comments related to COVID-19.

-- NLP can process text in multiple languages making it possible to analyze user comments related to COVID-19 from different parts of the world. This can further provide insights into how the pandemic is affecting people in different regions and help in developing appropriate responses. 

--NLP can be easily integrated with other technologies such as machine learning and data visualization to provide a comprehensive understanding of user comments related to COVID-19.


## Data Acquisition

Data acquisition is the process of collecting and gathering raw data from various sources and transforming it into a format that can be used for analysis or other applications.

### Identify the data source

  The methodology for collecting data sources for the deliverable will involve several steps to ensure the data is appropriate. First, we have already identified sources of COVID-19 patient comments, posted on Reddit from Kaggle. There was a total of 5,63,079 comments extracted, assessed, and used for this experiment.
     
  The dataset was collected between January 20, 2020, and March 19, 2020. We have then evaluated the data to ensure they contain relevant comments from COVID-19 patients that are suitable for sentiment analysis and topic modeling. Some of the NLP techniques that have been incorporated are Topic Modelling – LDA & Gibbs Sampling, Sentiment Analysis / determining the sentiment polarity, Machine learning algorithms for sentiment analysis, and Long-Short Term Model (LSTM).
      
  We will also consider the ethical implications of collecting and using the data and ensure that all necessary permissions are obtained before data collection begins. We have taken measures to protect the privacy and anonymity of the individuals who have made the comments. Overall, the methodology for collecting data sources will be rigorous and thorough to ensure that the data used for the deliverables are accurate.

### Potential problems with the data sources and collection methodology

-- The selection of COVID-19-related Reddit comments might not be representative of the overall population. For instance, it might overrepresent a particular demographic or people with a particular perspective on COVID-19.

-- Reddit comments may not be transferable to other platforms or social networking websites.

-- Reddit comments that contain errors or inconsistencies like misspellings, abbreviations, or sarcasm may affect the analysis.

-- Privacy concerns arise when gathering and analyzing data from social networking sites, especially if the data is not sufficiently anonymized.

-- Researchers must make sure they follow the proper ethical principles and receive the relevant approvals because collecting data from social media sites without users' explicit agreement or understanding presents ethical questions.

-- The dataset has comments for only three months, which is a very short duration.

### Iterative nature of NLP in relation to project and deliverable

  Some of the processes that have been followed in the project in an iterative manner are data collection. Data preprocessing, sentiment classification, model evaluation, Topic discovery, and model discovery.

  The first step is to collect many COVID-19-related comments from social media platforms such as Reddit, Twitter, and Facebook. Then, the collected data is preprocessed to remove stop words and other irrelevant information. The preprocessed data is then tokenized, stemmed, and lemmatized. The preprocessed data is used to train a deep learning model, such as an LSTM Recurrent Neural Network, to classify the sentiment of each comment as positive, negative, or neutral. The performance of the sentiment classification model is evaluated using different metrics such as accuracy and precision. In topic discovery, the preprocessed data is further analyzed using
topic modeling techniques such as Latent Dirichlet Allocation (LDA) to identify the topics discussed in the comments.

  Based on the results of the model evaluation and topic discovery, the model is refined by tweaking hyperparameters, changing the architecture of the deep learning model, or using a different feature extraction technique. The above steps are repeated iteratively until the desired performance of the sentiment classification and topic discovery model is achieved


## Data Cleaning

### Steps were taken to determine whether the data should be considered sensitive:

-- Sensitive data is any information that, if revealed, could harm, or embarrass people, as it relates to COVID-19 patient comments. Examples of sensitive information include personally identifiable information (PII), names of persons, financial information about the cost of medical care in a certain hospital, and any other information that can be used to identify a person.

-- Evaluating the data's possible hazards, such as the danger of injury or embarrassment to certain people if the data were revealed. 

-- Data protection procedures are implemented to safeguard the data based on the risk assessment. For example, the data may be anonymized, access restrictions may be put in place, or sensitive data fields may be encrypted.

-- Legal or ethical requirements linked with the collection and management of sensitive data are necessary.

### Necessary steps to ensure the security of the data:

-- Encryption and access controls should be used to prevent unauthorized access.

-- Data security requirements should be observed while using a secured server or cloud-based storage.

-- To protect the identity of specific people, the data should be anonymized if it contains personal information.

-- To use the data for research purposes, the individual's personal informed consent must be used.

-- To secure personal information, data privacy laws and regulations are rigorously adhered to.

### Process and Methodology for Cleaning the Data:

#### The final format for modeling and analysis:

<img width="436" alt="image" src="https://github.com/swethamurthy25/Deep-Sentiment-Classification-and-Topic-Discovery-with-NLP-using-LSTM-Recurrent-Network-approach/assets/112581595/6bc27984-3b03-463c-80b7-3ed6942d7340">










