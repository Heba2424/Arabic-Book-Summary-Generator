# Arabic Book Summary Generator

## Overview
This project is an **Arabic Book Summary Generator** that utilizes GPT-2 (`Aragpt2`) to generate concise summaries of Arabic books based on their descriptions. It also includes a **Gradio interface** that allows users to interact with the model and generate summaries in real-time.

## Features
- Scrapes book data and summaries from the **Arab Books website**.
- Cleans and preprocesses Arabic text for training.
- Trains a **GPT-2 (Aragpt2)** model on the scraped data to generate book summaries.
- Provides an interactive **Gradio interface** for easy user interaction.
- Supports generating summaries for new book descriptions in Arabic.

## Project Workflow
1. **Data Collection**: 
   - Web scraping Arabic book data from [Arab Books](https://arab-books.com/).
   - Cleaning and preprocessing the text to prepare it for training.

2. **Model Training**:
   - Tokenizing and preparing the data for GPT-2 (`Aragpt2`) training.
   - Fine-tuning the GPT-2 model on the cleaned Arabic book summaries.

3. **Summary Generation**:
   - Using the fine-tuned model to generate summaries based on user-provided book descriptions.

4. **Deployment**:
   - Deploying a **Gradio interface** that allows users to input book descriptions and get automatically generated summaries.


