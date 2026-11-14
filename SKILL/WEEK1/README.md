# Week 1 – First LLM API Call Using Gemini

## 1. Objective
To connect a Python application to a Large Language Model (LLM) using the Google Gemini API and generate AI responses through a simple prompt.

## 2. Technologies Used
- Python
- Google Gemini API
- Google GenAI SDK
- Python-dotenv
- Visual Studio Code

## 3. Project Structure

```text
WEEK1/
│
├── main.py
├── .env
├── .gitignore
└── README.md
```

## 4. Implementation

The application performs the following steps:

1. Loads environment variables from the `.env` file.
2. Retrieves the Gemini API key securely.
3. Initializes the Gemini client.
4. Sends a prompt to the Gemini model.
5. Receives and displays the AI-generated response.

## 5. Installation

Install the required Python packages:

```bash
python -m pip install google-genai python-dotenv
```

## 6. API Configuration

Create a `.env` file in the project directory.

Add your Gemini API key:

```env
GEMINI_API_KEY=your_api_key_here
```

**Note:** Never upload your actual API key to GitHub.

## 7. Execution

Run the Python program:

```bash
python main.py
```

## 8. Sample Prompt

```text
What is Artificial Intelligence? Explain in simple words.
```

## 9. Expected Output

The application displays an AI-generated explanation of Artificial Intelligence in the terminal.

The response includes a simple definition and real-world examples.

## 10. Learning Outcomes

- Understood the concept of Large Language Models.
- Learned how to connect Python with the Gemini API.
- Learned secure API key management using environment variables.
- Implemented a basic LLM API request.
- Generated AI responses using prompt input.

## 11. Conclusion

Successfully implemented the first LLM API call using Python and Google Gemini. This practical demonstrates how a Python application communicates with a cloud-based Large Language Model to generate natural-language responses.
