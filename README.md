# Document-Summarization-QA-Chatbot 
<h1>Overview</h1>
<p>This project implements an interactive document summarization and Q&A chatbot using the Ollama API and the Llama 3.2 model. The chatbot is capable of processing long text documents, summarizing key information, and answering questions based on the content of the uploaded document. The project uses LangChain for advanced document chunking, summarization, and context-aware responses.</p>

<h1>Features</h1>
<b>Document Summarization:</b> Automatically summarizes the content of uploaded documents.
<br><b>Q&A Interaction:</b> Allows users to ask questions based on the content of the document and receive context-aware answers.
<br><b>Chunking and Summarization:</b> Breaks large documents into chunks and generates summaries for each section.
<br><b>User-friendly:</b> Simple interface for users to upload documents and ask questions via the chatbot.

<h1>Technologies Used</h1>
<b>Ollama API:</b> Provides access to the Llama 3.2 model for document summarization and Q&A tasks.
<br><b>Llama 3.2:latest Model:</b> Used for processing and generating context-based summaries and answers.
<br><b>LangChain:</b> Framework used for document chunking, summarization, and managing document workflows.
<br><b>Python:</b> Programming language used for implementing the project.
<br><b>Jupyter Notebook:</b> Interactive environment used to develop and demonstrate the solution.
  
<h1>Installation</h1>
<h2>Prerequisites</h2>
<br>Before running the project, ensure you have the following installed into your local machine:
<ul>
  <li>Python 3.10.9</li>
  <li>Jupyter Notebook</li>
  <li>Ollama</li>
  <li>Llama3.2:latest</li>
  <li>Pip (Python package manager)</li>
</ul>

<h2>Install Dependencies</h2>
Install the required Python libraries using pip:
<br>pip install -r requirements.txt

<h2>API Key for Ollama</h2>
To interact with the Ollama API, you need to set up an API key.
<br>Follow these steps to get your API key:
<ol>
  <li>Obtain your API key here: https://github.com/ollama/ollama/blob/main/docs/api.md</li>
  <li>Set your API key in the project by adding it to your environment variables or directly in the code (ensure to keep it private).</li>
</ol>

<h2>Running the Project</h2>
<ol>
  <li>Open Jupyter Notebook and navigate to the folder containing the project.</li>
  <li>Open the document_summarization_qa_chatbot.ipynb notebook.</li>
  <li>Run the cells to initialize the chatbot and start interacting with the document summarization system.</li>
</ol>

<h1>Usage</h1>
<ol>
<li><b>Upload a Document:</b></li>
Upload your document in supported formats (e.g., .txt, .pdf) to the chatbot interface.
<li><b>Summarize the Document:</li></b>
The system will automatically generate a summary of the uploaded document based on the Llama 3.2 model’s analysis.
<li><b>Ask Questions:</b></li>
Once the summary is generated, you can ask specific questions related to the content of the document. The chatbot will provide context-aware answers.
</ol>

<h3>Example Interaction:</h3>

User: Summarize the document.
<br>Bot: [Generated summary of the document]

User: What are the main findings in section 2?
<br>Bot: [Answer based on the content of section 2]


<h2>Contributing</h2>
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Make sure to follow the coding style and include tests for new features.

<h2>Acknowledgments</h2>
<ul>
<li>Ollama API for providing access to the Llama 3.2 model.</li>
<li>LangChain for simplifying document processing and chunking.</li>
</ul>
