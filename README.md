 AI RSS News Summarizer using n8n
 An automated n8n workflow that collects AI and technology news from RSS feeds, merges the data, and generates concise summaries using Google Gemini.
 Features
* Fetches AI news from RSS feeds
* Fetches broader technology updates
* Merges and aggregates news articles
* Uses Google Gemini for AI-powered summarization
* Scheduled daily execution
* Clean categorized output format
 Workflow Overview
  1. Schedule Trigger runs daily
  2. RSS feeds are fetched:
   * AI Business
   * TechCrunch
  3. Articles are merged and aggregated
  4. Google Gemini summarizes the content
  5. Final output is structured into:
   * AI News
   * Technology Updates
RSS Sources
 https://aibusiness.com/rss.xml
 https://techcrunch.com/feed/
 Requirements
 n8n
 Google Gemini API Key
 Technologies Used
* n8n
* Google Gemini
* RSS Feed Nodes

 Example Use Cases
* Daily AI news digest
* Automated tech newsletter
* Internal company updates
* Personal news automation
