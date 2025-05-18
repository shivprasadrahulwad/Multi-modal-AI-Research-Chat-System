# M.A.R.S (Multi-modal AI Research System) 

[*M.A.R.S demonstration video*](https://github.com/user-attachments/assets/f6ef7dda-727a-4e59-b5b3-656f49d1c3f3)

# Try It Now
Experience the power of M.A.R.S yourself by visiting [M.A.R.S Web App](https://m-a-r-s.streamlit.app/).

## Experience the power of M.A.R.S - your ultimate AI assistant, like a chatbot on steroids

## Introduction
M.A.R.S. (Multi-modal AI Research System) is an innovative platform designed to revolutionize information access by seamlessly integrating various artificial intelligence technologies. Developed by Sahil Bhoite, this project aims to provide users with comprehensive capabilities for extracting, analyzing, and interpreting data from a wide range of file formats.

## Key Features
- **Intelligent File Extraction:** M.A.R.S employs advanced AI algorithms to extract key information from diverse file types, including PDFs, audio files, images, code snippets, and more.
- **Retrieval Augmented Generation (RAG):** M.A.R.S leverages cutting-edge RAG technology to enhance AI responses with real-time information retrieval from your documents, providing more accurate and contextually relevant answers.
- **User-Friendly Interface:** With its intuitive interface, M.A.R.S ensures a seamless user experience, allowing individuals to navigate through files, analyze content, and perform tasks with ease.
- **Versatile Functionality:** From querying file contents and conducting data analysis to generating commands and creating presentations, M.A.R.S offers a myriad of functionalities to meet the diverse needs of its users.
- **Cutting-Edge AI Technologies:** Powered by state-of-the-art AI technologies, including natural language processing (NLP), optical character recognition (OCR), and speech recognition, M.A.R.S delivers accurate results and enhances productivity.
- **Streamlined File Management:** By simplifying file management processes and optimizing workflows, M.A.R.S enables users to streamline their tasks and focus on driving innovation and growth.

## File Type Support
M.A.R.S supports a wide range of file types, including:
1. PDF
2. PPT/PPTX
3. Python scripts (.py)
4. Microsoft Word documents (.docx, .doc)
5. Excel spreadsheets (.xls, .xlsx)
6. CSV files (.csv)
7. HTML files (.html)
8. CSS files (.css)
9. JSON files (.json)
10. SQL scripts (.sql)
11. Plain text files (.txt)
12. Java source code files (.java)
13. C source code files (.c)
14. C++ source code files (.cpp)
15. JavaScript files (.js)
16. Swift source code files (.swift)
17. R scripts (.r)
18. Rust source code files (.rs)
19. Image files (.jpg, .jpeg, .png, .bmp)
20. XML files (.xml)
21. Markdown files (.md)
22. LaTeX files (.tex)
23. Zip archives (.zip)
24. RAR archives (.rar)
25. Audio files for transcription (.wav)
26. Websites

## Functionality and Use Cases
- **Text Extraction:** Extracting text from various file types for analysis or processing.
- **Audio Transcription:** Transcribing speech from audio files for documentation or analysis.
- **Code Analysis:** Extracting and analyzing code snippets for optimization or debugging.
- **Data Extraction:** Extracting structured data from files like Excel spreadsheets or JSON files.
- **Document Processing:** Extracting content from Word documents or PDFs for further analysis.
- **Image Text Recognition:** Extracting text from images for digitization or analysis.
- **File Compression Handling:** Extracting text from compressed files like ZIP or RAR archives.
- **Structured Data Handling:** Processing structured data from files like XML or JSON.
- **Document Markup Conversion:** Converting documents from Markdown or LaTeX format to plain text.
- **Text Summarization:** Summarizing large documents or articles for quick insights.
- **Language Translation:** Translating text between different languages for multilingual support.
- **Named Entity Recognition (NER):** Identifying and categorizing entities within text for analysis.
- **Sentiment Analysis:** Analyzing sentiment expressed in textual data for understanding public opinion.
- **Topic Modeling:** Identifying topics or themes present in a collection of documents.
- **Document Similarity Detection:** Identifying similarities between documents based on content.
- **Question Answering (QA):** Providing accurate responses to user questions based on relevant information within text data.
- **Semantic Search:** Retrieving documents or passages relevant to a user's query based on semantic similarity.
- **Code Generation:** Automatically generating code snippets based on user requirements or specifications.
- **Web Scraping:** Extracting information from web pages for data collection or analysis.

## RAG (Retrieval Augmented Generation)
M.A.R.S now features powerful Retrieval Augmented Generation capabilities, enhancing the system's ability to provide accurate and contextually relevant information:

### RAG Features
- **Smart Document Retrieval:** M.A.R.S indexes your documents to create vector embeddings, enabling intelligent semantic search and retrieval.
- **Context-Aware Responses:** By retrieving relevant information from your uploaded documents, M.A.R.S generates responses that are grounded in your specific context.
- **Knowledge Base Integration:** Create your own knowledge base by uploading documents, which M.A.R.S will reference when answering your queries.
- **Reduced Hallucinations:** RAG significantly improves response accuracy by basing answers on actual document content rather than model memory.
- **Up-to-date Information:** Access information contained within your most recent documents, regardless of when they were created.

### How RAG Works in M.A.R.S
1. **Document Processing:** When you upload documents, M.A.R.S processes and chunks them into manageable pieces.
2. **Vector Embedding:** Each chunk is converted into vector embeddings using advanced embedding models.
3. **Similarity Search:** When you ask a question, M.A.R.S searches for the most relevant document chunks based on semantic similarity.
4. **Contextual Response Generation:** The retrieved document chunks are used as context for the AI model to generate accurate, informative responses.

### RAG Use Cases
- **Technical Documentation:** Query complex technical documents and receive precise answers.
- **Legal Document Analysis:** Extract specific clauses or information from legal documents.
- **Research Paper Exploration:** Efficiently extract insights from academic papers.
- **Company Knowledge Base:** Build an organizational knowledge repository for easy information access.
- **Educational Material:** Create interactive learning experiences based on course materials.

## Conclusion
With its comprehensive set of features and cutting-edge AI technologies including RAG, M.A.R.S empowers users to unlock the full potential of their data and streamline their workflows. Whether it's extracting insights from documents, analyzing code, transcribing audio, or finding specific information within a large document corpus, M.A.R.S offers unparalleled capabilities for information access and analysis.

## Getting Started
To get started with M.A.R.S, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. You can get your Google API key [here](https://ai.google.dev/tutorials/setup). Run the `mars.py` file to launch the application.
4. Upload your files and start exploring the various functionalities offered by M.A.R.S.

## RAG Setup (Additional Steps)
To enable RAG capabilities:
1. Install the vector database dependencies with `pip install faiss-cpu` (or `faiss-gpu` for GPU support).
2. Configure your embedding model by setting the `EMBEDDING_MODEL` environment variable or updating the config file.
3. Ensure you have sufficient storage for the vector database, which will grow as you add more documents.

## Feedback and Contributions
Your feedback is valuable in improving M.A.R.S and making it even more useful for users. If you encounter any issues or have suggestions for improvement, please don't hesitate to open an issue or submit a pull request on GitHub.

## License
This project is licensed under the [Apache License](LICENSE).
