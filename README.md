# Amazon Price Competitor Analysis 🔎  

A dashboard & CLI tool that lets you input an Amazon ASIN, scrapes the product → finds competitor listings → scrapes them → and uses an LLM to generate actionable insights.  

## 🚀 What It Does  

- Scrapes product data from Amazon via Oxyabs (price, features, images, etc.).  
- Finds “competing” Amazon listings automatically.  
- Scrapes competitor data in the same way.  
- Uses LangChain + LLM to generate position summaries, pricing/feature suggestions, and strategic analysis.  
- Presents results via Streamlit dashboard (and/or command-line flow, depending on implementation).  

## ⚙️ Quick Start  

```bash
git clone https://github.com/HarshithaShetty27/Amazon-Price-Competitor-Analysis.git  
cd Amazon-Price-Competitor-Analysis  
pip install -r requirements.txt  

# Create .env file in root:
echo "OXYABS_API_KEY=YOUR_OXYABS_KEY" >> .env  
echo "OPENAI_API_KEY=YOUR_OPENAI_KEY" >> .env  

streamlit run main.py    # or `python main.py` depending on your entry
````

Open `http://localhost:8501` in your browser → enter an ASIN → “Scrape” → “Analyze” → get results.

## 🧪 Example Use Case

> I grabbed an ASIN for a protein powder → dashboard showed competitor prices, feature gaps, and AI-generated suggestions:
>
> * “Your product is priced slightly above average → consider adding value via feature X.”
> * “Competitors rank on page 1 with more reviews → propose automated review solicitation.”

## 💡 Why This Tool Matters

If you’re launching or optimizing a product on Amazon, competitive intelligence matters. This tool gives fast insight into how you stack up — enabling smarter pricing / feature / positioning decisions.

## ⚠️ Legal & Ethical Note

This tool is for **educational / research / personal use**. Make sure you respect Amazon’s Terms of Service, robots.txt, and all applicable laws before scraping data at scale.


