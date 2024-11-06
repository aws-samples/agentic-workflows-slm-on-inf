# Keeping it Small: Agentic Workflows with SLMs on AWS Inferentia

## Introduction

This repository contains code and resources for the reInvent session: "Keeping it Small: Agentic Workflows with SLMs on AWS Inferentia". By using the resources in this repository, you will create a personalized website that balances the innovative capabilities of LLMs with adherence to human directives and human-curated assets for a consistent and responsible personalization experience for the customers of a fictional company named OneCompany Consulting.

## Overview

To help you create OneCompany Consulting's website, we've broken each step of the website development process into several smaller, more specific sub-tasks that will each be performed by a specialized agent (LLM). This approach will ensure that your resulting website adheres to the company's guidelines, messaging, and related rules, while incorporating industry pain points, user experience (UX) and user interface (UI) design systems, and human-curated elements.

## Prerequisites

To use this repository, you need the following:

- An AWS account
- AWS Command Line Interface (AWS CLI) installed
- Python and the AWS SDK for Python (Boto3) set up
- Amazon SageMaker Studio or Studio Domain
- AWS Inferentia instances

## Usage

The notebooks in this repository will guide you through the following processes:

- Deploying a Llama3.1-8B model to a Amazon SageMaker endpoint on an AWS Inferentia instance.
- Deploying a Stable Diffusion XL model to a Amazon SageMaker endpoint on an AWS Inferentia instance.
- Generating a detailed website description and visual element descriptions using a personalizer LLM (Llama 3.1 8B)
- Creating visual assets using an image generator LLM (Stable Diffusion XL)
- Deploying the generated website assets to an Amazon S3 bucket

## Data and Sources of Truth

The repository includes fictitious references and data sources created manually or generated using language models. These resources serve as examples and should be replaced with your own company guidelines, design systems, and industry-specific data in real-world scenarios.

## Clean up

To clean up the resources created during the walkthrough, follow the instructions provided in the "Clean up" section of each notebook.

## Conclusion

This repository demonstrates how to use an agentic approach to build a customized website for a customer of the fictional company, OneCompany Consulting. It leveraged LLMs such as Llama3.1-8B and Stable Diffusion XL (SDXL) to generate text and images to create a personalized website, and explains how to deploy each of these models on AWS Inferentia.

## Additional Resources

[Optimum Neuron](https://huggingface.co/docs/optimum-neuron/en/index)  
[HuggingFace Text Generation Inference on Neuron](https://huggingface.co/docs/optimum-neuron/en/guides/neuronx_tgi)  
[AWS Neuron](https://awsdocs-neuron.readthedocs-hosted.com/en/latest/index.html)

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
