#Pretrained Model Comparison Using TOPSIS: Project Overview

##Introduction:
Text summarization, a critical natural language processing task, involves condensing extensive documents into concise, informative summaries. This project aims to guide users in selecting the most suitable text summarization model by comparing the performance of various pretrained models.

##Key Features:

Metrics Considered:
The model comparison is based on essential metrics, including Rouge scores, BLEU score, F1 scores, and a unique focus on perplexity (pplx). Perplexity is a measure of language model quality, with lower values indicating better performance.

Methodology - TOPSIS:
The Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method is employed for the comparison. This method considers both the similarity to the ideal solution and the dissimilarity to the negative ideal solution, providing a comprehensive ranking.

Models Evaluated:
The comparison includes well-known pretrained models: Bert, T5, Perplexity (pplx), PPLM (Perplexity for Language Modeling), and PPLC (Perplexity for Content).

##Project Structure:

- **'data.csv'**: CSV file containing evaluation metrics for each model.
- **'result.csv'**: CSV file with ranked results in tabular format.
##Results and Analysis:

1. **Ranked Table:**
Explore detailed ranked results in summarization_table_result.csv:


| **Model**   | **Rouge Scores**  | **BLEU scores      ** | **F1 scores    ** |
|-------------|-------------------|-----------------------|-------------------|
| RoBERTa     | 0.80              | 0.75                  | 0.82              |
| ELECTRA     | 0.82              | 0.78                  | 0.84              |
| DistilBERT  | 0.78              | 0.72                  | 0.79              |
| ALBERT      | 0.83              | 0.76                  | 0.85              |
| GPT-2       | 0.79              | 0.73                  | 0.80              |
| CTRL        | 0.76              | 0.71                  | 0.78              |

**Model Performance:**

Bert and T5 demonstrate competitive performance based on Rouge scores and BLEU.
Perplexity (pplx) emerges as the best model, showcasing superior language modeling quality.
Next Steps:

Further investigate the language modeling capabilities of the Perplexity (pplx) model.
Consider adjusting the focus on specific metrics based on use case requirements.
Utilize the insights gained from this project as a foundation for ongoing research and development in text summarization.
