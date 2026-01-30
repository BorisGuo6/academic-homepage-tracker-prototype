# Academic Homepage Tracker  

## Goals  
- Help academics monitor their personal homepages for updates.  
- Surface changes such as new papers, awards, or news.  
- Automatically publish an aggregated feed to a personal portfolio or website.  

## Tech Stack  
- **Python** for core scripting.  
- **BeautifulSoup** or **Scrapy** for crawling and parsing HTML.  
- **GitHub Actions** for scheduled scraping and automated publishing.  

## Planned Features  
- **Crawl author pages:** Traverse personal homepages and collect relevant information.  
- **Detect & surface updates:** Compare current and previous versions of pages to highlight new content.  
- **Auto‑publish to portfolio:** Generate a feed (e.g. Markdown or JSON) and commit it to a portfolio site.  

## Repository Layout (proposed)  
- `crawler/` – Python modules for scraping and parsing author homepages.  
- `data/` – Temporary storage for fetched pages and processed data.  
- `.github/workflows/` – GitHub Actions workflows for scheduled scraping and publishing.  
- `CONTRIBUTING.md` – Guidelines for contributing to this project.  
- `LICENSE` – Project license (MIT).  

This project is a prototype and will evolve over time. Contributions and feedback are welcome!  
