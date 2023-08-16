open chatbotV2yo.py 
#create a virtual environment :
new terminal in vs code , choose cmd 
then write 
1) python -m venv myenv
2) cd myenv
3) cd Scripts
4) activate

    now you're in the virtual environment you sould download the requirements
   using either
   1) adding the requirement.txt to the folder
      then in terminal in vscode :
      1)pip install -r requirement.txt
   if it's not working you sould download every package seperatly
       1) pip install langchain
       2) pip install InstructorEmbedding
       3)  pip install sentence_transformers
       4)  pip install faiss_cpu
       5)  pip install accelerate
       6)  pip install torch
       7)  pip install streamlit
       8)  pip install streamlit_chat
       9)  pip install transformers
       10)  pip install bitsandbytes
       11)  pip install pypdf
     
  #now you should download the llm fiel (.bin) from huggingFace using this link https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main 
  you choose from Files and versions (llama-2-7b-chat.ggmlv3.q4_0.bin) size: 3.79gb 
  then you add the .bin file to  the same folder you're working on 
  #you add the spring-boot documentation.pdf from the github repository and you adjust the path in line 19 

  #in terminal vscode (cmd) you write this line 
        1)streamlit run chatbotV2yo.py 
  it will give you a link localhost....... 

  
  if every requirement is downloaded , it will work hopefully 
