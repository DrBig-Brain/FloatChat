
# Topics

- Our Idea
- Our Solution
- Technical Approach



## Our Idea :
- scraping Argo data for temperature, salinity, Pressure and Buoy parameters (metadata / condition).
- establishing a data warehouse for the given observation
- LLM (gemini/gpt) based Rag to retrieve data from data warehouse using Natural Language Commands.
- creating Chatbot like interface with Map and Graphical interpretation.

### Problem :

- Argo float data or any other data related to ocean Is very huge and searching for any particular is very tough and time takin g,
also requires someone experience,hence ,many cant extract data from it

the need for technical expertise,


More into it:

And visualizing the  graphs 
 visualizing oceanographic information using *natural language*.


## Our Solution :   


# A Chatbot 
Like chat gpt or Claude or gemini, A conversational interface to be able to talk to the Data of ARGO and ask related queries 
Without being an Expert of the Domain.

A sleek Ui for the comfortable Questionb answering : Visualization of The of Graphs and Data In Expert Way , In way less time than ever required



* Natural-language chat interface that understands oceanographic intent.

* RAG backend that retrieves relevant ARGO metadata/profiles and generates queryable results.

* Interactive visualizations

* Quick export: ASCII, CSV, NetCDF for selected profiles.

* Query suggestions & guided prompts for novice users (e.g., “Show salinity near equator, Mar 2023”).

* Lightweight, fast UI with dark/light themes and live preview panels.



## Technical Approach

# Backend :


 - Data Ingestion
     - Parse argo
     - convert into structured formats
- Vector Database
    - Store embeddings into faiss/chroma
- RAG Pipeling:
    -  using llms : GPT /GEmini
    -  Retrieve Results


### Stack :  
- Langchain 
- Langgraph
- FASTAPI
- GEmini/GPT


## Front end :   

# Chatbot

### Stack

- React : Frontend
- BACKEND : To be decised later
- Langchain- Langgraph- For RAG
- LLM : GEMINI / GPT

### Future Prospect
- use of LLM instead of current APIs, 
- use of Agentic ai for database update
- use of Agentic ai to automate email for customer services
