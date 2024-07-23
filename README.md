# Meta-llama3 and Llama3.1
## Adapter for single-GPU
Llama3 and Llama3.1 models definition comes configured for multi-GPU. Although you should be able to set the configuration to run it in a single GPU with no code changes, this version simplifies the model's definition to adapt it to a single-GPU environment.

### Generation for Llama3
The original generation.py has been re-formatted as a Jupyter notebook for educational purposes.  In this version, only the text-completion is implemented (the chat completion was deleted).  You can run cell by cell the notbook to understand the different pieces that constitute the generation of new text. 

This code inherits the original license of Meta-llama3 and Llama3.1
