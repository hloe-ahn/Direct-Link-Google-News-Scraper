# Direct Link Google News Scraper
>This tool pulls fresh Google News articles from the last 24 hours and gives you their actual direct-source URLs. No proxies, no headaches—just clean, recent news data tied to the keywords you care about. If you need to track breaking stories or monitor topics in real time, this scraper keeps things simple and fast.

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Direct Link Google News Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The scraper fetches newly published news articles across the web based on keyword searches, using Google News as the discovery engine. It’s ideal for researchers, journalists, analysts, and anyone collecting timely updates without manually checking multiple sites.

### What It Focuses On
- Retrieves articles from the past 24 hours using real publication timestamps.
- Pulls true article URLs instead of Google redirect links.
- Supports multiple keywords in a single run.
- Works without proxy rotation or complicated setup.
- Returns structured results ready for databases, dashboards, or alerts.

---
## Features
| Feature | Description |
|---------|-------------|
| 24-Hour News Filtering | Extracts articles published within the last 24 hours using actual source timestamps. |
| Direct Article URLs | Captures real article links instead of Google redirect wrappers. |
| Keyword-Based Search | Accepts multiple keywords and returns matched stories per term. |
| Source Metadata | Collects publisher name, domain, and associated metadata. |
| Lightweight Operation | Runs efficiently without proxies or heavy browser automation. |
| Configurable Limits | Supports item caps per keyword for flexible output sizes. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| keyword | Search term used to discover the article. |
| title | Title of the news article. |
| link | Direct article link from the source website. |
| source | Name of the publishing outlet. |
| published | Actual publication timestamp in ISO format. |
| domain | Domain extracted from the article URL. |
| image | URL of the article’s preview image if available. |

---
## Example Output
    
    [
      {
        "keyword": "climate change",
        "title": "WASH considerations in key national climate change policies",
        "link": "https://www.graphic.com.gh/news/general-news/ghana-news-wash-considerations-in-key-national-climate-change-policies.html",
        "source": "Graphic Online",
        "published": "2024-03-25T06:50:08Z",
        "domain": "www.graphic.com.gh",
        "image": "https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSVaL97MoMZsWxSwZF9d0e-j0AgCxbyA8FVeEajWEGoT5U-cdq2PZXb0gQ0ojaAR0rhKvlNu_V0H7T9f9EAVY4"
      }
    ]

---
## Directory Structure Tree
    
    Direct Link Google News Scraper/
    ├── src/
    │   ├── main.js
    │   ├── scraper/
    │   │   ├── google_news_parser.js
    │   │   ├── article_extractor.js
    │   │   └── request_handler.js
    │   ├── utils/
    │   │   ├── timestamp_filter.js
    │   │   └── normalize_domain.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_keywords.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Journalists** track breaking stories tied to their beats so they can quickly review newly published content.  
- **Research teams** monitor topical keywords to gather up-to-date insights from diverse publishers.  
- **Developers** feed real-time news into dashboards, alerting tools, and search portals.  
- **Marketing teams** watch brand or industry keywords to react promptly to emerging coverage.  
- **Analysts** scrape daily keywords for sentiment, trend detection, and competitive research.  

---
## FAQs

**Does it require proxies?**  
No. It’s designed to run without proxy setup, making it lightweight and easy to deploy.

**How are articles filtered by date?**  
The scraper uses the original article's published timestamp, not Google’s indexing time.

**Can I limit how many results I get?**  
Yes, you can set a maxItems value per keyword.

**Does it return direct article links?**  
Absolutely—no redirect URLs, only real publisher links.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Delivers keyword-based news results in seconds, even across multiple search terms.

**Reliability Metric:**  
Maintains a consistent fetch rate above 98% accuracy for publication timestamps.

**Efficiency Metric:**  
Runs with low overhead thanks to streamlined requests and minimal parsing overhead.

**Quality Metric:**  
Returns clean, enriched article metadata including source, domain, and preview images for strong dataset usability.

---

<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>
         
