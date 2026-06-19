AI-Powered Brochure Generator

📌 Overview
This project combines web scraping with Google Gemini AI to automatically extract relevant information from company websites and generate structured content (like brochures). It identifies important links (About, Careers, Docs, Blog, etc.), scrapes their contents, and organizes them into a readable format.

⚙️ Features
Environment setup using .env for secure API key management.

Gemini AI integration for content generation and link classification.

Web scraping with requests + BeautifulSoup.

Chrome version detection for dynamic User-Agent headers.

Link filtering to identify relevant company pages.

Brochure builder that compiles landing page + key links into a structured output.

Gradio UI support for interactive usage (optional).

🛠️ Installation
Clone the repository.

Install dependencies:

bash
pip install -r requirements.txt
Create a .env file and add your Gemini API key:

Code
GEMINI_API_KEY=your_api_key_here
🚀 Usage
Run the notebook or script to:

Scrape a target website.

Extract and classify relevant links.

Generate a structured brochure with AI assistance.

Example:

python
get_all_details("https://huggingface.co")
📂 Dependencies
requests, beautifulsoup4, re, json

dotenv for environment variables

google-genai for Gemini API

gradio for UI

🔮 Future Improvements
Add error handling for broken links.

Support multiple brochure formats (PDF, HTML).

Enhance link classification with fine-tuned AI prompts.
