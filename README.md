# AI-powered Web Scraper

A web application that transforms any website's content into structured, tabular data using AI-powered scraping and natural language processing.

## main features

- **Scraping**: simply input any URL and describe your goal
- **Natural Language Processing**: Uses OpenAI's GPT-4 to understand and extract relevant data
- **Data Organization**: Automatically structures scraped data into clean, tabular format
- **Export Functionality**: Export results to CSV
  
## how to use it:

**This is the starting screen.**
![Screenshot 2025-01-30 at 11 03 43](https://github.com/user-attachments/assets/6ca94607-a2aa-4314-98fc-9e08f8c8769d)

**Paste the desired URL, and hit "Scrape it"**
(Optionally, if you want to provide extra details, you can interact with your data through the text box.)

![Screenshot 2025-02-28 at 14 34 29](https://github.com/user-attachments/assets/8c2baf5d-0375-47ff-92e7-1a978634032d)

If everything is to your liking, simply hit the "Export" button to download the data into a CSV file.

**Important Note**

As we can see in the video below, the model accurately extracts real data from the provided URL and does not fabricate fake information.
![nohalgif](https://github.com/user-attachments/assets/791aa761-ef19-4e8e-96a6-7a188898df83)


**Process**: The application will:
  - Fetch the webpage content
  - Compress and optimize the HTML
  - Use AI to identify relevant sections
  - Generate custom scraping code
  - Extract and structure the data
    
**View Results**: Data is presented in a clean, paginated table

## stack

- **Frontend**: Nuxt.js with Vue 3
- **Styling**: SCSS with custom design system
- **AI Integration**: LangChain with OpenAI
- **Scraping Engine**: Cheerio & Puppeteer
- **Vector Storage**: LangChain Memory Vector Store
- **Text Processing**: LangChain Text Splitter

## What can you use this for

- Market Research
- Data Collection
- Competitive Analysis
- Content Aggregation
- Price Monitoring
