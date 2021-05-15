# Text-summary-using-BERT


BERT (Bidirectional Encoder Representations from Transformers) introduces rather advanced approach to perform NLP tasks. Single-document text summarization is the task of automatically generating a shorter version of a document while retaining its most important information. Recently, I read a journal article intitle BERTSUM from Liu at Edinburgh. This paper extends the BERT model to achieve state of art scores on text summarization. In this lesson, we will learn how to extract a summary from several documents


Lesson Goals
In this lesson, we will learn how to extract a summary from several documents using Bidirectional Encoder Representations from Transformers (BERT).Summarization is the task of producing a shorter version of one or several documents that preserves most of the input's meaning.Extractive strategies select the top N sentences that best represent the key points of the article. Abstractive summaries seek to reproduce the key points of the article in new words. Mixed strategies either produce an abstractive summary after identifying an extractive intermediate state or they can choose which approach to use (eg: pointer models) based on the particulars of the text.
Prerequests
pip install bert-extractive-summarizer
pip install newspaper3k
Make sure to create a new directory and new environment
