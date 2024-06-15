# AIBot_finetune5_HPv5DGPTw9.ipynb:  
Finetuning the Dialog Dataset using DialoGPT-Medium. Dataset is a CSV file that has three columns namely: "Chapter, User_Bot and Dialog". However, the two columns<b> User_Bot	and Dialog</b> are used to form the Formated Dialog which are used to finetune the DialoGPT-medium model.

# llama2_finetune_w9_with_logs.ipynb:
Finetuning the Dialog Dataset using Llama-7B. Dataset is a CSV file that has three columns namely: "instruction, input and output". The three columns are used to form the Formated Dialog which are used to finetune the LLAMA2-7B model.

# Mistral-7B_finetune_w11.ipynb:
Finetuning the Dialog Dataset using Mistral-7B. Dataset is a CSV file that has two columns namely: "chat_sample	and dataset_origin". However, the "chat_sample"	column contains the required Instruction, Query and its relevant Response in a specific predefined Format which are used to finetune the Mistral-7B model.
