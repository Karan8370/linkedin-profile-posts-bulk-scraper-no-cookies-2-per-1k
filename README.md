# LinkedIn Profile Posts Bulk Scraper (No Cookies)
This scraper extracts complete public posts from LinkedIn profiles and companies — including text, media, engagement, comments, and reactions — without requiring cookies or login. It enables fast, scalable access to fresh LinkedIn content for analytics, research, and outreach workflows. Built for reliability, speed, and high-volume data collection.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/za2122/footer-section/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/devpilot1" target="_blank">
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
  If you are looking for <strong>LinkedIn Profile Posts Bulk Scraper (No Cookies)⚡$2 per 1k</strong> you've just found your team — Let’s Chat. 👆👆
</p>


## Introduction
The LinkedIn Profile Posts Bulk Scraper provides a secure and efficient way to collect LinkedIn post data at scale. It solves the challenge of manually aggregating large volumes of post-level information, especially when tracking engagement trends or performing competitor and influencer analysis.

### Why This Scraper Matters
- Extracts full post details such as content, media, engagement metrics, reactions, and comments.
- Does not require login or cookies, reducing friction and eliminating account risk.
- Supports high concurrency, processing multiple profiles simultaneously.
- Helps marketing, sales, and research teams collect structured LinkedIn insights quickly and safely.
- Returns fresh, uncached data for accurate analysis.

## Features
| Feature | Description |
|---------|-------------|
| No Login Required | Access publicly visible LinkedIn posts without cookies or account authentication. |
| High Concurrency | Scrapes up to 6 profiles or companies at a time for faster throughput. |
| Full Post Extraction | Captures text, media, documents, engagement, author info, and timestamps. |
| Reactions Scraping | Optional extraction of reactions, including reaction types and reacting users. |
| Comments Scraping | Optional extraction of comments with full author info and timestamps. |
| Flexible Pagination | Supports scraping all posts or limiting by maximum post count. |
| Content Filters | Toggle inclusion of reposts and quote posts based on your needs. |
| Fast Output Delivery | Returns structured post data in seconds with no caching. |
| Multi-Format Export | Export data as JSON, CSV, XLS, or use via API. |

---

## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|------------------|
| type | Indicates whether the item is a post, reaction, or comment. |
| id | Unique ID of the LinkedIn post or interaction. |
| linkedinUrl | Direct link to the post. |
| content | Full text content of the post. |
| author | Object containing author details, name, profile URL, avatar, and headline. |
| postedAt | Timestamps, date, and relative time indicators. |
| postImages | List of images included in the post. |
| document | Document metadata for posts containing PDFs or attachments. |
| engagement | Counts for likes, comments, shares, and detailed reaction breakdowns. |
| reactions | Individual reaction objects with type and actor information. |
| comments | Full comment objects with text, user data, timestamps, and related metrics. |

---

## Example Output

    [
      {
        "type": "post",
        "id": "7329207003942125568",
        "linkedinUrl": "https://www.linkedin.com/posts/williamhgates_how-better-data-helped-us-cut-child-mortality",
        "content": "The leading causes of childhood death reveal a stark truth...",
        "author": {
          "name": "Bill Gates",
          "publicIdentifier": "williamhgates",
          "linkedinUrl": "https://www.linkedin.com/in/williamhgates",
          "info": "Chair, Gates Foundation and Founder, Breakthrough Energy"
        },
        "postedAt": {
          "timestamp": 1747419119821,
          "date": "2025-05-16T18:11:59.821Z"
        },
        "postImages": [],
        "engagement": {
          "likes": 2916,
          "comments": 328,
          "shares": 153
        }
      }
    ]

---

## Directory Structure Tree

    linkedin-profile-posts-bulk-scraper-no-cookies/
    ├── src/
    │   ├── runner.py
    │   ├── extractors/
    │   │   ├── linkedin_posts_parser.py
    │   │   ├── reactions_parser.py
    │   │   ├── comments_parser.py
    │   │   └── utils_time.py
    │   ├── outputs/
    │   │   └── exporters.py
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── inputs.sample.txt
    │   └── sample.json
    ├── requirements.txt
    └── README.md

---

## Use Cases
- **Market analysts** aggregate competitor and industry leader posts to monitor trends and engagement patterns.
- **Sales and outreach teams** collect posts from prospects to personalize communication and timing.
- **Researchers** analyze public sentiment, reactions, and comment behavior using structured LinkedIn data.
- **Influencer marketing teams** track performance metrics of company or creator posts for campaign evaluation.
- **Content strategists** benchmark engagement across similar profiles to refine content planning.

---

## FAQs

**Do I need a LinkedIn account or cookies to use this tool?**
No. The scraper works without login or cookie authentication and only accesses publicly visible content.

**Can it extract all reactions and comments?**
Yes. By setting `maxReactions` or `maxComments` to `0`, the scraper retrieves all available reactions and comments.

**Does it include reposts or quote posts?**
You can toggle both `includeReposts` and `includeQuotePosts` depending on your needs.

**How fresh is the data?**
All content is scraped live on request, with no caching involved.

---

## Performance Benchmarks and Results
**Primary Metric:** Average extraction speed processes 6 profiles concurrently, typically returning results within seconds.
**Reliability Metric:** Stable scraping with a high success rate across profiles and company pages.
**Efficiency Metric:** Optimized throughput enables bulk retrieval of posts, reactions, and comments with minimal overhead.
**Quality Metric:** Captures a complete data model including media, documents, author information, and full engagement metadata for high-accuracy analysis.


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
        <img src="https://github.com/za2122/footer-section/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtube.com/shorts/6AwB5omXrIM" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review3.gif" alt="Review 3" width="35%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Exceptional results, clear communication, and flawless delivery. Bitbash nailed it.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
