# LexAI: Intelligent Legal Research Assistant

LexAI is a powerful, browser-based research assistant designed to help users extract insights from PDF documents. By leveraging Google's Gemini API, LexAI allows you to upload multiple documents and engage in a natural, cited conversation across your sources.

## Features

- **Multi-document Analysis**: Upload multiple PDFs and query them simultaneously.
- **Cited Answers**: Get precise, context-aware answers with references directly from your documents.
- **Document Previewer**: Integrated viewer to inspect source text easily.
- **Privacy-First**: All data is processed in-browser or via your personal API key; your documents remain local to your session.
- **Customizable**: Adjust model "creativity" (temperature) and chunk retrieval settings to optimize your research.
- **Responsive Design**: Built for both desktop and mobile research on the go.

## Getting Started

1. Visit the live app: [https://lex-ai-blond.vercel.app](https://lex-ai-blond.vercel.app)
2. Obtain your Google Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
3. Paste your API key into the "Gemini API Key" section in the left panel.
4. Upload your PDFs and start asking questions!

## Technology Stack

- **Frontend**: HTML5, CSS3 (with Flexbox/Grid), Vanilla JavaScript.
- **LLM Integration**: Google Gemini API.
- **PDF Processing**: `pdf.js`.
- **Deployment**: Vercel.

---
*Built as a research productivity tool.*
