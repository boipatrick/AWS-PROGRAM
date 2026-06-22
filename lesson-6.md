## Optimizing Foundational Models

## Retrieval-Augmented Generation
Allows FMs to query knowledge bases to provide accurate and up-to-date answers to customer prompts. 


### Storing vectors
Their purpose is to compactly store billions of high dimensional vectors representing words and entitites. Vector databases provide ultra-fast similarity searches across these billions of vectors in real time. 

Evaluate Results
Evaluating performance of generative AI models is critical for understanding their effectiveness and ensuring they meet their intended objectives.

The two most common evaluation methods are human evaluation and the use of bench mark datasets. 

Each method provides unique insighs and is suitable for different aspects of model performance assessment.


## Model Evaluation
### Recall Oriented Understudy for Gisting Evaluation(ROUGE)
A set of metrics used to evaluate automatic summarization of texts,in addition to machine translation quality in NLP.
The main idea behind ROUGE is to count the number of overlapping units. This includes words, N-grams, or sentence fragments between the computer-generated output and a set of reference(human-created) texts.

It is widely used because it is not complex and it is interpretale, and correlates reasonably well with human judgement, especially when evaluating the recall aspect of summaries.

Theevalutaion assess how much of the important information in the source texts is captured by the generated summaries.

### BLEU
Metric used to evaluate the quality of text that has been machine-translated from one natural language to another. 

Quality is calculated by comparing the machine-generated text to one or more high-quality human translations. BLEU measures the precision of N-grams in the machine generated text that appears in the reference texts and applies a penalty for overly short translations.

### BERTScore
Uses the pretrained contextual embeddings from models like BERT to evaluate the quality of text-generation tasks. 

