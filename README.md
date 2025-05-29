# Scalable-Image-Classification-application-on-Amazon-Sagemaker
Building a scalable and safe image classification model on Amazon Sagemaker implemented with AWS Lambda Functions for supporting services and AWS Step Functions to merge them into an an event-driven application
**Deploy and Monitor a Machine Learning Workflow for Image Classification Using Amazon SageMaker**

---

## Overview

This project is part of the **AWS x Udacity Machine Learning Engineer Nanodegree Scholarship Program**.

The objective is to build and deploy an image classification model for **Scones Unlimited**, a scone-delivery-focused logistics company, using AWS SageMaker and related AWS services.

---

## Project Files

| File Name                                      | Description                                                                                      |
|-----------------------------------------------|------------------------------------------------------------------------------------------------|
| `starter.ipynb`                               | Jupyter notebook demonstrating the complete ML workflow: preprocessing, training, deployment, and monitoring. |
| `starter.html`                                | HTML version of the notebook for easy viewing in a browser.                                    |
| `lambda.py`                                   | AWS Lambda function scripts used in the Step Functions workflow, including the `lambda_handler`.|
| `step-function.json`                          | AWS Step Functions state machine definition in JSON format.                                    |
| `execution-detail.json`                        | Details of the execution output from the Step Functions workflow.                              |
| `Screenshot-of-Working-Step-Function (Lambda Successful Excution).png` | Screenshot showing a successful AWS Lambda execution within the Step Functions workflow.       |
| `Screenshot-of-Working-Step-Function-2.png`  | Additional screenshot of Step Functions execution details.                                     |
| `Screenshot-of-Working-Step-Function-Excution.png` | Screenshot depicting an execution overview of the Step Functions.                              |
| `Screenshot-of-Working-Step-Functions-Graph.png` | Visual graph of the Step Functions workflow state machine.                                     |

---

## Dependencies

- Python 3 (Data Science) — Kernel v3.7.10 for Jupyter Notebook
- AWS Lambda runtime — Python 3.8
- AWS SageMaker instance type — `ml.t3.medium`

---

## Installation and Setup

To run the notebook locally:

1. Install [JupyterLab](https://jupyter.org/install) if not already installed.

```bash
pip install jupyterlab
