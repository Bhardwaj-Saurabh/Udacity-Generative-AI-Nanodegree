# Personalized Real Estate Agent
The Personalized Real Estate Agent project leverages GEN AI techniques to recommend homes tailored to user preferences. It interacts with users through a conversational interface, gathering insights on their preferences through a series of questions. Utilizing a large language model (LLM), it processes user responses to recommend homes that best match their desires and explains why these homes are ideally suited for them.

# Features
**Interactive Q&A:** Dynamically generates personal questions to understand user preferences.

**Semantic Analysis:** Uses LLMs to interpret the semantic meaning behind user responses.

**Tailored Recommendations:** Provides personalized home recommendations based on user preferences.

**Explanatory Feedback:** Offers explanations for why certain homes are recommended, enhancing user trust and understanding.

# Prerequisites
Before running the project, ensure you have the following prerequisites installed and set up:

- **Python 3.8:** Ensure Python is installed on your system.
- **Jupyter Notebook or JupyterLab:** For interacting with the .ipynb notebook.
- **LangChain:** LLM based development libraries.
- **ChromaDB:** Vector Database
- **OpenAI API Key:** Required for accessing the GPT-3.5-turbo model and embeddings.

# Dependencies
The project depends on several Python libraries. Install them using pip:

```
pip install -U langchain-openai
pip install openai==0.28
pip install chromadb
pip install tiktoken
```

# How to Run

## Clone the Repository
```
git clone https://github.com/Bhardwaj-Saurabh/Udacity-Generative-AI-Nanodegree.git
```

## Install Dependencies
Navigate to the cloned directory and install the required Python libraries:
```
cd Personalized_Real_Estate_Agent
pip install -r requirements.txt
```

## Set Up OpenAI API Key
Export your OpenAI API key as an environment variable:
```
export OPENAI_API_KEY='your_api_key_here'
```

Start Jupyter Notebook or JupyterLab:
```
jupyter notebook
```

In the Jupyter interface, navigate to the Personalized_Real_Estate_Agent.ipynb notebook and open it.

## Run the Notebook

Execute the cells in the notebook sequentially, following any additional instructions provided within.

## Contributing
We welcome contributions! Please open an issue for any bugs or feature requests, or submit a pull request with improvements.