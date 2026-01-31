# Web Crawler Collections

This repository is a curated collection of related projects focused on web crawling, search result collection, and ranking analysis. Each project is maintained as an independent repository and is referenced here to provide a clear overview of the systems and technologies involved.

## Projects

### [SECmp (Search Engine Ranking Comparator)](https://github.com/zhichzhang/secmp)
**SECmp** collects top search results from multiple search engines and compares
their rankings against Google as a baseline, measuring relevance overlap and
rank correlation.

**Programming Language**
- Python

**Libraries / Tools**
- requests
- BeautifulSoup (beautifulsoup4)
- Selenium
- JSON / CSV processing
- I/O-bound search result collection pipeline

### [News Site Crawler](https://github.com/zhichzhang/news-site-crawler)
A multi-threaded, domain-restricted crawler designed to ingest and analyze
large-scale news websites, producing structured crawl logs and coverage
analytics.

**Programming Language**
- Python

**Libraries / Tools**
- requests
- BeautifulSoup (beautifulsoup4)
- pandas
- concurrent.futures (ThreadPoolExecutor)