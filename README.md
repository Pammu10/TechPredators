# Team Name - Tech Predators

## Problem Statement - Generative AI Large Language Models Fine Tuned For Legal Practice Platform

## Team Leader Email - [Nikhil Bansal](mailto:nikhil@example.com)

## A Brief of the Prototype:
Leaf Disease Detection using Image Classification is a project aimed at developing a robust system for automated identification and classification of diseases affecting plant leaves. 
Leveraging machine learning algorithms and image processing techniques, the project focuses on training a model to accurately classify images of leaves into healthy or diseased categories, and further classify the diseased leaves into specific disease types. 
The system aims to provide farmers and agricultural stakeholders with a reliable tool for early detection of leaf diseases, enabling timely interventions to prevent crop losses and optimize agricultural practices.

## Dataset:
https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf

## Tech Stack:
**Intel® oneAPI Tensorflow Library (intel-tensorflow):**
   - Use intel-tensorflow for optimized deep learning operations, accelerating the training and inference processes of the fine-tuned LLAMA-2 model.
     ```python
     import intel-tesnorflow
     ```
This libraries from the Intel® oneAPI AI Analytics toolkit provided an optimized deep learning training experience, contributing to the efficiency and performance of the leaf disease detection platform.

## Step-by-Step Code Execution Instructions:
##Commands for setup a new server - 

Install anaconda with this guide-
https://www.digitalocean.com/community/tutorials/how-to-install-the-anaconda-python-distribution-on-ubuntu-22-04

AI toolkit installation-
https://www.intel.com/content/www/us/en/developer/tools/oneapi/ai-analytics-toolkit-download.html?operatingsystem=linux&distributions=offline

Clone this repo and follow instructions from step 3 onwards from README-
https://github.com/vishnumadhu365/oneapi-devsummit-sea-2023


##Running backend fastAPI server

You need to have python(version 3.11 or lesser) installed 
Check here to install it https://www.python.org/downloads/

Go to proper project directory
```cpp
cd tomato_disease_classification/api
```


Run server using command:
```cpp
python main.py
```


Go to project directory:
```cpp
cd /root/hackathon/oneapi-devsummit-sea-2023/
```


Activate virtual environment:
```cpp
source itex_cpu/bin/activate
```

start python application:
```cpp
python hackathon-notebooks/rag_llm_serviceV2.py
```

## Future Scope:
The prototype exhibits notable scalability and forward-looking features that position it as an advanced solution for the evolving landscape of legal document research. Leveraging Intel technologies such as oneAPI Threading Building Blocks and oneDAL, the platform efficiently scales to handle a substantial volume of legal documents. This not only ensures optimal performance but also primes the system for accommodating future expansions in legal data repositories.#  