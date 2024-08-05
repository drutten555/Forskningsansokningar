# Project Forskningsansökningar

This notebook does the same tasks, but uses the Llama3.1 LLM model instead.

## Run Llama using Ollama
To run using llama3.1 do the following:
1. Download ollama at: https://ollama.com/
2. Run on of the following commands in venv terminal. This should install the Llama3 model to the venv. The model can be changed to something else.
    ```
    ollama run llama3.1  # pulls and runs the LLM 
    ```
    
    or

    ```
    ollama pull llama3.1  # only pulls the LLM
    ```
3. When done then you are ready to run the scripts! If you used the `ollama run` command then exit the running model by writing `\bye` or `\exit`.