# PDF-Chat: Interact with Your PDFs in a Conversational Way

PDF-Chat is a Streamlit application that allows users to upload PDF documents, ask questions, and receive answers directly from the content of the documents. It leverages OpenAI to process and understand the content, and provides a user-friendly interface for interaction.

## Installation

1. Clone this repository to your local machine.
2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```
3. Install the required dependencies from the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Navigate to the URL provided in the terminal.
3. Enter your OpenAI API key when prompted.
4. Upload your PDF document.
5. Enter your question or prompt in the text input box.
6. The app will display the response based on the content of the uploaded PDF.

## Features

- Upload PDF documents and interact with them in a conversational manner.
- Get responses to your queries directly from the content of the documents.
- Explore document similarity search to find relevant pages in the document.
- Built with Streamlit for a user-friendly interface.
- Utilizes OpenAI for natural language understanding and processing.

## Dependencies

- Streamlit for building the web application.
- Langchain for interacting with OpenAI and handling PDF documents.
- OpenAI for natural language understanding and processing.
- Pillow for image handling.

Make sure to check the `requirements.txt` file for the complete list of dependencies and their versions.

## License

This project is open-source and available under the [MIT License](LICENSE).
```

Adjustments may be needed to fit the exact nature and structure of your project, such as the file name `app.py` which I assumed based on standard practice, and the License link at the end which should point to your actual LICENSE file if you have one.
