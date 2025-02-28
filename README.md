# AI-powered Web Scraper

A web application that transforms any website's content into structured, tabular data using AI-powered scraping and natural language processing.

## main features

- **Scraping**: simply input any URL and describe your goal
- **Natural Language Processing**: Uses OpenAI's GPT-4 to understand and extract relevant data
- **Data Organization**: Automatically structures scraped data into clean, tabular format
- **Export Functionality**: Export results to CSV
  
## how do i use it?

**This is the starting screen.**
<img src="https://github.com/user-attachments/assets/6ca94607-a2aa-4314-98fc-9e08f8c8769d" width="1920" height="1080">

**Paste the desired URL, and hit "Scrape it"**
(Optionally, if you want to provide extra details, you can interact with your data through the text box.)

<img src="https://github.com/user-attachments/assets/8c2baf5d-0375-47ff-92e7-1a978634032d" width="300" height="250">

Hit the "Export" button to download the data into a CSV file.


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

## what is it good for?

- Market Research
- Data Collection
- Competitive Analysis
- Content Aggregation
- Price Monitoring
