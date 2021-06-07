# macapedia_recommender
Model of recommender system for Macapedia

## The dataset
We use the book dataset from [https://github.com/zygmuntz/goodbooks-10k](https://github.com/zygmuntz/goodbooks-10k). We scrape Goodreads best books from 2017-2020, adding about 1K books to the dataset. The notebook for doing data scraping and cleaning are in `dataset/recommender_data_cleaning.ipynb`.

## The model
We follow the guid from this [medium post](https://medium.com/recombee-blog/machine-learning-for-recommender-systems-part-1-algorithms-evaluation-and-cold-start-6f696683d0ed) written by Pavel Kordík. The recommender model use deep neural network. We worked on notebook `recommender_system.ipynb`.
