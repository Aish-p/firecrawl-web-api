# WebScraperAPI 🔥 – Extract smarter, faster, and better! 

WebScraperAPI is a powerful web scraping interface that transforms any website into structured, queryable data using natural language. Built with Streamlit and powered by Firecrawl, this tool enables users to extract specific information from websites without writing complex scraping code. Perfect for developers, researchers, and data analysts who need to quickly convert web content into structured JSON or CSV formats.


## Features

- 🌐 Extract data from any website URL
- 📊 Custom schema builder for structured data extraction
- 💬 Natural language interface for data queries
- ⬇️ Export data in JSON and CSV formats
- 🔄 Real-time data streaming
- 🎯 Support for multiple data types (string, boolean, integer, float)
- 🚫 No coding required for end users


## ⚡ Quick Start

1️⃣ Clone the Repository
  ```
  git clone https://github.com/Aish-p/WebScraperAPI.git
  cd WebScraperAPI
  ```

2️⃣ Install Dependencies
  ```
  pip install -r requirements.txt
  ```

3️⃣ Set Up Environment Variables
  Create a .env file and add your Firecrawl API key:
  ```
  FIRECRAWL_API_KEY=your-api-key-here
  ```

4️⃣ Run the App
  ```
  streamlit run app.py
  ```


## 🛠 How It Works

1. Enter a website URL in the sidebar.

2. (Optional) Configure the schema builder:
   * Add fields by clicking "Add Field ➕"
   * Specify field names and types
   * Remove fields using the ❌ button

3. Ask questions about the website in the chat interface

4. Download the extracted data in JSON or CSV format


## 🔗 Technologies Used

**Firecrawl** – AI-powered web data extraction

**Streamlit** – Interactive Python apps

**Pandas** – Data processing

**Pydantic** – Schema validation

**Dotenv** – Environment variable management


## 📌 Demo

<div align="center">
  <p><strong>The main application interface with sidebar configuration</strong></p>
  <img src="/screenshots/main_interface.PNG" alt="Main Interface" width="700">
</div>
<br>

<div align="center">
  <p><strong>Extracting product details from an e-commerce website</strong></p>
  <img src="/screenshots/product_query1.PNG" alt="Product Query" width="700">
  <br>
  <br>
  <img src="/screenshots/product_query2.PNG" alt="Product Query" width="700">
</div>
<br>


## 🙌 Acknowledgments

- Built with [Streamlit](https://streamlit.io/)
- Powered by [Firecrawl API](https://firecrawl.com/)
