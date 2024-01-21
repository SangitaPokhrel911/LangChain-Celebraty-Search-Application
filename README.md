# LangChain-Celebraty-Search-Application

This is the basic application where you can type the name of the celebraties and using the Open AI API, it gives you the description of that person. I have also applied Memory Buffer to store the information of 2 interactions 'DOB Memory' and 'Description Memory'. Simple user interface by streamlit framework.

The main.py contains the simple code just to pass the Open AI API key and put the title using streamlit, ask the input_text variable the topic you want to know and pass the llm over it. You can search anything that you want. #basic idea for you to understand how we can use the API

The example.py file contains the 'Celebraty Search Results', I have used three customized prompt templates where once you type the name of celebray, it gives the description of that person, date of birth and the 5 major events happened around that date of birth year in the world. Used the Sequential Chain library from langchain to combine the customized multiple chains. 

Please make sure that the API key  has to be keep in the constant.py which you can generate from the Open AI by creating account, so that we can use the openai_key variable in the main.py and example.py. 

In the requirements.txt, you can see the main libraries that we need to install in our environment. 

Thanks 
