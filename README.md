# DD2430 Sentiment Classification
## General
This repo contains the code that was used to generate the results presented in the report of the project. In the code we load both data from SQL tables and from pkl files, but those files are intentionally left out opf this project due to the sensitive information that is in the data. 

## File structure
In this repo there are three main folders 
- `/helpers`
- `/models`
- `/plots`

## Helpers
In the helpers folder we provide some code that we have used throughout the project, but that is not used in the final experiments with the GAN-BERT architecture. This includes
- data laoding from BQ
- Language detection of the unlabeled data
- division of data into training and test sets
- Functions to modify the data distribution between negative and positive comments in the labeled data 
- Sentiment classification using external implementation applied to our data

## Models
In this folder we include the code for the experiments, specifically
- the different architectures
- alter percentages of labeled data

## Plots
In this folder we provide the functions that we have used to plot our results