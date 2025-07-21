# Final Project: Article Summarizer

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the `.pkl` or `.txt`file of your scraped html (this is specified in the notebook)

## Rubric

### Tasks Checklist

- ✅ **(Question 1)** Article HTML stored in a separate file that is committed and pushed: 1 pt  
- ✅ **(Question 2)** Polarity score printed with an appropriate label: 1 pt  
- ✅ **(Question 2)** Number of sentences printed: 1 pt  
- ✅ **(Question 3)** Correct (or equivalent in the case of multiple tokens with the same frequency) tokens printed: 1 pt  
- ✅ **(Question 4)** Correct (or equivalent in the case of multiple lemmas with the same frequency) lemmas printed: 1 pt  
- ✅ **(Question 5)** Histogram shown with appropriate labeling: 1 pt  
- ✅ **(Question 6)** Histogram shown with appropriate labeling: 1 pt  
- ✅ **(Question 7)** Cutoff score seems appropriate given histograms: 2 pts (1 pt/score)  
- ✅ **(Question 8)** Summary contains a shortened version of the article (less than half the number of sentences): 1 pt  
- ✅ **(Question 8)** Summary sentences are in the same order as they appeared in the original article: 1 pt  
- ✅ **(Question 9)** Polarity score printed with an appropriate label: 1 pt  
- ✅ **(Question 9)** Number of sentences printed: 1 pt  
- ✅ **(Question 10)** Summary contains a shortened version of the article (less than half the number of sentences): 1 pt  
- ✅ **(Question 10)** Summary sentences are in the same order as they appeared in the original article: 1 pt  
- ✅ **(Question 11)** Polarity score printed with an appropriate label: 1 pt  
- ✅ **(Question 11)** Number of sentences printed: 1 pt  
- ✅ **(Question 12)** Thoughtful answer based on reported polarity scores: 1 pt  
- ✅ **(Question 13)** Thoughtful answer based on summaries: 1 pt  

---

## Project Overview

In this project, we perform sentiment analysis on an article to extract a concise summary. The main tasks include:
1. Cleaning and preparing the data.
2. Calculating sentiment scores using tokens and lemmas.
3. Filtering and selecting relevant sentences for the summary.
4. Evaluating the sentiment and structural aspects of the summary.

## File Details

- **article.html**: The raw HTML file containing the article content.
- **article-summarizer.ipynb**: The final summarized version of the article.
- **requirements.txt**: A list of the Python packages required for the project.

 ---
## How to Run

1. **Clone this repository**:
 ```bash
   git clone https://github.com/Elen-tesfai/article-summarizer.git
   cd article-summarizer
 ```  
2. Ensure Python 3.x is installed on your system.
 ```bash
python --version
 ```
3. Install required packages, e.g.:  
 ```bash
   pip install spacy spacytextblob beautifulsoup4 matplotlib
   python -m spacy download en_core_web_sm
 ``` 
4. Open `article-summarizer.ipynb` in Jupyter Notebook or VS Code and run all cells.

## Dependencies

- **spaCy** – for NLP processing  
- **spaCyTextBlob** – for sentiment analysis integration with spaCy  
- **BeautifulSoup** – for parsing HTML  
- **Matplotlib** – for visualization  

**Author:** Elen Tesfai  
GitHub Repository: [https://github.com/Elen-tesfai/article-summarizer](https://github.com/Elen-tesfai/article-summarizer)