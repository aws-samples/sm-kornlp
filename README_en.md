# Korean NLP downstream tasks Hands-on Labs on Amazon SageMaker

## Introduction

### Hugging Face on Amazon SageMaker
Although there are many AI/ML application cases for Natural Language Processing (NLP), such as text analysis, translation, sentence summarization, and entity classification, many customers still struggle with adoption due to technical barriers to adapt. Some people are already accelerating AIML adoption with the Hugging Face transformer library and many example codes from SageMaker. However, SageMaker did not natively support Hugging Face-specific containers until early 2021. Therefore, we had the difficulty of writing custom scripts and custom containers separately.

However, AWS recently introduced the Hugging Face Deep Learning training container and inference container, which make it easier to train and deploy Hugging Face's transformer models on Amazon SageMaker. Thus, it is possible to train and deploy NLP models quickly with just a few lines of code (low-code) without worrying about setting up the infrastructure.

### Korean Language Support
Hands-on lab for Korean language is highly sought after by those who are less technically mature or who are just starting to examine NLP models. However, we have seen that Hands-on labs for Korean language is not systematically organized, so it was difficult to introduce it. Accordingly, we have developed Korean Hands-on  labs that even beginners can easily start.

## Hands-on Labs
Each hands-on can be run independently. During the workshop, you can freely perform hands-on according to use-cases.

### [Multiclass Classification](multiclass-classification)

### [Named Entity Recognition (NER)](named-entity-recognition)

### [Question Answering](question-answering)

### [Chatbot and Semantic Search using Sentence-BERT (SBERT)](sentence-bert-finetuning)

### [Natural Language Inference (NLI)](natural-language-inference)

### [Summarization](summarization)

### [Translation](translation)

### [TrOCR](trocr)

<br>

## References
See [REFERENCES](REFERENCES.md) for more information.

## Security
See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License 
This project is licensed under the MIT-0 License. See [LICENSE](LICENSE) for more information.
However, pre-trained models and datasets other than this sample code follow their respective licenses. Please check each license for non-hands-on purposes.
