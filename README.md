# news-summarisation-translation
- Python-based project leveraging NLP techniques for news summarization and translation to foreign language; streamlined NLP pipeline utilizing tools like NLTK, Hugging Face Transformers Library, and the Helsinki-NLP/opus-mt Model for text processing, summarization, and translation.
- done in Google Colab
- English news summarisation (scraped from Google News) and translation into French

**Problem Statement**
 - Breaking the language barrier (translation): inability to access news from other countries because of the language barrier limits understanding of global events.
 - Information overload (summarisation): so much news on the internet is overwhelming; people want shorter, easier-to-read versions of news articles.

**NLP PIPELINE**
1. Retrieving the news from the website
2. Text Summarisation
3. NLP stages in Translation
4. Summarized translation in foreign language
5. Text Pre-Processing

**NLP TOOLS USED**

1. Pre-Processing tools:
- NLTK
- Stopwords Corpus
- Tokenization
- Stemming
- Lemmatization
- Text Normalisation
- Special Character and Punctuation Removal
- Word Limitation"

2. Hugging Face Transformers Library: Open Source library For NLP - continuous library growth from the community; could be used for text summarisation, translation, sentiment analysis, etc.; pre-trained models available - easy implementation with few lines of code

3. Pipeline Feature: used to simplify the NLP workflow; cross-lingual support - allows users to specify source and target languages; seamless integration with pre-trained models

4. Helsinki-NLP Model: Open Source library For NLP - part of the Opus-MT project by the Helsinki-NLP team; designed to perform machine translation
allows translation between different language pairs; For example, ""Helsinki-NLP/opus-mt-en-fr"" indicates translation from English to French; The Opus-MT project leverages parallel corpora, which are collections of texts in multiple languages, to build translation models that can maintain the context and meaning of the text.
integrates seamlessly with the Hugging Face Transformers Library
