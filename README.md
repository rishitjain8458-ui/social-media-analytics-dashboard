# SocialLens 🔍

> **See clearly. Analyse smarter. Grow faster.**

A professional social media analytics dashboard that turns raw Instagram and YouTube CSV data into actionable insights — built entirely with HTML, CSS, and JavaScript. No backend. No login. Just upload and go.

🔗 **Live Demo:** [rishitjain8458-ui.github.io/social-media-analytics-dashboard](https://rishitjain8458-ui.github.io/social-media-analytics-dashboard)

---

## What It Does

SocialLens takes your Instagram and YouTube performance data and gives you a full analytics suite in seconds — including creator rankings, top reel tracking, strategic recommendations, and a professional PDF export.

Built as a portfolio project by a BBA Marketing Analytics student to demonstrate real-world data analysis and dashboard design skills.

---

## Features

| Feature | Description |
|---|---|
| 📊 **Overview Tab** | Combined Instagram + YouTube view with 6 paired KPI cards |
| 📸 **Instagram Analytics** | Engagement, reach, impressions, follower growth, saves vs comments |
| ▶️ **YouTube Analytics** | Views, watch time, CTR trend, subscribers gained, likes vs comments |
| 🏆 **Creator Leaderboard** | Ranks top creators by total likes and average reel performance |
| 🎬 **Top Reels Tracker** | Best performing Reels ranked by likes, saves, shares and engagement rate |
| 💡 **Strategic Recommendations** | 6 data-driven recommendations generated from your actual numbers |
| 📈 **Industry Benchmarks** | Compares your metrics against industry averages with visual progress bars |
| 📄 **PDF Export** | Clean 4-page professional report — KPIs, creator leaderboard, top reels, recommendations |
| 🎨 **Dark UI** | Minimal dark theme built with Chart.js and Google Fonts |

---

## How To Use

### Option 1 — Try Sample Data
1. Open the live link above
2. Click **"Load sample data with creators"**
3. Click **Generate Dashboard**

### Option 2 — Upload Your Own Data
1. Export your Instagram data from Meta Business Suite as CSV
2. Export your YouTube data from YouTube Studio as CSV
3. Upload both files on the SocialLens upload screen
4. Enter your brand name and click **Generate Dashboard**

---

## CSV Format Required

**Instagram CSV**
```
date, post_type, creator, likes, comments, shares, saves, reach, impressions, followers
```
- `post_type` accepts: `Reel`, `Carousel`, `Static Post`, `Story`
- `creator` is optional — add @handles to unlock the Creator Leaderboard
- `date` format: YYYY-MM-DD

**YouTube CSV**
```
date, video_title, views, watch_time_hours, likes, comments, subscribers_gained, ctr, avg_view_duration
```
- `ctr` is a percentage value e.g. `5.2`
- `date` format: YYYY-MM-DD

---

## Project Structure

```
social-media-analytics-dashboard/
│
├── index.html                   # SocialLens — full dashboard
├── instagram_sample_data.csv    # Sample Instagram data with creator column
├── youtube_sample_data.csv      # Sample YouTube data
└── README.md                    # You are here
```

---

## Built With

| Tool | Purpose |
|---|---|
| HTML / CSS / JavaScript | Core structure and styling |
| Chart.js | All interactive charts |
| PapaParse | CSV parsing |
| jsPDF | PDF report generation |
| Google Fonts — Syne + DM Sans | Typography |

---

## About the Creator

**Rishit Jain**
BBA — Finance & Marketing Analytics
Christ University, Bangalore

Currently interning at **Clapingo** with a focus on email marketing and marketing analytics. Building this portfolio to demonstrate hands-on skills in data analysis, dashboard design, and marketing technology.

- 📍 Bangalore, India
- 🎓 Christ University — BBA Finance & Marketing Analytics
- 💼 Marketing Analytics Intern @ Clapingo

---

## Portfolio Roadmap

| # | Project | Status |
|---|---|---|
| ✅ 1 | SocialLens — Social Media Analytics Dashboard | **Live** |
| 🔲 2 | Email Marketing Analyzer | Coming Soon |
| 🔲 3 | Customer Segmentation Dashboard | Coming Soon |
| 🔲 4 | SEO & Web Traffic Tracker | Coming Soon |
| 🔲 5 | Marketing Mix Optimizer | Coming Soon |

---

*Built with curiosity, Chart.js, and way too many CSV files.*
