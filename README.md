# Clothing Buyer Feedback Analysis with LLMs

[![OpenAI](https://img.shields.io/badge/Powered%20by-OpenAI-blue)](https://openai.com)
[![ChromaDB](https://img.shields.io/badge/Powered%20by-ChromaDB-orange)](https://www.trychroma.com)

This data portfolio project showcases the application of Large Language Models (LLMs) and embedding techniques for analyzing buyer feedback on clothing purchases. The goal is to demonstrate how LLMs can be effectively used for tasks like product recommendation, sentiment analysis, and topic classification.

This project is part of DataCamp's [Developing AI Application](https://app.datacamp.com/learn/skill-tracks/developing-ai-applications) skill track.


## Key Features

- **Data Processing:** Cleaning and preparation of buyer feedback data.
- **Embedding Generation:** Utilizes OpenAI's API to create meaningful embeddings of feedback text.
- **ChromaDB Integration:** Stores and manages embeddings for efficient similarity search.
- **Recommendation Engine:** Suggests similar products based on user preferences and feedback.
- **Sentiment Analysis:** Classifies feedback as positive, negative, or neutral.
- **Topic Modeling:** Identifies key themes and trends within buyer feedback.

## Technologies Used

- **OpenAI:** Leveraged for its powerful LLM capabilities and embedding generation.
- **ChromaDB:**  Chosen for its robust vector database features and ease of integration.
- **Python:** The primary programming language used for data analysis and model building.
- **Other Libraries:** Pandas, NumPy, Scikit-learn (optional)

## Project Structure

data/ \
├── raw_feedback.csv

notebooks/ \
├── data_preparation.ipynb \
├── embedding_generation.ipynb \
├── chromadb_integration.ipynb \
├── recommendation_engine.ipynb \
├── sentiment_analysis.ipynb \
├── topic_modeling.


## How to Run

1. **Clone the Repository:** `git clone https://github.com/yourusername/clothing-feedback-analysis.git`
2. **Install Dependencies:**  `pip install -r requirements.txt`
3. **Obtain API Keys:** Get your OpenAI API key.
4. **Set Environment Variables:** Configure environment variables for API keys.
5. **Execute Notebooks:** Follow the sequence of Jupyter Notebooks in the `notebooks` folder.

## Project Goals

- To showcase proficiency in utilizing LLMs for real-world data analysis tasks.
- To demonstrate the potential of embedding techniques for recommendation and classification.
- To provide a clear and well-documented project for prospective employers to evaluate.

## Additional Notes

- This project is primarily a demonstration of technical skills.  Expanding the dataset or refining the models would be natural next steps in a production environment.
- Feel free to adapt and modify this project to fit your own data and use cases.

## License
[Choose a license (e.g., MIT, Apache 2.0)]