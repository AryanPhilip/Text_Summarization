# Project: Extractive Text Summarization using Latent Semantic Analysis (LSA) and BERT

## Course Information

- **Course:** DSC 212 A: Numerical Linear Algebra for Data Science
- **Instructor:** Dr. Tsui-wei Weng
- **Group Members:** Aryan Philip, Asher Jacob, Saloni Reddy, Shivani Patnaik
## Instructions

Before running the notebook, make sure to have the following Python libraries installed in your environment:

- [scikit-learn](https://scikit-learn.org/)
- [tqdm](https://github.com/tqdm/tqdm)
- [nltk](https://www.nltk.org/)
- [transformers](https://huggingface.co/transformers) (for BERT)
- [ExtractiveSummarizer](https://pypi.org/project/bert-extractive-summarizer/)
- [Metrics:RougeScore](https://lightning.ai/docs/torchmetrics/stable/text/rouge_score.html)

### Running the Notebook

1. Open `BERT_Extractive_Summarizer.ipynb`.
2. Run all the cells of the notebook.

## Results

The project focuses on Extractive Text Summarization using two techniques: Latent Semantic Analysis (LSA) and BERT. These methods are implemented in the context of the DSC 212 course, Numerical Linear Algebra for Data Science.

Feel free to explore the notebook to understand the implementation details and insights gained through Extractive Summarization using LSA and BERT. Disclaimer this is just the inference notebook, the full code will be available however, it requires a GPU to run and is trained on a different dataset.

Table: A comparison between BERT and LSA
|   Metric   |  BERT  |   LSA   |
|:-----------:|:------:|:-------:|
|  ROUGE-1    | 0.3804 |  0.5582 |
|  ROUGE-2    | 0.3666 |  0.5464 |
|  ROUGE-L    | 0.3804 |  0.5582 |


![BERT_ROUGE_Metric](https://github.com/AryanPhilip/Text_Summarization/assets/150488197/2ec95432-92c2-4a02-ab8c-28b35d8a8c5a)


