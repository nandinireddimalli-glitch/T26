# 📊 Explore Google Analytics 4 Reports

**Digital Marketing Track – Task** · Reddi Malli Nandini

Analysis of the official **GA4 demo property (Google Merchandise Store)** to identify key
**acquisition, engagement, and conversion** metrics and turn them into marketing insights.

---

## 🎯 Objective
Learn the fundamentals of web analytics using Google Analytics 4.

## 🛠️ Tools
- Google Analytics 4 (Demo Account – Google Merchandise Store web data stream)

## 📁 Repository Structure
```
ga4-report-analysis/
├── README.md                  # Project overview + summary of findings
├── report/
│   └── GA4_Report_Analysis.pdf   # Full report (traffic, engagement, conversions, insights)
├── screenshots/               # GA4 report screenshots (see index below)
└── linkedin-post.md           # LinkedIn post text
```

## 🔎 How I Accessed the Data
1. Opened the **Google Analytics Help → "Demo account"** page and clicked *Access demo account*.
2. Selected the property **GA4 – Google Merchandise Store**.
3. Set the date range to **[e.g. Last 28 days]**.
4. Explored the reports listed below and captured screenshots.

## 📘 Key Metrics Explained
| Metric | Meaning |
|---|---|
| Users / Active users | Distinct people who visited (active = had an engaged session) |
| New users | First-time visitors in the date range |
| Sessions | Group of interactions; ends after 30 min of inactivity |
| Engaged session | 10+ seconds, a key event, or 2+ page views |
| Engagement rate | Engaged sessions ÷ sessions (opposite of bounce rate) |
| Avg. engagement time | Time the site was in focus, per active user |
| Key event | Important action, e.g. `purchase` (formerly "conversion") |

## 🚦 1. Traffic-Source Analysis
**Report:** Acquisition → Traffic acquisition (Session default channel group)

| Channel | Sessions | Engagement rate | Key events |
|---|---|---|---|
| Direct | | | |
| Organic Search | | | |
| Paid Search | | | |
| Referral | | | |
| Unassigned | | | |

**Finding:** _[e.g. Direct + Organic Search bring X% of sessions; Paid Search has the highest engagement rate.]_

## 👀 2. Engagement Analysis
**Reports:** Engagement → Overview, Pages and screens, Events

- Avg. engagement time per active user: **[ ]**
- Top pages: **[1, 2, 3]**
- Top events: `page_view`, `user_engagement`, `session_start`, `scroll`, `view_item`
- Device split (desktop vs mobile): **[ ]**

**Finding:** _[ ]_

## 🛒 3. Conversion Observations
**Reports:** Engagement → Key events · Monetization → Ecommerce purchases, Purchase journey

| Step | Active users | Drop-off |
|---|---|---|
| Session start | | – |
| View product | | |
| Add to cart | | |
| Begin checkout | | |
| Purchase | | |

**Finding:** _[e.g. Only X% of sessions purchase; biggest drop is cart → checkout.]_

## 💡 4. Five Marketing Insights
1. **Organic & direct traffic carry the store** → invest in SEO for product/category pages.
2. **Untracked ("Unassigned") traffic hides real sources** → add UTM tags to all campaign links.
3. **The cart is where buyers are lost** → cart-abandonment emails, earlier shipping info, guest checkout.
4. **Mobile under-converts vs desktop** → simplify mobile checkout, improve page speed.
5. **A few pages/products drive most value** → feature best sellers and retarget product viewers.

_(Each insight is backed by numbers in the full report.)_

## 🖼️ Screenshots
| # | File | Report |
|---|---|---|
| 1 | `screenshots/01-home-property.png` | Home – property selected |
| 2 | `screenshots/02-reports-snapshot.png` | Reports snapshot |
| 3 | `screenshots/03-traffic-acquisition.png` | Traffic acquisition |
| 4 | `screenshots/04-engagement-overview.png` | Engagement overview |
| 5 | `screenshots/05-pages-and-screens.png` | Pages and screens |
| 6 | `screenshots/06-events.png` | Events |
| 7 | `screenshots/07-key-events.png` | Key events |
| 8 | `screenshots/08-ecommerce-purchases.png` | Ecommerce purchases |
| 9 | `screenshots/09-purchase-journey.png` | Purchase journey |
| 10 | `screenshots/10-tech-details.png` | Tech details (device) |

![Traffic acquisition](screenshots/03-traffic-acquisition.png)

## ✅ Learnings
- GA4 is **event-based**: users, sessions and engagement are all built from events.
- **Engagement rate** replaced bounce rate as the main quality signal.
- Good analytics means connecting a number to a **business action**.

## 👤 Author
**Reddi Malli Nandini**
[LinkedIn](https://www.linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)
