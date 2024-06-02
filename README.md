# PDFQuery: Chat with PDF using Gemini

PDFQuery is a Streamlit-based web application that allows users to upload PDF files and ask questions about the content within those files. The app uses the LangChain framework, Google Generative AI for embeddings, and FAISS for vector storage to provide detailed answers based on the context of the uploaded PDFs.

## Features

- Upload multiple PDF files.
- Extract text from PDF files.
- Split text into manageable chunks.
- Embed text chunks using Google Generative AI embeddings.
- Store embeddings using FAISS.
- Perform similarity search to find relevant document chunks.
- Use a conversational AI model to answer questions based on the content of the PDFs.

## Installation

### Prerequisites

- Python 3.8 or higher
- [Streamlit](https://streamlit.io/)
- [Google API Key](https://console.cloud.google.com/apis/credentials) for Generative AI

### Setup

1. **Clone the repository:**

    ```sh
    git clone https://github.com/Rishitabansal9/PdfQuery.git
    cd PdfQuery
    ```

2. **Create a virtual environment and activate it:**

    ```sh
    python -m venv venv
    .\venv\Scripts\activate  # On Windows
    source venv/bin/activate  # On macOS/Linux
    ```

3. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Set up your environment variables:**

    Create a `.env` file in the root directory of the project and add your Google API key:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key
    ```

## Usage

1. **Run the Streamlit app:**

    ```sh
    streamlit run app.py
    ```

2. **Upload PDF files:**

    - Use the sidebar to upload your PDF files.
    - Click the "Submit & Process" button to process the files.
![image](https://github.com/Rishitabansal9/PdfQuery/assets/95099754/f84936b8-4cab-4a62-985b-03bacdfa551c)


3. **Ask questions:**

    - Enter your question in the text input box on the main page.
    - The application will display the answer based on the content of the uploaded PDFs.


## Project Structure

- `app.py`: The main Streamlit application file.
- `requirements.txt`: The list of required Python packages.
- `.env`: File to store environment variables (e.g., Google API key).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


