# Wikipedia Topic Crawler and Link-Network Analyzer

## Problem Statement
To develop a web crawler that collects Wikipedia articles and analyzes their text content and hyperlink relationships using data mining techniques.

## Objectives
- Crawl Wikipedia articles using the MediaWiki API.
- Extract article text, titles, and hyperlinks.
- Perform data cleaning and exploratory data analysis.
- Identify frequent words using tokenization and stop-word removal.
- Analyze hyperlink relationships using a directed graph.
- Visualize results using interactive Plotly charts.

## Technologies Used
Python, Google Colab, Requests, Pandas, NetworkX, Plotly, Matplotlib.

## Algorithm
1. Initialize the crawler with the starting article, *Artificial intelligence*.
2. Retrieve article text and links through the MediaWiki API.
3. Traverse linked articles using Breadth-First Search (BFS).
4. Store the collected article and hyperlink data in dataframes.
5. Clean the data and calculate article word counts.
6. Tokenize text, remove stop words, and calculate word frequencies.
7. Construct a directed graph of links between crawled articles.
8. Calculate incoming and outgoing link counts.
9. Generate interactive visualizations and export the results.

## Implementation
The crawler collects up to 30 successful articles. Article metadata and hyperlink relationships are stored as CSV files. Text analysis identifies frequent terms, while NetworkX represents the hyperlink structure as a directed graph. Plotly generates interactive word-frequency and network visualizations.

## How to Run
1. Open `wikipedia_topic_crawler.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Allow the crawler to retrieve articles from the MediaWiki API.
4. Run the analysis and visualization cells.
5. Run the final export script to generate the output files.

## Results
- Articles collected: 30
- Unique internal hyperlink relationships: 90
- Most connected article by incoming links in the collected network: Artificial intelligence
- Outputs: article dataset, link datasets, network statistics, frequent-word analysis, and interactive HTML visualizations.

## Limitations
The results represent a sample of 30 crawled articles, not the entire Wikipedia network. Word frequencies and link counts depend on the selected starting article and the crawled sample.

## Author
- Name: Aayush Vinodkumar Ram
- Team member: Keshav Sharma
- Year / Class: TE-CE-D
- Roll Number: [Your Roll Number]
- Group: [Your Group]
