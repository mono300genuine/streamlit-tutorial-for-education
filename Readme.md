# 🦜🔗 Quickstart App ( 👑 Streamlit First Tutorial )
This is a simple Streamlit application that interacts with OpenAI's language model using the LangChain library. Users can input text, and the app will generate a response using OpenAI's API.

# Features
- Simple user interface with Streamlit.
- Sidebar input for OpenAI API key.
- Text area for user input.
- Generates responses from OpenAI's language model.

# Requirements
- Python 3.7+
- Streamlit
- LangChain
- OpenAI Python client

# Installation
1. Clone the repository:

    ```bash
    git clone https://github.com/mono300genuine/streamlit-tutorial-for-education.git
    cd streamlit-tutorial-for-education

2. Create and activate a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install streamlit langchain openai
    ```

# Usage
1. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

2. Open your browser and navigate to:

    ```bash
    http://localhost:8501
    ```

3. Enter your OpenAI API key in the sidebar.

4. Input text in the text area and click "Submit" to generate a response.

# Deploy the app
## Deploying the app is super simple:

> Create a GitHub repository for the app.
In Streamlit Community Cloud ( https://share.streamlit.io/ ), click the Create app button, then specify the repository, branch, and main file path.
Click the Deploy! button.
And here it is!

