# Spamclssifier_using_NLP

## DESCRIPTION

Dataset contains one set of SMS messages in English of 4837 messages, tagged according being ham (legitimate) or spam.
It has a total of 4,199 SMS legitimate messages (86.81%) and a total of 638 (13.18%) spam messages.

## Requirements
The code uses NLTK and scikit-learn libraries.

## Tokenization

Tokenization is essentially splitting a phrase, sentence, paragraph, or an entire text document into smaller units, such as individual words or terms. Each of these smaller units are called tokens.

Let’s take an example. Consider the string:<br>
**This is a cat.**<br>
After we perform tokenization on this string? We get [‘This’, ‘is’, ‘a’, cat’].

## Stemming

Stemming is the process of removing a part of a word, or reducing a word to its stem or root word.<br>
For example: “Flying” is a word and its suffix is “ing”, if we remove “ing” from “Flying” then we will get base word or root word which is “Fly”.

## Lemmatization

Lemmatization is the process of removing a part of a word, or reducing a word to its lemme.<br>
It is similar to stemming but it brings context to the words.

Examples of lemmatization:

-> rocks : rock<br>
-> corpora : corpus<br>
-> better : good<br>

## How is Lemmatization different from Stemming?

Lemmatization algorithm would know that the word better is derived from the word good, and hence, the lemme is good. But a stemming algorithm wouldn’t be able to do the same. There could be over-stemming or under-stemming, and the word better could be reduced to either bet, or bett, or just retained as better

## Count vectorizer

CountVectorizer is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency(count) of each word that occurs in the entire text.

## TF_IDF or ( Term Frequency(TF) — Inverse Dense Frequency(IDF))

TF-IDF is a statistical measure that evaluates how relevant a word is to a document in a collection of documents.<br>
This is done by multiplying two metrics: how many times a word appears in a document, and the inverse document frequency of the word across a set of documents.

*IDF =Log[(# Number of documents) / (Number of documents containing the word)]* 

*TF = (Number of repetitions of word in a document) / (# of words in a document)*


