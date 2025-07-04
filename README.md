# Book-Recommendation-App

This is a lightweight, fast, and token-free book recommendation web app built using `flan-t5-base`, LangChain, and Gradio. Based on the user's input about their reading interests, the app returns 5 book suggestions categorized by reading level.

## Features

- No API keys or Hugging Face tokens required
- Uses the `google/flan-t5-base` instruction-tuned model
- Categorizes books as Beginner, Intermediate, Advanced, and General
- Fast response and small memory footprint
- Simple Gradio interface for real-time use

## Installation

Install the required packages:

```bash
pip install transformers langchain langchain-community gradio
