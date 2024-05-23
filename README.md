# MLproject_RecommenderSystem

This repository contains the code and a dataset example for a news recommendation system leveraging both DKN (Deep Knowledge-Aware Network) and NPA (Neural News Recommendation with Personalized Attention) models. The project aims to enhance user engagement by delivering personalized news recommendations.

## Setup

1. **Install Dependencies**:
   Install the required packages using the command:
   
   ```bash
   pip install recommenders
   ```

3. **Download and Prepare Data**:
   The MIND dataset is utilized for training and evaluation. Use the provided scripts to download and preprocess the data.

4. **Model Implementation**:
   - **DKN**: Integrates knowledge graph embeddings with a knowledge-aware CNN to enrich news representations.
   - **NPA**: Utilizes CNNs and personalized attention mechanisms to transform news titles and user interaction data into informative embeddings.

5. **Future Improvements**:
   - **Two-Tower Model**: Implementing a Two-Tower model to process user and item data simultaneously for better embedding and recommendation precision.

6. **Evaluation Metrics**:
   The system's performance is evaluated using AUC, MRR, and nDCG metrics.

