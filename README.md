# Financial News Sentiment Analysis

This Python script leverages web scraping techniques using BeautifulSoup and performs sentiment analysis on financial news headlines sourced from Finviz for selected stock tickers—AMZN, TSLA, and GOOG. The sentiment analysis is conducted utilizing the NLTK VADER (Valence Aware Dictionary and Sentiment Reasoner) tool.

## Overview

The script is designed to provide insights into the sentiment surrounding specific stocks by gathering recent news headlines from the Finviz website and analyzing their sentiment. The sentiment analysis is based on the polarity scores derived from NLTK VADER, which categorizes text sentiment into positive, negative, neutral, and compound values.

## Usage

### Prerequisites

- Python 3.x
- Required libraries are included in the script. Install any missing libraries using:
    ```bash
    pip install pandas matplotlib nltk
    ```

### Execution

1. Open the Python script in your preferred editor.
2. Run the script to collect financial news headlines from Finviz for the stocks—AMZN, TSLA, and GOOG.
3. Perform sentiment analysis and visualize the average sentiment scores over time for the selected stocks.
4. The generated bar charts illustrate the sentiment trends for the specified stocks.

### Code Breakdown

- **Web Scraping:** Utilizes BeautifulSoup to extract news headlines from Finviz for the selected stock tickers.
- **Sentiment Analysis:** Employs NLTK VADER for sentiment analysis to derive polarity scores for the collected headlines.
- **Data Visualization:** Utilizes Pandas and Matplotlib to generate bar charts visualizing the average sentiment scores over time for the chosen stocks.

## Results

The code generates sentiment scores and visual representations, providing an overview of sentiment trends for the selected stocks based on the collected financial news headlines.

## Additional Notes

- Adjusting the tickers or modifying the code to incorporate additional stocks is feasible by modifying the `tickers` list in the script.
- The code can be enhanced for more sophisticated sentiment analysis or integrated into larger financial analysis projects.

Feel free to use, modify, or extend this code for further analysis or adapt it according to your specific requirements.

For more detailed insights and instructions, refer to the script itself or reach out for additional assistance or inquiries.

Happy analyzing! 📊✨
