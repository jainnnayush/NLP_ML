# TV Series Analysis Platform with Interactive Character Chatbot 

Authors: Ayush Jain (ayush.cl21@iitg.ac.in), Bhadra Tendulkar (t.bhadra@iitg.ac.in), Abhijit Pandey (p.abhijit@iitg.ac.in)

In this project we are going to analyze a series with NLP and LLMs. We are going to scrape our own dataset, use zero shot classifiers, build our own LLM text classifier, use NER to build a character network and build a charatecter chatbot to chat with your favorite characters. And in the end we are going to put all that in web GUI with Gradio.

## Overview

1) Used Scapy for scraping of data to build dataset and used \textbf{Spacy's NER Model, NetworkX and VizPy} to create character network.
2)  Developed a chatbot using Meta-Llama-3-8B-Instruct as base model and fine-tuned it using LoRA and SFT.
3) Built a Text Classifier using DistilBERT and HuggingFace Autotokenizer for category prediction.

## Requirements: 
Before running the code, please ensure that you install the neccessary requirements using pip. 

```pip install -r requirements.txt```
