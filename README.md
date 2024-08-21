# Drug Classification App

[![CI](https://github.com/kingabzpro/CICD-for-Machine-Learning/actions/workflows/ci.yml/badge.svg)](https://github.com/amitca75/drug-classification-app/actions/workflows/ci.yml)
[![Continuous Deployment](https://github.com/kingabzpro/CICD-for-Machine-Learning/actions/workflows/cd.yml/badge.svg)](https://github.com/amitca75/drug-classification-app/actions/workflows/cd.yml)

[![Open in Spaces](https://huggingface.co/datasets/huggingface/badges/resolve/main/open-in-hf-spaces-md-dark.svg)](https://huggingface.co/spaces/amitca75/Drug-Classification)

## Description

The project uses scikit-learn pipelines to train a random forest classifier and build a drug classifier. After training, it automates the evaluation process using Continuous Machine Learning (CML). Finally, it builds and deploys the web application to Hugging Face Hub.

From training to evaluation, the entire process is automated using GitHub actions. Once the code changes are pushed to the repository, a CI/CD pipeline is triggered which trains and evaluates the model and finally, pushes the app to HuggingFace Spaces for deployment. 

## Architecture

![CICD](./asset/CICD-pipeline.png)

## Libraries Used

* scikit-learn
* numpy
* pandas
* matplotlib
* skops
* black
* gradio