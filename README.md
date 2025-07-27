# Deploying a Databricks Asset Bundle (DAB) using Azure DevOps Pipelines

This GitHub repo contains the code discussed in the [article on my website](https://gontcharov.eu/posts/blog/databricks-dab-azure-devops-pipelines).

## Contents

The project directory in the Git repository consists of just three files and a README:

```stdout
.
├── README.md --> Documentation
├── azure_devops_pipeline.yml --> Azure DevOps pipeline YAML file
├── databricks.yml --> The DAB YAML file with a notebook task
└── demo_notebook.ipynb --> The minimal Databricks notebook
```

## Objective

The DAB defines a simple Databricks job with one notebook task that reads and prints a value from a notebook widget. This DAB is deployed to a Databricks Free Edition workspace using an Azure DevOps Pipeline.

For more information, refer to the full [article on my website](https://gontcharov.eu/posts/blog/databricks-dab-azure-devops-pipelines).

***
