# Project: Extractive Text Summarization using Latent Semantic Analysis (LSA) and BERT

## Course Information

- **Course:** DSC 212 A: Numerical Linear Algebra for Data Science
- **Instructor:** Dr. Tsui-wei Weng

## Instructions

Before running the notebook, make sure to have the following Python libraries installed in your environment:

- [scikit-learn](https://scikit-learn.org/)
- [tqdm](https://github.com/tqdm/tqdm)
- [nltk](https://www.nltk.org/)
- [transformers](https://huggingface.co/transformers) (for BERT)

### Running the Notebook

1. Open `Extractive_Summarization_BERT.ipynb`.
2. Run all the cells of the notebook.

## Results

The project focuses on Extractive Text Summarization using two techniques: Latent Semantic Analysis (LSA) and BERT. These methods are implemented in the context of the DSC 212 course, Numerical Linear Algebra for Data Science.

Feel free to explore the notebook to understand the implementation details and insights gained through Extractive Summarization using LSA and BERT. Disclaimer this is just the inference notebook, the full code will be available however, it requires a GPU to run

---

*Note: Make sure to replace the placeholder links in the instructions with the actual URLs of the libraries if necessary.*
Top 5 words for each of the topics:
<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://user-images.githubusercontent.com/18485647/163595256-eaa19d1b-9c52-4cd2-9a63-b1dbcd728d23.png">

Distributions of top 3 topics to each document:
<p align="center">
<img width="33%" alt="Screen Shot 2022-04-15 at 9 19 11 AM" src="https://user-images.githubusercontent.com/18485647/163595137-f9ea7e72-1f20-417f-bad4-4161cfcbe2f3.png">
 <img width="33%" alt="Screen Shot 2022-04-15 at 9 20 03 AM" src="https://user-images.githubusercontent.com/18485647/163595234-1951d9bf-0a54-40ec-8002-50d0042be260.png">
 <img width="33%" alt="Screen Shot 2022-04-15 at 9 19 35 AM" src="https://user-images.githubusercontent.com/18485647/163595185-18ca8fcc-ef7d-48fe-b7a5-76bb485a80a2.png">
</p>
Visualized embedding of documents in 2-D space:
<img width="816" alt="Screen Shot 2022-04-15 at 9 23 07 AM" src="https://user-images.githubusercontent.com/18485647/163595568-e9d9fd26-986a-4c06-8bf8-3bfbb95dbc79.png">


* **Latent Dirichlet Allocation (LDA)**

Top 5 words for each of the topics:
<img width="844" alt="Screen Shot 2022-04-15 at 9 23 15 AM" src="https://user-images.githubusercontent.com/18485647/163595579-638c74c8-27f4-4ee2-ade2-e62406422600.png">

Distributions of top 3 topics to each document:
<p align="center">
  <img width="33%" alt="Screen Shot 2022-04-15 at 9 24 03 AM" src="https://user-images.githubusercontent.com/18485647/163595666-06612d57-978b-4245-b89f-72fdf4bc1f7e.png">
<img width="33%" alt="Screen Shot 2022-04-15 at 9 24 12 AM" src="https://user-images.githubusercontent.com/18485647/163595676-8fb7feb8-7471-440a-a19f-8c2735f987cb.png">
<img width="33%" alt="Screen Shot 2022-04-15 at 9 24 19 AM" src="https://user-images.githubusercontent.com/18485647/163595701-c097c01f-66f4-497a-af5b-4f63988e3284.png">
</p>

Visualized embedding of documents in 2-D space:
<img width="784" alt="Screen Shot 2022-04-15 at 9 24 38 AM" src="https://user-images.githubusercontent.com/18485647/163595735-bed01c6a-9d73-41be-8f34-284aee22ec91.png">



