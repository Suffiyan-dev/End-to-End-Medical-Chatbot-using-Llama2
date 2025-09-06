#Steps to run the project
1-Create a enivorment
"conda create -n mchatbot python=3.8 -y"
2-Activate the enivorment
"conda activate mchatbot"
3-Pip install -r requirement.txt

# How to run?
#### STEPS:

Clone the repository
'''bash
Project repo: 
'''

### STEP 01-CREATE A CONDA ENIVORMENT AFTER OPEING THE REPOSITORY
'''bash
conda create -n mchatbot python = 3.8 -y
'''

'''bash
conda activate mchatbot
'''
### Step-02 Intall the requirements
'''bash
pip install -r requirement.txt
'''


### Create a .env file in the root directory and add your Pinecone credential as follows
'''import os
os.enivorn['PINECONE_API_KEY']='XXXXXXXXXXXXXXXXXXXXXXXXXX'
'''



### Downloade the quantize model from the link provided in model folder and keep the model in the model directory
'''init
## Download the Llama 2 model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## from the following link:
https://huggingface.co/TheBloke/Llama-2-7b-Chat-GGML/tree/main
'''

