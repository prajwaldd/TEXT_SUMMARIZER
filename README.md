# TEXT_SUMMARIZER
This is a Python script for a text summarization application using two NLP libraries: NLTK and Spacy. The script contains two functions, nltk_summarizer and spacy_summarizer, which both take in a text document as input and return a summarized version of the text.

The main function is responsible for the user interface of the application. It allows the user to input text and choose between the two summarization options: NLTK or Spacy. Once the user clicks the "Summarize Via Text" button, the selected function is called to generate a summary, which is then displayed to the user.

The NLTK summarizer function works by first tokenizing the input text into words and sentences, and then assigning a score to each sentence based on the frequency of its constituent words. The sentences with the highest scores are selected for inclusion in the summary.

The Spacy summarizer function follows a similar approach, but uses Spacy's built-in stop words list instead of NLTK's. It also uses a larger set of stop words and a larger pre-trained language model than the NLTK function.

Overall, this script provides a simple yet effective way to generate text summaries using two popular NLP libraries.
