# QuranRel
An annotated semantic similarity corpus of the Holy Quran.

The corpus is based on a highly reputable Islamic scholar's book, أضواء البيان في تفسير القرآن بالقرأن. 

The dataset was experimented with Binary and Multi classification tasks as illustrated in my [PhD Thesis](https://etheses.whiterose.ac.uk/id/eprint/37334/)

You can find the Train, Validation and Test split csv files in their corresponding folders: Binary and Multi.

# Citation 
Please cite my dataset if you have used it in your work.


```
@phdthesis{wreo37334,
           month = {March},
           title = {Transformer-based Semantic Similarity Exploration on the Holy Quran},
          school = {University of Leeds},
            note = {Unpublished},
            year = {2025},
             url = {https://etheses.whiterose.ac.uk/id/eprint/37334/},
        keywords = {Quran; Semantic Similarity; BERT; Transformer; Question Answering; Passage Retrieval; Classical Arabic; Quranic Corpus},
          author = {Alsaleh, Abdullah Nassir A},
        abstract = {This PhD research explores the application of modern Natural Language Processing (NLP) techniques to the study of the Holy Quran, with a focus on semantic understanding. It addresses the challenges of working with Classical Arabic and explores how Transformer-based Arabic language models can be used to better understand relationships between Quranic verses, answer questions, and retrieve relevant passages.

The thesis makes four key contributions. First, it evaluates QurSim, a semantic similarity corpus in the Quran, and produces a cleaner version of the QurSim dataset to support more reliable experiments. Second, it applies Arabic pre-trained language models to three semantically related tasks: semantic similarity, question answering and passage retrieval, to demonstrate their potential and limitations in handling religious text. Third, it outlines the methods and strategies for tackling the tasks, identifying the most effective approaches to understanding the Quranic text.

The findings of this PhD thesis demonstrate two main contributions. First, the Arabic pre-trained Transformer-based language models can be effectively applied to Quranic text semantic tasks, although their performance varies depending on the nature of the task. Second, the thesis highlights the need for a new semantic similarity corpus of the Holy Quran, grounded in a Quranic exegesis that interprets the Quran through the Quran itself. These contributions advance the field of NLP for the Holy Quran in particular and Classical Arabic in general, providing tools and resources that open new pathways for the computational linguistics of religious text.}
}
```
