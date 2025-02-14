# Portfolio Content Summariser
This Python script fetches the contents of a given website, extracts relevant text, and generates a short markdown-formatted summary using OpenAI's GPT-4o-mini.  

## Features  
- Uses `requests` and `BeautifulSoup` to scrape and clean website content  
- Removes irrelevant elements like scripts, styles, and images  
- Sends extracted text to OpenAI's API for summarization  
- Outputs a concise website summary in markdown format  

## Requirements  
- Python 3.x  
- `requests`, `beautifulsoup4`, `openai` libraries  
- OpenAI API key (set as `OPENAI_API_KEY` in environment variables)  

## Usage  
Replace https://joshjharris.com with any URL to summarize its content.

Run the script with:  
```python  
python script.py
