# About preface

### 5 techniques of prompting:
* Zero-shot prompting
  * Just ask the question
* Chain of thought
  * Ask the question. Ask to think step by step
  * You can also write yourself the steps That helped in the boardgames chatbot.
* RAG
  * Include context in the prompt. 
* Tool calling
  * Adds to prompt a list of external functions and a description of what each does. 
  * Adds instructions on how to signal in the output that it wants to use one or some of these functions to better answer the question
  * The developer should parse the output and call the appropriate functions, and then returns the output of the functions to the model so it can provide the final answer to the user
* Few-shot prompting
  * Include in the prompt examples of other questions with the correct answers.
For best results, combine chain of thought, rag and tool calling, and even few-shot

### RAG terms:
Vector store: databases dedicated to storing embeddings
Vector indexes: regular databases with vector-storing capabilities
