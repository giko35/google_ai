# Google Gen-AI Integration

## Getting Started

Follow these instructions to set up your local environment and run the examples.

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-name>
```

### 2. Install Dependencies

Install the required packages using pip:
```bash
pip install python-dotenv langchain langchain-google-genai google-genai
```

### 3. Set Up Environment Variables

The examples in this repository require API key for Google AI. You need to create a `.env` file in the root of the project to store these secrets.

1. Create a file named `.env` in the project's root directory.
2. Add the following key-value pairs to the file:

```env
# Google AI API Key
# Get your key from: https://aistudio.google.com/apikey
GOOGLE_API_KEY="YOUR_GOOGLE_AI_KEY"
```

## Notebooks

- [Google AI Examples](./google_ai.ipynb) - Demonstrates using Google's Gemini models through both LangChain and direct API access
