![Reddit Ads Scraper](https://lexis-solutions-apify.fra1.cdn.digitaloceanspaces.com/banners/reddit-ads.png)

## 🛒 What does Reddit Ads Scraper do?

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.8` |
| **Last Update** | Dec 1, 2025 |

---



## 💻 Integration Examples

This repository includes example code showing how to integrate the `reddit-ads-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---



Reddit Ads Scraper allows you to extract hosted ad content and stats as displayed on Reddit.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/hIHt2e63CUiKjs2mw/BuI4eIg0hyWKWUAGa-Icon.jpeg" alt="Reddit Ads Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/reddit-ads-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


Reddit Ads Scraper transforms hosted Reddit data into a structured dataset.

Its results include:

<table>
<tr>
<td>✅ Headline</td>
<td>✅ Ad text</td>
</tr>
<tr>
<td>✅ Budget category</td>
<td>✅ Industry</td>
</tr>
<tr>
<td>✅ Created at</td>
<td>✅ Post URL</td>
</tr>
</table>

## 🌊 How do I use Reddit Ads Scraper to extract data?

Reddit Ads Scraper is designed to be user-friendly, even for those who have never extracted data from the web before. Here’s how you can scrape data from Reddit with this tool:

1. [Create](https://console.apify.com/sign-up) a free Apify account using your email.
2. Open [Reddit Ads Scraper](https://console.apify.com/actors/lexis-solutions/reddit-ads-scraper).
3. Enter the subreddit URL you want to scrape Reddit ads from.
4. Click the “Start” button and wait for the data to be extracted.
5. Download your data in JSON, XML, CSV, Excel, or HTML.

## ⬇️ Input

The input for Reddit Ads Scraper is a search query, and optional filters for budget category, industry, and objective type.

Example input:

```json
{
  "query": "crypto",
  "budgetCategory": "MEDIUM",
  "industry": "TECH_B2C",
  "objectiveType": "AWARENESS"
}
```

## What are the input filter options?

- **query**: Keywords to search for specific ads. Leave empty for all ads.
- **budgetCategory**: Filter ads by budget category (LOW, MEDIUM, HIGH).
- **industry**: Filter ads by industry (TECH_B2C, FINANCE, etc.).
- **objectiveType**: Filter ads by objective type (AWARENESS, CONVERSIONS, APP_INSTALLS, TRAFFIC, VIDEO_VIEWABLE_IMPRESSIONS).

## ⬆️ Output sample

The scraped data will be shown as a dataset which you can find in the **Storage** tab. Here’s an excerpt from the dataset you can get when applying the input parameters above:

And here is the same data but in JSON. You can choose in which format to download your Reddit data: JSON, JSONL, Excel, HTML table, CSV, or XML.

```json
{
  "id": "aef36f01740c13b03b1d19476eb5a8c0",
  "post_url": "https://www.reddit.com/r/u_GoldFire33/comments/18um8lt/weve_been_working_for_3_years_on_this_scifi/",
  "headline": "We've been working for 3 years on this sci-fi adventure where your only companion in the arctic is a court-mandated therapy bot!",
  "profileName": "u_GoldFire33",
  "budget_category": "LOW",
  "industry": "OTHER",
  "created_at": "2023-12-30T18:34:14+00:00",
  "type": "VIDEO", // TEXT, IMAGE, CAROUSEL, VIDEO
  "content": ["https://v.redd.it/ya50e0bmm3rc1/DASH_1080.mp4?source=fallback"]
}
```

## Limitations

The Reddit Ads Scraper can only scrape up to **30 ads** per run. Those are the top ads in the last 365 days shown on the platform. Due to Reddit's data policy, **no more than 30 ads can be scraped**.

Still, you can scrape multiple queries and combine the results in a dataset. Furthermore, you can track ads over time to see how they evolve.

Scheduling the Reddit Ads Scraper is easy using the Apify platform.

## ❓FAQ

### Can I use this tool for free?

With the Apify Free plan, you get $5 worth of credits every month. You can use the Reddit Ads Scraper with the free trial option, after which you can upgrade to a paid plan.

### **How much does it cost?**

The cost for using the Google Ads Scraper is shown on the top of this page. You can also check the Apify Store page for more information.

## Need to scrape ads from other platforms?

👉 Scrape Google ads with [Google Ads Scraper](https://apify.com/lexis-solutions/google-ads-scraper)

👉 Scrape Bing ads with [Bing Ads Scraper](https://apify.com/lexis-solutions/bing-ads-scraper)

👉 Scrape TikTok ads with [TikTok Ads Scraper](https://apify.com/lexis-solutions/tiktok-ads-scraper)

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!

Image Credit: Google Transparency Center
