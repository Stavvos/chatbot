# Chatbot:

This chatbot is able to answer questions relating to a custom knowledge base.

## Installation:

To run this program you'll have python installed on your machine.

##
        pip install langchain_community langchain_text_splitters langchain_openai langchain_chroma gradio python-dotenv pypdf

## Running the program:

1. Delete the README.txt file in /data.
2. Put some .pdf files into /data.
3. Run createDatabase.py.
4. Get an open ai api key.
5. Open the .env file and put your open ai api key inside the quotation marks OPENAI_API_KEY = 'YOUR API KEY GOES HERE'
6. save and exit .env file
7. Run chatbot.py.
8. The chatbot will return a link in the command line interface. 
9. Open the link with a brower.

