# CaseStudy4

# Fashion Embeddings Application

This repository contains the source code and instructions for an application that computes embeddings for a fashion dataset, stores them using PINECONE, and provides an interface through FastAPI and Streamlit for searching images based on text descriptions or finding similar images.

## Dataset

The fashion dataset used in this application can be found in the following sources:
- [AI Datasets for Fashion E-Commerce](https://maadaa-ai.medium.com/ai-datasets-for-fashion-e-commerce-open-vs-commercial-and-the-trends-2b1937f5787b)
- [Papers with Code - Fashion200k](https://paperswithcode.com/datasets?q=Fashion200k)

## Application Overview

The application performs the following tasks:

1. Computes embeddings for the fashion dataset and stores them using PINECONE.
2. Build a dataset that links image IDs to text tags and embeddings.
3 Wraps the application in FastAPI, supporting functions for text-based image retrieval and finding similar images based on an uploaded image.
4. Create a Streamlit app that interacts with the FastAPI backend based on user input.

## How to Run the Application

### Prerequisites

- Python (version 3.10.11)
- Dependencies listed in `requirements.txt`

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/fashion-embeddings-app.git
cd fashion-embeddings-app

# Start FastAPI server:

uvicorn fastapi_app:app --reload

Run the Streamlit app:

streamlit run main.py


