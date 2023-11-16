# Building-Natural-Language-Pipelines
Building Natural Language Pipelines published by Packt

## Setting up

Set up a virtual environment and install the required packages:

### Set up

If you have completed the following, you may discard this information. Otherwise, as a reminder and to ease installation, you can follow the instructions below.  

Throughout this book we will be using `pip` and `conda` for package management. We will also create an isolated `conda` environment with Python 3.10.  

We recommend that you install Miniconda and VSCode. We also recommend that you install GitHub (GitBash for Windows or Git for Linux and Mac) to make the process of accessing the material locally easier.   

* Install Miniconda: https://docs.conda.io/projects/miniconda/en/latest/  

* Install VSCode: https://code.visualstudio.com/docs/setup/setup-overview  

To obtain the code and exercises, clone the repository: 

Open VSCode, Click File-> New Window, then Terminal ->New Terminal. Ensure your terminal is of type “Bash” or “Command line”.  


Within the terminal, type each of the commands (a command is identified by the $ sign) below, one by one. Then press enter.  

```bash

$ git clone https://github.com/PacktPublishing/Building-Natural-Language-Pipelines.git 

$ cd building-natural-language-pipelines/ 

$ conda create –-name llm-pipelines python==3.10 

$ conda activate llm-pipelines 

$ pip install poetry, haystack-ai

$ poetry install
```

Enable the Jupyter Notebook extension on VSCode through the extension marketplace. When you open a notebook, press on ‘Select Kernel’ and click on `llm-pipeline` as our environment. 

