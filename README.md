# End To End Document QA With Google Gemma
 
This repository contains a Streamlit-based application that allows users to interact with PDF files by asking questions. It leverages Google Gemini models for language processing, embeddings, and question-answering. The application uses Google Generative AI and FAISS for efficient document search and retrieval.

## Features

- **PDF-Based Q&A**: Upload PDF files and ask questions based on the content of the PDFs.
- **Google Gemini Integration**: Uses Google Gemini models for accurate and generative question-answering.
- **FAISS Vector Store**: Efficiently retrieves relevant content from the PDFs using embeddings.

## Project Structure

- `app.py`: The main Streamlit app for PDF-based question-answering.
- `requirements.txt`: List of required Python packages for the project.
- `.env`: Environment variables file for API key configuration.

## Installation

To run this application, follow these steps:

### 1. Clone the repository
```bash 
git clone https://github.com/4Pranjal/End-To-End-Document-QA-With-Google-Gemma.git
```
## 2. Set up a Python virtual environment 
   ```bash
   python3 -m venv venv
   ```
or you can use conda to create environment.
On Windows use
   ```bash
venv\Scripts\activate
   ```
## 3. Install dependencies
Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 4. Set up environment variables
Create a .env file in the root directory of your project.
Inside this file, set your Google API key:
To get the API key sign with google account and create a new key from the project.
https://ai.google.dev/aistudio
   ```bash
GOOGLE_API_KEY=your_google_api_key_here
   ```
You can get your API key from the Google Cloud Console.

## 5. Run the applications
You can run each application by navigating to the project folder and executing the following command:

For Q&A Chatbot:
   ```bash
   streamlit run app.py
   ```
![Capture](https://github.com/user-attachments/assets/7e1c9b7c-dd96-4a9c-8a96-fad435fe9114)

## Contributors

- [Pranjal Jain](https://github.com/4Pranjal)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

