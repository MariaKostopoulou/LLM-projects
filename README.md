# Wildfires in Australia - Data Extraction Project

This project is all about scraping wildfire data from Wikipedia, focusing on the 2018–19 Australian bushfire season. We're transforming unstructured data into something easy to analyze, like total burnt land, number of fires, deaths, and affected areas.

## What Does This Project Do?

- **Web Scraping**: Grabs wildfire data from Wikipedia using Python.
- **Data Cleaning**: Cleans up descriptions by removing citation references.
- **Structured Extraction**: Uses a model to pull out the important details like fire names, dates, and more.
- **Final Output**: Saves everything neatly into a CSV file.

## How It Works

1. **Fetch Data**: Scrape wildfire descriptions from Wikipedia.
2. **Process**: Extract the key features—burnt land, number of fires, etc.
3. **Clean & Save**: Clean the data and save it to a CSV for easy use.

## Output

You’ll get a CSV file with:
- Wildfire name
- Dates (start and end)
- Number of deaths
- Total burnt land (hectares)
- Areas affected

Most of the extraction works well, but for complex cases, some extra analysis might be needed.

## Requirements

Make sure you have these libraries installed:
- `requests`
- `BeautifulSoup`
- `pandas`
- `pydantic`
- `openai`
