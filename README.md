Here’s a concise README file for your project:

---

# BookLens - Book Reviews Analysis PoC

This repository contains a Proof of Concept (PoC) designed to automate the analysis of book reviews for Hachette UK using NLP and Large Language Models (LLMs). The PoC focuses on three key functionalities: sentiment analysis of reviews, positioning of the publisher across book categories, and generation of author performance reports.

## Project Structure

### Notebooks

1. **01_explore_books.ipynb**
   - Initial exploration of the book metadata.
   - Provides insights into the available data fields and their distributions.

2. **01_explore_ratings.ipynb**
   - Exploration of ratings and reviews data.
   - Identifies patterns and trends in reader feedback.

3. **02_join_dfs.ipynb**
   - Merges different datasets (books and reviews) to create a unified dataset for analysis.

4. **03_vectorize_category.ipynb**
   - Vectorizes the book descriptions to identify positioning across different literary categories.
   - This notebook supports the analysis of the publisher's strength in various genres.

5. **04_plot_category.ipynb**
   - Visualizes the distribution of books across categories.
   - Helps in understanding the publisher's market positioning.

6. **05_analyze_author_perfomance.ipynb**
   - Analyzes the performance of individual authors based on reviews and ratings.
   - Generates key metrics to evaluate author success.

7. **06_category_performance.ipynb**
   - Evaluates the publisher’s performance across different book categories.
   - Compares performance with other publishers where applicable.

8. **07_sentiment-roberta-review.ipynb**
   - Applies the RoBERTa model to perform sentiment analysis on book reviews.
   - Classifies reviews as positive, negative, or neutral to gauge reader sentiment.

9. **08_model-evaluation.ipynb**
   - Evaluates the effectiveness of the sentiment analysis model.
   - Provides metrics and insights to ensure model reliability.

### Data

- All input data used in these analyses is stored in the `Input` directory.
- This includes book metadata, ratings, reviews, and any other relevant datasets.

## Getting Started

To run this project locally, clone the repository and ensure you have the necessary Python packages installed. You can install the required packages by running:

```bash
pip install -r requirements.txt
```

After installation, you can execute the notebooks in sequence to reproduce the analyses.

## Key Functionalities

1. **Sentiment Analysis**
   - Conduct sentiment analysis on book reviews using the RoBERTa model (`07_sentiment-roberta-review.ipynb`).

2. **Publisher Positioning**
   - Analyze and visualize the publisher's positioning across different book categories using vectorization (`03_vectorize_category.ipynb`).

3. **Author Performance Reports**
   - Generate detailed reports on author performance to support editorial decisions (`05_analyze_author_perfomance.ipynb`).

## Next Steps

- Extend this PoC by integrating these analyses into an automated pipeline.
- Monitor and refine the models based on feedback and evolving data.

## License

This project is licensed under the MIT License.

## Contact

For any questions or further information, please contact Mateus Exel.

---

This README provides an overview of the project, guiding the user through the structure and purpose of each notebook while highlighting the key functionalities.