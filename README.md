# Airline-Review-Analysis
This repository contains code and analysis for scraping airline reviews from the Skytrax website and generating insights based on customer feedback. The project focuses on understanding various aspects of airline services through sentiment analysis, ratings distribution, and other service-specific insights.

## Features
- **Web Scraping**: Extracts reviews from multiple pages of the Skytrax website.
- **Data Cleaning**: Processes and cleans the scraped data for analysis.
- **Sentiment Analysis**: Analyzes the sentiment of customer reviews to categorize them as positive, negative, or neutral.
- **Service-Specific Insights**: Correlates overall ratings with specific services like seat comfort, cabin staff service, and more.
- **Visualization**: Generates visualizations such as histograms, scatter plots, word clouds, and bar charts to present the findings.
- **Time-Based Trends**: Analyzes trends in customer ratings over time.

## Getting Started

### Prerequisites
- Python 3.x
- Required Python libraries: `requests`, `beautifulsoup4`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `textblob`, `wordcloud`

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Airline-Review-Analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Airline-Review-Analysis
    ```
3. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Web Scraping**:
   - Run the script `scrape_reviews.py` to scrape reviews from the Skytrax website.
   - The scraped data will be saved in the `data/airline_reviews.csv` file.

2. **Data Analysis**:
   - Run the script `analyze_reviews.py` to perform analysis on the scraped data.
   - The insights will be displayed as visualizations and printed summaries.

3. **PowerPoint Presentation**:
   - The insights generated from the analysis are also saved in a PowerPoint presentation `airline_review_insights.pptx`.

## Insights
- **Average Rating**: Provides the average rating given by customers.
- **Sentiment Distribution**: Categorizes reviews into positive, negative, and neutral sentiment.
- **Service Correlation**: Examines the relationship between overall ratings and specific services such as seat comfort and cabin staff service.
- **Recommendations**: Analyzes the percentage of customers who would recommend the airline.
- **Time-Based Trends**: Shows how customer ratings have changed over time.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Feel free to open issues or submit pull requests for any improvements or additional features you'd like to see.

## Contact
For any inquiries, you can reach out at `jrkesari@gmail.com`.
