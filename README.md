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

![LSA ROUGE Metric](https://github.com/AryanPhilip/Text_Summarization/assets/150488197/4ad4c227-de14-4876-aad8-40f571510e1b)

## Additional Training Code (if needed):

-[Reference Code](https://github.com/entbappy/End-to-end-Text-Summarizer)

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the conponents
6. update the pipeline
7. update the main.py
8. update the app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/AryanPhilip/Text_Summarization
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n summary python=3.8 -y
```

```bash
conda activate summary
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


```bash
Author: Krish Naik
Data Scientist
Email: krishnaik06@gmail.com

```



# AWS-CICD-Deployment-with-Github-Actions

## 1. Login to AWS console.

## 2. Create IAM user for deployment

	#with specific access

	1. EC2 access : It is virtual machine

	2. ECR: Elastic Container registry to save your docker image in aws


	#Description: About the deployment

	1. Build docker image of the source code

	2. Push your docker image to ECR

	3. Launch Your EC2 

	4. Pull Your image from ECR in EC2

	5. Lauch your docker image in EC2

	#Policy:

	1. AmazonEC2ContainerRegistryFullAccess

	2. AmazonEC2FullAccess

	
## 3. Create ECR repo to store/save docker image
    - Save the URI: 566373416292.dkr.ecr.us-east-1.amazonaws.com/text-s

	
## 4. Create EC2 machine (Ubuntu) 

## 5. Open EC2 and Install docker in EC2 Machine:
	
	
	#optinal

	sudo apt-get update -y

	sudo apt-get upgrade
	
	#required

	curl -fsSL https://get.docker.com -o get-docker.sh

	sudo sh get-docker.sh

	sudo usermod -aG docker ubuntu

	newgrp docker
	
# 6. Configure EC2 as self-hosted runner:
    setting>actions>runner>new self hosted runner> choose os> then run command one by one


# 7. Setup github secrets:

    AWS_ACCESS_KEY_ID=

    AWS_SECRET_ACCESS_KEY=

    AWS_REGION = us-east-1

    AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

    ECR_REPOSITORY_NAME = simple-app
