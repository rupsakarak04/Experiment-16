#**EXPERIMENT 16 : *Implementation of Natural Language Processing (NLP) Techniques on Text Data****

##*AIM*: **To study and implement fundamental Natural Language Processing techniques in Python to process, clean, and analyze unstructured text data using libraries such as NLTK and Pandas.** 

*THEORY*:

Natural Language Processing (NLP) is a branch of artificial intelligence that focuses on the interaction between computers and human language. Since computers cannot understand raw text directly, NLP techniques are used to convert unstructured text into a structured format that a machine can process.

1. Text Preprocessing

Raw text data is often "noisy" (containing symbols, varied casing, and filler words). Preprocessing is the essential first step in any NLP pipeline to improve the accuracy of models.
- Lowercasing: Converting all text to lowercase ensures that words like "Apple" and "apple" are treated as the same token.
- Punctuation Removal: Removing symbols like commas and periods helps focus on the actual words.

2. Tokenization

Tokenization is the process of breaking a stream of text into smaller units called tokens. These tokens can be words, characters, or sub-words. Word tokenization is the most common form, where a sentence is split into individual words.

3. Stopword Removal

Stopwords are commonly used words in a language (e.g., "is", "the", "at", "which") that carry little unique information. Removing them reduces the size of the dataset and allows the analysis to focus on the meaningful keywords.

4. Stemming and Lemmatization

Both techniques are used to reduce a word to its root form:
- Stemming: A rule-based process that chops off the ends of words (e.g., "running" becomes "run"). It is fast but can sometimes result in non-dictionary words.
- Lemmatization: Uses a dictionary and morphological analysis to return the base or dictionary form of a word, known as a lemma (e.g., "better" becomes "good").


**Conclusion**
The experiment demonstrates that Text Preprocessing is a critical foundation for Natural Language Processing. By applying techniques such as tokenization, stopword removal, and normalization, we transform messy, unstructured text into a refined format. These steps are vital for any text-based analysis, from simple word counts to complex machine learning applications.
