Requirements:
- You need to run this with python or on Google Colab
- You need to install all of this package to use with these commands:
	!pip install langchain_community
    !pip install langchain_experimental
    !pip install langchain
    !pip install llama-cpp-python
    !pip install langchainhub
    !pip install sentence-transformers
    !pip install chromadb
    !pip install gradio
- You need to install one of the Llama2 model from this URL: 'https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGUF#provided-files'
- After finish install, you need to change the path in this line to your model file location "model_path = expanduser("D:/TDP/TDP/ChatBox/llama-2-7b-chat.Q4_0.gguf")"
- And, you need to change the path in this line to your .csv file location "loader = CSVLoader(file_path='D:/TDP/TDP/ChatBox/data.csv', encoding='utf-8')"
- Then you need to run all the commands. 
- After running all command, at the end of the file there will be a line: "Running on public URL:" and there will be a URL. You click on that URL and go to demo