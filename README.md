# Natural Language Processing
## Applications of Language Processing
* Spelling and grammatical checkers: *MS Word*, e-mail programs, etc.
* Text indexing and information retrieval on the Internet: *Google, 
  Microsoft Bing, Yahoo*, or software like *Apache Lucene*
* Translation: *Google Translate, DeepL, Bing translator*, etc.
* Spoken interaction: *Apple Siri, Google Assistant, Amazon Echo*
* Speech dictation of letters or reports: *Windows 10, macOS*
* Direct translation from spoken English to spoken Swedish in a restricted domain: *SRI* and *SICS*
* Voice control of domestic devices such as tape recorders: *Philips* or disc changers: *MS Persona*
* Conversational agents able to dialogue and to plan: *TRAINS*
* Spoken navigation in virtual worlds: *Ulysse, Higgins*
* Generation of 3D scenes from text: *Carsim*
* Question answering: *IBM Watson and Jeopardy!*

## Assignments

### Assignment 0: Spell Checker
Spell-checking is the task of predicting which words in a document are misspelled. Correction is the
task of substituting the well-spelled hypotheses for misspellings. In this assignment, we need to run and
comment the spell checker implemented by Peter Norvig in "How to Write a Spelling Corrector", http://norvig.com/spell-correct.html.

### Assignment 2: Building an inverted index
In this assignment, we need to write a Python program that first collects all the words from the corpus
of Selma Lagerl¨of, extracted from Lagerl¨of arkivet at Litteraturbanken. Then, we will learn how to build
an index from the collected words. At the end, we will get familiar with the Tf-Idf value to represent
documents. An additional task consists in reading about the history of Google indexing by Jeff Dean: "Challenges in Building 
Large-Scale Information Retrieval Systems", https://static.googleusercontent.com/media/research.google.com/en//people/jeff/
WSDM09-keynote.pdf

### Assignment 2: Language Models
In this second assignment, we will write Python programs to find n-gram statistics i a corpus of approximately one million words 
and to determine the probability of a sentence. After collecting the corpus,
we will deal with building a segmenter and discussing the perplexity concept using different language
models. At the end, as an application of n-grams, we will execute the Jupyter notebook by Peter Norvig.

### Assignment 3: Language Detector
In this assignment, we will apply and explore the supervised learning algorithm Multi-layer Perceptron
(MLP) for building a language classifier using Scikit-learn. We will consider Tatoeba dataset limited
to the three languages only: French (fra), English (eng), and Swedish (swe). The resulting language
detector is inspired from Google’s Compact Language Detector version 3, also called CLD3: https://github.com/google/cld3

### Assignment 4: Extracting Syntactic Groups using Machine Learning Techniques
In this assignment, we will work on important tasks in NLP as Part-of-speech (PoS) and Named Entity
Recognition (NER) tagging. In the first part, we will write a program to detect partial syntactic structures
from a text and applied to the CoNLL 2000 dataset, whereas in the second part we will deal with the
principles of supervised machine learning techniques applied to language processing for training a ML
model to detect noun groups.

### Assignment 5: Extraction of Subject-Verb-Object Triples
In this assignment, we are going to practice and deal with relation extraction, one of infromation
extraction (IE) tasks, and understand how dependency parsing can help create a knowledge base. We
will extract all the subject–verb pairs and subject–verb–object triples from a parsed corpus involving
two words or entities. The implemented program will use a parsed corpus of Swedish to extract the
pairs and triples and then it will be applied to other languages. This work is inspired by the Prismatic
knowledge base used in the IBM Watson system [Fan, Ferrucci and al. (2010)] "PRISMATIC: Inducing Knowledge from
 a Large Scale Lexicalized Relation Resource". IBM Watson Research Lab: https://www.aclweb.org/anthology/W10-0915.
pdf.

### Assignment 6: Dependency Parsing
In this assignment, we are going to explore dependency graph and understand the principles of a
transition-based parser. Using supervised machine learning techniques, we will extract features to
learn parsing actions from an hand-annotated corpus, and the annotated texts are then used to train
classifier/parser to annotate an unseen test set. This assignment is inspired by the CoNLL 2018 shared
task of the conference on computational natural language learning [Multilingual Parsing from Raw Text to 
Universal Dependencies: http://universaldependencies.org/conll18/], and the implemented parser
will be trained on the Swedish Talbanken corpus. In section 4, two different parsing experiments are
solved.



