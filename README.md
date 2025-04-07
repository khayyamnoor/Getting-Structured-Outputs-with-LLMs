LLM Structured Output Showcase using OpenAI API
Project Overview
This project demonstrates how to integrate OpenAI's GPT-4 model with structured output handling. It focuses on generating JSON-formatted responses using function calling, exploring the concept of logits in token prediction, and constraining outputs using regex to ensure predictable, structured results. The project also includes sentiment analysis to classify user feedback into categories like positive or negative.

Features
Structured Outputs with JSON: Leverages OpenAI's function calling feature to generate structured feedback in JSON format, making it easy to use and process in applications.

Logits and Token Prediction: Explores how logits (raw token scores) guide token prediction in language models. Though raw logits are not accessible through the API, understanding this concept is essential for interpreting model behavior.

Regex Constrained Outputs: Implements regex constraints to ensure outputs are in a specific format (e.g., positive or negative), improving reliability in automated sentiment analysis tasks.

Key Learning Outcomes
Understanding how to use OpenAI's function calling to extract structured data.

Gaining insights into the role of logits in token prediction.

Using regex to constrain model outputs to predefined formats for specific tasks like sentiment analysis.

Requirements
Python 3.x


Pydantic library

Install dependencies:
bash
Copy
Edit

Project Structure
main.py: The main script that integrates OpenAI API and demonstrates sentiment analysis, logits explanation, and regex output constraints.

requirements.txt: A list of dependencies required for the project.

README.md: This file.

Contributing
Feel free to fork this repository, submit issues, and create pull requests. Contributions are welcome!
