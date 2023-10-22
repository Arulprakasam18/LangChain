# LangChain
ChatGPT for YOUR OWN PDF files with LangChain
Abstract:

In this project, we demonstrate how to use LangChain to create a ChatGPT-like interface for PDF files. LangChain is a framework for developing applications powered by language models. It allows you to connect your language model APIs to other sources of data, and then it allows the language model to interact with its environment.

In this case, we use LangChain to connect OpenAI's ChatGPT to a corpus of PDF files. We first extract the text from the PDF files and then create embeddings for each chunk of text. We then use these embeddings to power a semantic search engine. When the user asks a question, the semantic search engine finds the most relevant chunks of text from the corpus. These chunks of text are then passed to ChatGPT, which generates an answer.

The resulting system is a ChatGPT-like interface for PDF files. The user can ask questions about the contents of the PDF files, and the system will generate answers that are based on the information in the files.

Methods:

![Alt text](URL " ")

The following methods were used to create the ChatGPT-like interface for PDF files:

The text was extracted from the PDF files using PyPDF2.
Embeddings were created for each chunk of text using OpenAIEmbeddings.
A semantic search engine was created using FAISS.
A ChatGPT instance was created using OpenAI.
The semantic search engine was used to find the most relevant chunks of text for each question.
The relevant chunks of text were passed to ChatGPT, which generated an answer.
Results:

The resulting system is a ChatGPT-like interface for PDF files. The user can ask questions about the contents of the PDF files, and the system will generate answers that are based on the information in the files.

For example, the user could ask the following questions:

Who are the authors of the article?
What was the cost of training the GPT4all model?
What was the size of the training dataset?
What is Google Bard?
The system would then generate answers to these questions based on the information in the PDF files.

Conclusion:

The ChatGPT-like interface for PDF files is a powerful tool for accessing information in PDF files. The system allows users to ask questions about the contents of PDF files in a natural way, and the system will generate answers that are based on the information in the files.
