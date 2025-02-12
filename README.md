# AI-powered Web Scraper

A web application that transforms any website's content into structured, tabular data using AI-powered scraping and natural language processing.

## main features

- **Scraping**: simply input any URL and describe your goal
- **Natural Language Processing**: Uses OpenAI's GPT-4 to understand and extract relevant data
- **Data Organization**: Automatically structures scraped data into clean, tabular format
- **Export Functionality**: Export results to CSV
  
## how do i use it?

1. **Input URL**: Enter any website URL you want to scrape
2. **Define Goal**: Describe what data you want to extract in plain English
3. **Process**: The application will:
   - Fetch the webpage content
   - Compress and optimize the HTML
   - Use AI to identify relevant sections
   - Generate custom scraping code
   - Extract and structure the data
4. **View Results**: Data is presented in a clean, paginated table
5. **Export**: Download results as CSV

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
