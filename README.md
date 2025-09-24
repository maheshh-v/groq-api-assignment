# Groq API Assignment: Conversation Management & Information Extraction

This project is a submission for an AI internship assignment. It demonstrates the use of the Groq API to perform two core tasks without relying on high-level frameworks.

## Features

1.  **Task 1: Conversation Management**
    * A chatbot that maintains a running conversation history
    * Demonstrates history truncation by a fixed number of turns
    * Implements an intelligent periodic summarization of the conversation every 3 turns to maintain long-term context

2.  **Task 2: Structured Information Extraction**
    * Uses a JSON schema and the Groq APIs "Tool Calling" feature.
    * Extracts key details (name, email, phone, etc.) from natural language and returns a structured JSON object

## How to Run

The entire implementation is contained within the Google Colab notebook: `Groq_Internship_Assignment.ipynb`

To run it, please open the notebook in Google Colab and add your Groq API key to the Colab Secrets manager with the name `GROQ_API_KEY`.
