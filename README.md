**DOCUMENTATION**

**1.TITL:**

- Creating a QA Conversational chatbot using Langchain and OpenAI API

**2.DESCRIPTION:**

- This documentation provides an overview of the Conversational AI Bot implemented using the LangChain library and OpenAI API. The bot is designed to answer user questions based on content from a provided PDF document and maintain context through a simple memory mechanism.

**3.PREREQUISITES:**

Before using the Conversational AI Bot, make sure you have the following prerequisites-

- Python 3.6 
- OpenAI API Key
- LangChain Library

**4.INSTALLATION:**

- Clone the repository using the “git clone” command.
- Use the following command to install the required dependencies: 

“pip install langchain openai chromadb tiktoken pypdf ”

**5.USAGE:**

- Place the PDF document (DP1Merrill\_Manual\_en.pdf) in the same directory as the script. 
- Run the script-

“app.py”

- Follow the prompts to interact with the bot. Type your queries and see the bot's responses.

**6.COMPONENTS:**

The Conversational AI Bot comprises the following components:

- PDF Document Loader: Loads the content from the provided PDF document.
- Text Splitting: Divides the document content into smaller chunks for processing.
- OpenAI Embeddings: Generates embeddings for text chunks using the OpenAI API.
- Chroma Vector Store: Creates a vector store index using Chroma from LangChain.
- Retriever: Sets up a retriever interface for similarity-based searches.
- RetrievalQA Chain: Creates a conversational QA chain using LangChain's RetrievalQA class.
- Simple Memory: Maintains conversation history using the conversation\_history list.

**9. ACKNOWLEDGEMENTS:**

- This project utilizes various open-source libraries and technologies, including Langchain, OpenAI, and more. Special thanks to the developers of these tools for making this project possible.

**10. LICENSE:**

- This project is licensed under the MIT LICENSE.

**11. CONTACT INFORMATION:**

For any questions or feedback, please contact:

Name- Niket Virendra Patil

Email- pniket7@gmail.com






