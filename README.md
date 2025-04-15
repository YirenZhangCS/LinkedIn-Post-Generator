# LinkedIn Post Generator  

An AI-powered LinkedIn post generator built with GenAI (LLaMA 3), LangChain, and Streamlit. 


## Technologies Used


| Category             | Library / Tool            | Purpose                                                                 |
|----------------------|---------------------------|-------------------------------------------------------------------------|
| **Frontend / UI**     | `streamlit`               | Build the interactive web interface for the generator                 |
| **LLM Framework**     | `langchain_core`, `langchain_groq` | Orchestrate prompts and LLaMA 3 API integration (via Groq)            |
| **Prompt Engineering**| `PromptTemplate`, `JsonOutputParser` | Create structured prompts and parses LLM responses                    |
| **LLM Model**         | `ChatGroq` (LLaMA 3)      | Perform actual post generation using the Groq-hosted LLaMA model      |
| **Machine Learning**  | `scikit-learn`            | Provide RandomForestRegressor for predicting post engagement          |
| **Model Storage**     | `joblib`                  | Save and load the trained ML model                                   |
| **NLP / Text Analysis**| `TextBlob`               | Compute sentiment score of post content                               |
| **Data Handling**     | `pandas`, `json`          | Used to preprocess and manipulate structured post data                 |
