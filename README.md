# How I Built a Lightweight Search Engine Using Classic NLP

This notebook walks through the process of building a simple search engine using fundamental NLP techniques like TF-IDF vectorization and cosine similarity.

Along the way, I asked a fun question: "Who's the most famous podcaster in the world?"

The results? Wildly wrong -- and yet surprisingly revealing. This little failure ended up turning into one of the project's biggest insights -- a clear illustration of the strengths and weaknesses of a bag-of-words style search.

## The Roadmap
- Import and clean a large dataset of news articles
- Transform the text into numerical format using TF-IDF vectorization
- Use cosine similarity to measure relevance between a search query and articles
- Rank and retrieve the top matches, just like a search engine
- Scale the search engine code into a reusable Python function

## Tools & Libraries Used
- **Jupyter Notebook** — for writing and running Python code interactively
- **Python 3.12.2**
- **pandas** — for data loading and manipulation
- **nltk** - for text preprocessing, stemming, and lemmatization 
- **gensim** -- for tokenization suppot
- **scikit-learn** — for vectorization (CountVectorization, TfidfVectorization), cosine similarity, and modeling infrastructure 

## The Dataset

The full dataset (111MB) is stored locally and not included in this repo due to GitHub's file size limit. A sample
file ('fake_news_sample.csv') with the first 100 rows is included for reference and testing.

## Acknowledgements

I came up with the idea for this search engine while working on a similar project in my NLP course, taught by Michele Samorani, 
Associate Professor in the Department of Information Systems and Analytics at the Leavey School of Business at 
Santa Clara University. The dataset mentioned above also comes from that class.

## Note
This notebook is a work in progress. The only way to code is to practice. Stay tuned for more.
